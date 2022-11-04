## 说明
本仓库源码来自 [wyveo/nginx-php-fpm](https://github.com/wyveo/nginx-php-fpm)

本人添加了`sqlite3`  开启了 `sqlite3` 和 `mbstring` 插件

## 生成镜像

拉取仓库

```
$ git clone https://github.com/fukoy/nginx-php-fpm.git
$ cd nginx-php-fpm
```

生成镜像
```
$ docker build -t nginx-php-fpm:php7.4 . # PHP 7.4.x
```

## 拉取镜像
```
$ docker pull fukoy/nginx-php-fpm:php7.4
```

## 运行
运行镜像
```
$ sudo docker run -d fukoy/nginx-php-fpm:php7.4
```

默认网站目录
```
/usr/share/nginx/html
```
