# 介绍
一个sinopia服务的docker镜像 用于创建私有npm库

# 使用

## 创建Image

```bash
cd docker
docker build -t sinopia .
```

## 创建container

```bash
./start_sinopia_docker.sh
```

## 进入container

```bash
docker ps -a # 查看container id
docker exec -it CONTAINER_ID bash
```

## 修改sinopia服务配置
修改conf/sinopia.yaml
[配置详解](https://segmentfault.com/a/1190000005790827)


