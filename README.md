Ubuntu based container with MongoDB

## Pull Images

Actually this Docker container supports:

Pull the image.

```
docker pull oscerd/mongodb
```

## Run containers

Run container

```
docker run --name container_mongodb -dt oscerd/mongodb
```

## Connect to a running container

Suppose your running container is named mongodb_test you can execute:

```
docker exec -ti mongodb_test /bin/bash
```
