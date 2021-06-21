docker-cheatsheet-headstart
# Docker Cheatsheet - Headstart

## 100 - Docker commands

### 100 - Docker Build commands

### 200 - Docker Run commands

#### 100 - Check Running Processes

```
$ docker ps
```

#### 200 - Remove all Docker containers

```
$ docker rm $(docker ps -aq)
```

#### 300 - Stop and force remove all containers

```
$ docker-compose stop ; docker-compose rm -f
```

#### 400 - View logs of a container

```
$ docker logs [CONTAINER ID]
```

### 300 - Docker Share commands

## 200 - Docker Compose commands

### 100 - Docker Compose Build commands

### 200 - Docker Compose Run commands

#### 100 - Check Running Processes

```
$ docker-compose ps
```

### 300 - Docker Compose Share commands
