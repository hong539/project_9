# MongoDB

* version
    * 6.0.11

```shell
#6.0.11-ubi8
docker run --name mongodb -d -p 27017:27017 -e MONGODB_INITDB_ROOT_USERNAME=user -e MONGODB_INITDB_ROOT_PASSWORD=passwd mongo:6.0.11

podman run --name mongodb -d -p 27017:27017 -e MONGODB_INITDB_ROOT_USERNAME=user -e MONGODB_INITDB_ROOT_PASSWORD=passwd docker.io/mongo:6.0.11
```