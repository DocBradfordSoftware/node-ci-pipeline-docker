# node-ci-pipeline-docker


### Setup

```bash
mkdir ./data
npm install
docker-compose up
npm test
```
#### Jenkins Setup

Copy Admin Password
```bash
docker cp $JENKINS_CONTAINER_ID:/var/jenkins_home/secrets/initialAdminPassword adminpass
```

```bash
http://$DOCKER_IP:9090
```