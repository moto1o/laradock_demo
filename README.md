# laradock_demo
重写laradock,只保留laravel5.5,nginx,php,mysql模块

## 目录说明

1. app laravel应用目录
2. data MySQL数据存储目录,data/mysql目录需要有写入权限
3. laradock laravel+nginx+php+mysql运行的docker环境

## 启动环境

1. cd /laradock
2. 配置.env配置文件，来设置php和mysql的版本，以及运行环境，默认可以直接拷贝.env.example即可
3. 启动并后台运行docker: sudo docker-compose up -d

## 注意
1. laradock/workspace/crontab 目录可以设置定时任务
2. laradock/.github目录有一些帮助文档
