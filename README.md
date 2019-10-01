# Services

This repo contains a `docker-compose.yml` that helps you run all auxilliary
services for Aroundhome.

The services are configured to the versions we are using in production.

## Usage

### Run all database services as a daemon
```sh
$ docker-compose up -d
```

### Stop all services
```sh
$ docker-compose stop
```

*You can run all services in one terminal session and stop them in another.*
