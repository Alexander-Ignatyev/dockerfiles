# Dockerfiles

Various docker files I use.

Docker hub: https://hub.docker.com/u/alexignatyev/


## Building and publishing Docker images

```
% cd mltool-deps
% docker build -t alexignatyev/mltool-deps[:tag]  # tag is not required, "latest" by default
% docker images
% docker push alexignatyev/mltool-deps[:tag]
```
