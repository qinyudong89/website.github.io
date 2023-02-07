---
title: "MySQL 数据迁移"
date: 2023-02-06T08:20:30-04:00
categories:
  - blog
tags:
  - MySQL
---
### 前言
相信大部分有 3 - 5 年开发经验的同学都会经历过数据迁移，比如从机房到云数据库或单库到多库多表。那么今天我就来讲一下 MySQL 数据库的迁移方案中的其中两种：双写方案、级联同步方案。


### 参考

[数据库的迁移该如何做](https://time.geekbang.org/column/article/155138)