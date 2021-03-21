# TIG Stack

The combination of Telegraf, Influxdb and Grafana to be provisioned on a VM to be the monitering service

* Telegraf 
* Influxdb 
* Grafana 

## Prerequisites

* VM Running locally or running in the cloud
* Docker

## How to deploy

Clone the repository
```
git clone https://github.com/skuxxdeluxxe/tigstack.git
```

Go into the directory and run docker compose
```
cd tigstack
sudo docker-compose up -d
```