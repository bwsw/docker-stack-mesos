# docker-stack-mesos
Docker stack for mesos deployment

## Features:
- native docker stack
- reloading fallen services of mesos
- test your environment in mesos
- customizing stack for your needs

## Use:
#### Start
To start mesos stack use `docker stack deploy` command:
```
docker stack deploy -c <path/to/stack/file> mesos
```
This command up mesos services in docker containers.

#### Stop
To stop mesos stack use `docker stack rm` commad:
```
docker stack rm mesos
```
This command remove all services in stack.

## Roadmap:
