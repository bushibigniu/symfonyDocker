# symfonyDocker
This is used Docker to deploy Symfony project.
docker-compose 常用的操作命令。

docker-compose build restart

//重启
docker-compose restart php

//docker 如何查看已存在的容器所挂载的目录
docker inspect container_name | grep Mounts -A 20

//进入容器
docker-compose exec php-fpm sh

docker-compose images









