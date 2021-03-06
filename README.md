# Villo
Data streaming and viewings from Brussel Open Data / Open Weather Data through the Confluent stack. Producers are Python scripts using `confluent_kafka` lib to provide the weather and bike stations every 30s. 

## Getting started
### Prerequisities
You 'll need to install Docker : 
- [Windows](https://docs.docker.com/docker-for-windows/)
- [Linux](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- [OS X](https://docs.docker.com/docker-for-mac/)

### Usage
Compose the Docker :
```shell
docker-compose up -d
```
Watch active containers :
```shell
docker ps
```
<p align="center"><img src="https://github.com/robincvlr/villo/blob/master/resources/process.PNG" width=1300></p>

Kibana is reachable at : http://<DOCKER_MACHINE_IP>:5601

### Architecture
<p align="center"><img src="https://github.com/robincvlr/villo/blob/master/resources/schematic.png" width=500></p>

### Brussel Opendata
[API](https://opendata.bruxelles.be/explore/dataset/stations-villo-disponibilites-en-temps-reel/information/)

### Open Weather Map
[API](https://openweathermap.org/api)

### Visualisation
![](https://github.com/robincvlr/villo/blob/master/resources/screen_kibana.png)

