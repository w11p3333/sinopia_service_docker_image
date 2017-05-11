FROM hub.c.163.com/public/nodejs:5.7.0

MAINTAINER luliangxiao <luliangxiao@corp-ci.com>

#安装nodejs npm sinopia pm2 nrm
RUN npm install -g sinopia
# 每次启动启动sinopia服务
ENTRYPOINT /conf/run_sinopia_service.sh
