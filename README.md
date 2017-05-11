# Introduce
easy build your private npm by using docker image

![](http://7xtc17.com1.z0.glb.clouddn.com/Snip20170511_36.png)

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

