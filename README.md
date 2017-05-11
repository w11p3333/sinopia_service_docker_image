# Introduce
easy build your private npm by using docker image

# Usage

## Create Image

```bash
cd docker
docker build -t sinopia . # image named 'sinopia'
```

## Start Container

```bash
./start_sinopia_docker.sh
```

## Enter Container

```bash
docker ps -a # Get your Container ID
docker exec -it CONTAINER_ID bash
```

## .yaml Config

modify ```conf/sinopia.yaml```

