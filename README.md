# MQTT Server and Client

This project has server mosquitto (MQTT) and client

## Requirements
1. Docker
2. Python3>

## Configurations
* Configure *.env* with enviroment variables. You can rename *example.env* to *.env*

```
    BROKER=
    PORT_BROKER=
    USER_MQTT=
    PWD_MQTT=
    URLPOST_BACKEND=
```
## Installations

1. Install paho-mqtt, you need python 3 at least

```
pip3 install paho-mqtt
```
2. Install python-dotenv

```
pip3 install python-dotenv
```
## Run MQTT server

1. Open folder mosquitto
```
cd mosquitto
```
2. Exec docker container
```
docker-compose up -d
```

## Run MQTT Client

1. Run python client 

```
python3 mqtt-client.py
```