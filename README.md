# node-less

docker image for nodejs less command, see [appleboy/node-less](https://hub.docker.com/r/appleboy/node-less/) image from docker hub.

## Build Image

1. clone the source code.

```sh
$ git clone https://github.com/appleboy/node-less.git
```

2. Build image

```sh
$ docker build -t appleboy/node-less .
```

## Run Less Command

```sh
$ docker run --rm -v `pwd`:/app -ti appleboy/node-less styles.less > styles.css
```
