---
title: 设置git用户信息
date: 2020-12-18
categories:
 -tools
tags:
 -git
---

```shell
# git config命令的–global参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。
 
# 查看git配置信息
$ git config --list
 
 
# 2.查看git用户名、密码、邮箱的配置
$ git config user.name
$ git config user.password
$ git config user.email
 
 
# 3.设置git用户名、密码、邮箱的配置
$ git config user.name "freedom"
$ git config user.password "123456"
$ git config user.email "1548429568@qq.com"

# 4.设置git用户名、密码、邮箱的配置（全局配置）
$ git config --global user.name 用户命
$ git config --global user.name freedom
$ git config --global user.password 密码
$ git config --global user.password abc0506abc
$ git config --global user.password 邮箱
$ git config --global user.email "1548429568@qq.com"

```

