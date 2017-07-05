# docker-stack-mesos
Docker stack for mesos deployment

## Features:
- native docker stack commands
- reloading fallen services of mesos
- testing your environment in mesos
- customizing stack for your needs

## Usage:
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
This command removes all services of stack.

## Roadmap:
- add the ability to scale slaves.
- add jwilder/nginx-proxy (https://github.com/jwilder/nginx-proxy) support for naming services (working only for dockerized tasks?).
- use marathon features to prevent TASK_LOST status, after the slave is dropped.
