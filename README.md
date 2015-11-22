# 国内用户的Ubuntu Dockerfile 基于 ubuntu:14.04

1. 对ubuntu:14.04做了修改`sources.list`的操作
1. 进行`apt-get update`


源文件如下：

```
deb http://cn.archive.ubuntu.com/ubuntu/ precise main restricted universe multiverse
deb http://cn.archive.ubuntu.com/ubuntu/ precise-security main restricted universe multiverse
deb http://cn.archive.ubuntu.com/ubuntu/ precise-updates main restricted universe multiverse
deb http://cn.archive.ubuntu.com/ubuntu/ precise-proposed main restricted universe multiverse
deb http://cn.archive.ubuntu.com/ubuntu/ precise-backports main restricted universe multiverse
deb-src http://cn.archive.ubuntu.com/ubuntu/ precise main restricted universe multiverse
deb-src http://cn.archive.ubuntu.com/ubuntu/ precise-security main restricted universe multiverse
deb-src http://cn.archive.ubuntu.com/ubuntu/ precise-updates main restricted universe multiverse
deb-src http://cn.archive.ubuntu.com/ubuntu/ precise-proposed main restricted universe multiverse
deb-src http://cn.archive.ubuntu.com/ubuntu/ precise-backports main restricted universe multiverse
```
