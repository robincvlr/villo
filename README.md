# Villo
Data streaming and viewings from Brussel Open Data through the Confluent stack. 

## Getting started
### Prerequisities
You 'll need to install Docker : 
- [Windows](https://docs.docker.com/docker-for-windows/)
- [Linux](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- [OS X](https://docs.docker.com/docker-for-mac/)

### Usage
Pull the Docker image :
```shell
docker pull rbcvlr/villo
```

Build the Docker image
```shell
docker build -t villo .
```

Run the Docker image
```shell
docker run villo
```
Kibana is reachable at : http://<DOCKER_MACHINE_IP>:5601

### Architecture


