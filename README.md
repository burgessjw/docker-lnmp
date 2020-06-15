# docker-lnmp

基于docker的lnmp开发环境

版本说明：

- linux:	alpine
- php：		7.3.12
- nginx:	1.14.2
- redis:	4.0.12
- mysql:	5.7.24

参考`.env.example`创建`.env`文件
```
cp .env.example .env
```

参考`docker-compose.local.yml.example`创建`docker-compose.local.yml`文件
```
cp docker-compose.local.yml.example docker-compose.local.yml
```

根据需要创建nginx的配置文件`nginx/sites.conf.template`

启动服务
```
docker-compose up -d
```