- “works on my machine” -problem
- isolated environments
- development environment
- scaling
    - orchestration

## Image 

`Images` are built from `Dockerfile`

```dockerfile
FROM <image>:<tag>

RUN <install some dependencies>

CMD <command that is executed on `docker container run`>
```

## Container

## CLI

| command | explain | shorthand  |
|---|---|---|
| `docker image ls` | Lists all images | `docker images` |
| `docker image rm <image>` | Removes an image | `docker rmi` |
| `docker image pull <image>` | Pulls image from a docker registry | `docker pull`|
| `docker container ls -a` | Lists all containers | `docker ps -a` |
| `docker container run <image>` | Runs a container from an image | `docker run` |
| `docker container rm <container>` | Removes a container | `docker rm` |
| `docker container stop <container>` | Stops a container | `docker stop`|
| `docker container exec <container>` | Executes a command inside the container | `docker exec` |

```
docker image prune -a
```

"We aren’t yet familiar with the exceptions that docker system prune does not remove."

"The -d flag starts a container detached, meaning that it runs in the background."

-t will create a tty.

-i flag will instruct to pass the STDIN to the container

## Docker users group
```
sudo groupadd docker
sudo usermod -aG docker $USER
newgrp docker 
```