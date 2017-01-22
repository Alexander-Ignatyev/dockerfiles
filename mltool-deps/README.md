# mltool-deps

Contains dependenies required by [mltool](https://github.com/Alexander-Ignatyev/mltool).

## Usage

### 1. Run the image in a container

`docker run -t -i alexignatyev/mltool-deps:lts-7.14`

Docker will download image if it is still not on the Docker host.

### 2. Build the project inside the docker container:

```
% git clone https://github.com/Alexander-Ignatyev/mltool.git
% cd mltool
% stack build --system-ghc
% stack test --system-ghc
```

## Docker hub link

https://hub.docker.com/r/alexignatyev/mltool-deps/
