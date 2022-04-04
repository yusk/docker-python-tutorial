# docker

## build

```bash
docker build ./ -t docker-python-tutorial
```

## run

```bash
docker run docker-python-tutorial 

docker run -p 8000:8000 docker-python-tutorial
```

## bash

```bash
docker run -it docker-python-tutorial  /bin/bash
```

# docker-compose

## build

```bash
docker-compose build
```

## run

```bash
docker-compose up
```

## exec

```bash
docker-compose exec app bash
```
