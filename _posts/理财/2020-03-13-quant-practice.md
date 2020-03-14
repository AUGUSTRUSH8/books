---
layout: post
title: 量化实践入门
category: 理财
keywords: 量化
---

### 获取不同的行情数据

tuShare：https://tushare.pro/
- 优势：数据齐全
- 不是缺点的缺点：要积分支持服务器建设

BaoStock：http://baostock.com/baostock/index.php/%E6%8C%87%E6%95%B0%E6%95%B0%E6%8D%AE
- 优点：快速，准确，免费
- 缺点：暂时还没体会到

### 简单策略实践

基于python的股票自动盯盘程序
- 博文地址：https://zhuanlan.zhihu.com/p/37157872
- 策略简介：使用BaoStock获取股票行情数据，实现对盘中突破10日高点，且在20日均线上股票的提示。

### vnpy在阿里云服务器上的安装

vnpy在云服务器（ubuntu）运行cta策略的详细方法
- https://zhuanlan.zhihu.com/p/91770166
- https://github.com/vnpy/vnpy/wiki/%E9%98%BF%E9%87%8C%E4%BA%91%E6%9C%8D%E5%8A%A1%E5%99%A8%E5%AE%89%E8%A3%85vn.py%EF%BC%88Ubuntu-16.04-LTS%EF%BC%89
- 注意内存的问题，要求至少4个G，否则报错