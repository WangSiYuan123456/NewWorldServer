# NewWorldServer
(最后一次更新时间2026.8.1 15:14)

## 1 构建及编译

本服务器目前仅支持Windows操作系统，通过cmake进行构建和编译

本系统的通信框架使用sougou的workflow框架（通过源码构建，可以在github拉取仓库后，切换到windows分支，workflow对windows的支持没有linux那么好）

workflow依赖OpenSSL

在windows上编译workflow源码时，必须使用OpenSSL1.1.1版本，如果使用其他版本，在使用cmake构建workflow时，无法找到OpenSSL的关键库文件

OpenSSL1.1.1的安装程序在env目录下可见"Win64OpenSSL-1_1_1i.msi"

## 使用的第三方库

spdlog

workflow



