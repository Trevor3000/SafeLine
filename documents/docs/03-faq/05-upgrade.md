---
title: "升级问题"
---

# 升级问题

记录常见的升级问题

## 升级提示目录不对

在错误的目录下执行（比如 safeline 的子目录）会导致无法升级成功。

切换目录到安装目录下再次执行升级,默认目录为：/data/safeline。

## 配置的备份与恢复（还原）

升级过程担心配置受到影响

备份：备份安装目录的全部文件,默认目录为：/data/safeline

恢复（还原）：把备份的内容放回安装目录执行 `docker compose down && docker compose up -d`，重新启动雷池


## 升级过程中下载超时

网络问题导致，建议等待网络稳定或者尝试离线升级。

## 升级后系统信息显示 api 错误或者 docker 状态显示异常

重启 docker

## 升级后原配置不生效

极少数情况出现，一般删掉重新配置即可

## 问题无法解决

1. 通过右上角搜索检索其他页面

2. 通过社群（官网首页加入微信讨论组）寻求帮助或者 Github issue 提交反馈，并附上排查的过程和截图
