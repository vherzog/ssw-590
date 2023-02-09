# Homework 2: My first Docker container

Followed the Docker guide [found here](https://www.codingforentrepreneurs.com/blog/simple-docker/).

## How to run

To build the container image:
```
$ docker build -t hello-world -f Dockerfile .
```

To see a list of images on your system:
```
$ docker images
```

To see the containers currently running:
```
docker ps -a
```

To run the container image built in first step:
```
docker run -it hello-world
```
