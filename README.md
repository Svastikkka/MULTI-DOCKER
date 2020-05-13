<h1>Micro Services App</h1>

[![Build Status](https://travis-ci.org/Svastikkka/multi-docker.svg?branch=master)](https://travis-ci.com/Svastikkka/multi-docker)


<span style="color:#cc0000">The top way over complicated version of a Micro Service App just to get experience with a multi container deployment with production and development  grade environment.</span>

> Combination of React, Redis, Postgres, Express and Node. Multi container app setup with docker and travis CI/CD pipeline. Using images on docker hub to deploy app directly into AWS and GCP

## Prerequisites

```
1.Make sure you have docker and docker compose installed in system
```

## Tech Stacks
* [Docker](https://www.docker.com) - Containerize app
* [Docker Compose](https://docs.docker.com/compose) - Local development environment to run tests and builds by using volumes and networks
* [Docker Hub](https://hub.docker.com/) - Convenient Images
* [NGINX](https://www.nginx.com/) - Web Server
* [Create React App](https://github.com/facebook/create-react-app) - Bootstrapping
* [Node](https://hub.docker.com/_/node) - Backend
* [Redis](https://redis.io/) - Memcached
* [PostgreSQL](https://www.postgresql.org/) - Database
* [Travis-ci](https://travis-ci.com/) - CI/CD Pipelines


### Application Architecture

Created using [App Diagram](https://app.diagrams.net/)
<div align="center">  
  <img alt="Application Architechture" src="screenshots/Travis Application Architechture.png"/>
</div>

### Development Architecture

Run following command in your terminal

```bash
docker compose up --build
```

remove --build argument if you are rerunning the app witout making any change in dockerfile and docker-compose.yml file

and you are good to go visit http://localhost:3050

Created using [App Diagram](https://app.diagrams.net/)
<div align="center">  
  <img alt="Development Architecture" src="screenshots/Travis Development Architecture.png"/>
</div>

### Deployment Architecture
Created using [App Diagram](https://app.diagrams.net/)
<div align="center">  
  <img alt="Deployment Architecture" src="screenshots/Travis Deployment Architecture.png"/>
</div>

## Screenshots
See the screenshots folder for detailed instructions.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
