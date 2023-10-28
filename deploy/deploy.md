# deploy

## how to deploy this project?

* deploy MongoDB --> backend --> frontend
    * deploy on Linux host with dev server
    * deploy on Linux host with docker
    * deploy on Render: Cloud Application Hosting for Developers

```shell
#mongodb
podman run --name mongodb -d -p 27017:27017 -e MONGODB_INITDB_ROOT_USERNAME=user -e MONGODB_INITDB_ROOT_PASSWORD=passwd docker.io/mongodb/mongodb-community-server:6.0.11-ubi8


#backend
cd server
npm install
mpm start

#frontend
cd client
npm install
mpm start

```