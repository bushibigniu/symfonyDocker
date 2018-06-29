# symfonyDocker
This is used Docker to deploy Symfony project.
docker-compose 常用的操作命令:
docker-compose build restart

//重启
docker-compose restart php

//docker 如何查看已存在的容器所挂载的目录
docker inspect container_name | grep Mounts -A 20

//进入容器
docker-compose exec php-fpm sh

docker-compose images

docker-compose down //删除所有容器 ,它也会删除你的数据容器
docker-compose start
docker-compose up
docker-compose up -d
docker-compose stop {容器名称}  //停止某个容器

docker 常用命令:
//看网络
docker network ls

//查看日志文件
docker logs {container-name}

//进入docker
docker exec -it test_mysql_1 bash


