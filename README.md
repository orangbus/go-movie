# 仿YouTube在线聚合影视
> 前提条件，已经安装了docker以及docker-compose

## 如何使用

## 1、下载源码
```
git clone https://github.com/orangbus/go-movie.git
```
如果需要支持全文检索，请使用 `docker-compose-scout.yml` 配置文件,执行下面命令
```bash
cd go-movie
cat docker-compose-scout.yml > docker-compose.yml && mkdir data
```
Tip: 在`go-movie`目录下,将`docker-compose-scout.yml`内容复制到`docker-compose.yml` 中，并且创建一个`data`的空目录
## 2、运行
```bash
cd go-movie
docker-compose up -d
```
访问：http://ip:3000

效果图
![image](./app.png)

## 3、文档地址

[https://v.orangbus.cn](https://v.orangbus.cn)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=orangbus/go-movie&type=date&legend=top-left)](https://www.star-history.com/#orangbus/go-movie&type=date&legend=top-left)
