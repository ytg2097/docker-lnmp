# docker-lnmp

#### 介绍

docker-compose 部署二次开发的织梦dedecms

#### 软件架构

nginx + php7.2 （gd模块与mysqli模块）+ mysql5.7.26


#### 安装教程

1.  git clone https://gitee.com/ytg2097/docker-lnmp.git
2.  docker-compose up -d
3.  docker cp mysql/sql.sql m.lh-esports.com_mysql:/tmp/sql.sql
4.  docker exec -it m.lh-esports.com_mysql sh
5.  mysql -u lanhai -p
6.  lanhai
7.  use lanhai;
8.  source /tmp/sql.sql;


#### 使用说明

1.  若遇到后台管理部分页面中右侧出现空白问题, 修改www/data/tplcache权限为 666

