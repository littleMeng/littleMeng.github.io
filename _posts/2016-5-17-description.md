---
layout: post
title: 邵逸凯的简历
description: "具体描述"
tags: [介绍]
---

### 教育背景

* 2009.9 - 2013.6 武汉科技大学本科，电子信息工程专业

### 技能介绍

* 能独立进行android应用程序开发，framework功能定制及修改，HAL层的接口实现
* 熟悉常用算法和数据结构
* 良好的c功底，基本的java技能
* 熟练使用linux(Ubuntu)、编写shell脚本
* 了解android基本系统架构，有阅读android源码经验
* 三年工作经验

***

### Android相关开发

* android application
    * 本地音乐播放器：歌词平滑滚动、进度条控制歌曲播放
    * 斗鱼游戏直播：抓取斗鱼直播源，利用vitamio进行播放；根据斗鱼官方API，利用弹幕烈焰使呈现弹幕。（[github地址](https://github.com/littleMeng/video-live)）
    
* android framework(version 4.4)
    * 添加SystemServer，管理开机时的网络配置
    * ethernet支持ipv6功能：状态机管理；增加ipv6地址接口；清除ipv4/ipv6地址(实现HAL层接口)
    * 修改wifi模块，支持客户端和热点共存：改动文件数量较多，主要思路是修改状态机及其相关代码，使其支持客户端和热点两种状态同时存在；根据项目需求实现定制接口，例如热点设置自身IP和DHCP的IP范围、客户端设置静态IP等等

* others
    * 熟悉NDK开发，完成动态链接库打通c和java通信(JNI)
    * adb传输速率优化
