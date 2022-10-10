---
layout:     post
title:      rabbitMQ高级特性
subtitle:   rabbitMQ
date:       2022-10-10
author:     
header-img: img/post-bg-alibaba.jpg
catalog: true
tags:
    - 中间件
---

八大特性：
1、ACK（confirm机制）
2、如何保证消息百分百投递成功
3、幂等性
4、return机制
5、限流
6、重回队列
7、TTL
8、死信队列

能解决的问题
1、生产者消息送达失败
2、重复消费
3、消息没有成功消费
4、消息N年后一直没有被销毁
5、高并发
6、消息丢失后无法找回
