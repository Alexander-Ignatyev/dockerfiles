# optimer-deps

Contains dependenies required by [optimer](https://github.com/Alexander-Ignatyev/optimer).

## Usage

### 1. Run the image in a container

`docker run -t -i alexignatyev/optimer-deps`

Docker will download image if it is still not on the Docker host.

### 2. Build the project inside the deocker container:

```
# git clone https://github.com/Alexander-Ignatyev/optimer.git
# cd optimer
# mkdir build && cd build
# export CXX=g++
# cmake ..
# make && make test
```

## Docker hub link

https://hub.docker.com/r/alexignatyev/optimer-deps/
