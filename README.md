# dockerized LNMP


修改 docker/daemon.json，设置docker的镜像库为阿里云镜像库，内容如下:

{
    "registry-mirrors" : ["https://***.mirror.aliyuncs.com"]
}

或 其他镜像仓库，如：http://f1361db2.m.daocloud.io