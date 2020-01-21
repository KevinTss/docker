# Docker

Learning sandbox for [Docker](https://www.docker.com/)

## Run any docker image

```
docker run node
```

#### Parameters

| flag | description |
| --- | --- |
| -it | Stay with the terminal open (if not, he will launch the command in the background |
| -p | Specify the port on our machine where we will listen the port of the container ex `-p 80:80` |

---

Check all containers
```
docker ps
```

| flag | description |
| --- | --- |
| -a | see also stopped containers |

check all image on my machine
```
docker images
```

## Build image based on Dockerfile

```
docker build -t <project-name> .
```
> The dot (.) is the path where is the project, in that case you should be inside the project
> Signature is: `docker build [OPTIONS] PATH | URL | -`
