# docker-project
## 开发环境docker化部署
#### 一、项目结构
```bash
code  conf  data  docker  docker-compose.yml  logs
```
* code 代码目录
* conf ngx fpm es mysql ... 的配置目录
* data mysql es redis 数据目录
* logs 日志目录

#### 二、导入镜像 或 直接编译
##### 直接编译
```bash
docker-compose build .
```
##### 也可以导入已有的镜像包
```bash
docker load -i dev_images.tar
```

#### 三、运行docker环境
```bash
docker-compose up -d
```
