---
title: MySQL8.x开启远程访问
tags:
  - mysql
categories:
  - mysql
date: 2020-10-15 09:18:00
top_img: https://cdn.jsdelivr.net/gh/mxfj/cdn/img/MySQL.png
cover: https://cdn.jsdelivr.net/gh/mxfj/cdn/img/MySQL.png
---
## Step1.首先登录进MySQL
``` 
mysql -u root -p
```
## Step2.接着选择mysql数据库
``` 
use mysql;
```
##  Step3.然后使用如下命令开启root用户远程访问权限
``` 
CREATE USER 'root'@'%' IDENTIFIED BY '你MySQL的root密码';
GRANT ALL ON *.* TO 'root'@'%';
ALTER USER 'root'@'%' IDENTIFIED WITH mysql_native_password BY '你MySQL的root密码';
``` 
##  Step4.最后刷新一下权限
``` 
FLUSH PRIVILEGES;
``` 
