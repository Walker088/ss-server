# ss-server
A shadowsocks server which wrapped by docker-compose.

## Pre-requirements

1. docker
2. docker-compose

## Usage

```bash
# 1. remember to edit the config file after copy the template
$ cp .ss_server.env.example .ss_server.env

# Start the ss server
$ docker-compose up -d

# Pause the ss server
$ docker-compose stop

# Start the ss server
$ docker-compose start

# Delete the ss server
$ docker-compose down

# Show the logs
$ docker-compose logs
```
