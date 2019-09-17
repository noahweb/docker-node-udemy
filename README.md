# docker-node-udemy

A project following the [Docker Mastery: The Complete Toolset From a Docker Captain!] (https://www.udemy.com/docker-mastery) course from [Bret Fisher!] (https://www.bretfisher.com/)


You can pull the [docker image!] (https://hub.docker.com/r/noahweb/node-udemy) running: 

```sh
docker pull noahweb/node-udemy
```


Then create a container with:
```sh
run -p 80:3000 noahweb/node-udemy
```