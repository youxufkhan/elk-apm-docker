# elk-apm-docker
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
<div align="center">
  <img width="50" src="https://ik.imagekit.io/himalayas/https://cdn-images.himalayas.app/llxlr1gio7c529kxpj6lla41ax5j" alt="Elasticsearch" title="Elasticsearch"/>
  <img width="50" src="https://cdn.iconscout.com/icon/free/png-256/free-logstash-3521553-2944971.png" alt="Logstash" title="Logstash"/>
  <img width="50" src="https://cdn.iconscout.com/icon/free/png-256/free-kibana-3628875-3030015.png" alt="Kibana" title="Kibana"/>
  <img width="50" src="https://davinciti.com/wp-content/uploads/2021/03/apm-logo-color.png" alt="APM-Server" title="apm-server"/>
</div>

This repository contains a `docker-compose.yml` file for running the Elastic Stack with APM Server on Docker.

## Prerequisites

- Docker
- Docker Compose

## Usage

1. Clone this repository.
2. Navigate to the cloned directory.
3. Run the following command:

docker-compose up -d --build


This will start the Elastic Stack with APM Server on Docker.

## Configuration

The `docker-compose.yml` file contains the following services:

- Elasticsearch
- Logstash
- Kibana
- APM Server

Each service is configured with its own image and environment variables.

## License

This repository is licensed under the MIT License.
