# Part1
## 1.1
```
CONTAINER ID   IMAGE     COMMAND                  CREATED              STATUS                      PORTS     NAMES
fc30607aa8d2   nginx     "/docker-entrypoint.…"   About a minute ago   Exited (0) 53 seconds ago             eloquent_yonath
b7534bd57169   nginx     "/docker-entrypoint.…"   About a minute ago   Exited (0) 2 seconds ago              hungry_wilbur
2a6145df4899   nginx     "/docker-entrypoint.…"   About a minute ago   Up About a minute           80/tcp    cool_knuth
```
## 1.2
```
$ docker ps -as
CONTAINER ID   IMAGE     COMMAND   CREATED   STATUS    PORTS     NAMES     SIZE
$ docker images
REPOSITORY   TAG       IMAGE ID   CREATED   SIZE
```

## 1.3
```
$ docker run -d --rm -it --name secret devopsdockeruh/simple-web-service:ubuntu
$ docker exec -it secret bash 
root@1d584a117fc1:/usr/src/app# tail -f ./text.log
Secret message is: 'You can find the source code here: https://github.com/docker-hy'
```

## 1.4
```
```

