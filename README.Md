# Docker deploy elasticsearch
[![Build Status](https://ci-next.docker.com/public/buildStatus/icon?job=compose/master)](https://ci-next.docker.com/public/job/compose/job/master/)

## Version Elasticsearch + Kibana: 7.0.2
## Version Docker 
<div >
  <img src="https://miro.medium.com/max/2400/1*zvPL19PUTMslrhXPODj_Og.png" alt="My cool logo" width=18%/>
  
  <img src="https://steemitimages.com/1280x0/http://i.imgur.com/gkBnE8Z.png" alt='docker + elasticsearch deploy' width=14% />
</div>

### * Prerequisites

### Before you continue, ensure you meet the following requirements:
* You have installed the docker leasted version.
### Download elastic_python_request:
```php
git clone https://github.com/typro33333/docker-elasticsearch.git
```
**Move to folder:**
```php
cd docker-elasticsearch
```
**Look at file docker-compose.yml and click**
**The data elasticsearch will store at volumes -> esdata -> driver_opts -> device: (you must change this dictory to your dictory)**
```php
change this device: /Users/thinh/Desktop/elasticsearch/data
```
**Then setting complete run it to deploy with cmd:**
```php
docker-compose up
```
**Wait docker download image and deploy it will take 3 min for first deploy**
**Elastic-search will have port 9200 (default) you can change it in file docker-compose.yml**
**Kibana will have port 5600 (default) you can change it in file docker-compose.yml**
### Read more docker-compose to setup to run multi node run faster 
This document: <a href='https://github.com/docker/compose'>Docker-compose</a>