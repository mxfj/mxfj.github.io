---
title: WIN10开启远程桌面服务
date: 2020-10-16 10:18:00
updated:
tags: win10
categories: windows
keywords: 
- win10
- 远程桌面
description: 如何开启win10远程桌面
top_img: https://cdn.jsdelivr.net/gh/mxfj/cdn/img/win10.jpg
cover: https://cdn.jsdelivr.net/gh/mxfj/cdn/img/win10.jpg
comments:
toc:
toc_number:
auto_open:
copyright:
copyright_author:
copyright_author_href:
copyright_url:
copyright_info:
mathjax:
katex:
aplayer:
highlight_shrink:
---

>  其实网络上的教程很多，但是没有几个能完整的展示这个实现的过程，所以我重新整理了一下，希望看客门能在观看完本篇文章学习到如技能：如何开启本地Windows10的远程管理服务

## Step1.设置电脑密码

>> 给自己需要连接的电脑设置一个电脑用户名密码
1. 右键我的电脑打开"计算机管理"，也可以使用如下快捷方式通过CMD运行打开"计算机管理"
```bash 
compmgmt
``` 
2. 在"计算机管理"-"系统工具"-"本地拥护和组"-"用户"下找到自己电脑登录的用户名,推荐使用administrator，右键设置密码
![avatar](https://cdn.jsdelivr.net/gh/mxfj/cdn/img/WIN10KQYCZM1.jpg)
## Step2.开启windows远程连接服务
1. 右键此电脑（我的电脑）点击属性，或进入控制面板-系统；
2. 在系统界面，点击远程桌面。
3. 远程桌面选项下，选择允许远程连接到此计算机。
![avatar](https://cdn.jsdelivr.net/gh/mxfj/cdn/img/WIN10KQYCZM2.jpg)

## Step3.配置防火墙
1. 最简单的可以直接关闭防火墙（官方不推荐）
   PS：如果没有什么高安全审计啥的个人推荐关闭防火墙"享受如丝般的顺滑"！
![avatar](https://cdn.jsdelivr.net/gh/mxfj/cdn/img/WIN10KQYCZM3-1.jpg)
![avatar](https://cdn.jsdelivr.net/gh/mxfj/cdn/img/WIN10KQYCZM3.jpg)
2. 在"控制面板"-""窗口的左侧窗格中，选择“高级系统设置”。

## Step4.关闭自动休眠
1. 在“设置”中选择“系统”>“电源和睡眠”，并检查以确保“睡眠”设置为“从不”。
![avatar](https://cdn.jsdelivr.net/gh/mxfj/cdn/img/WIN10KQYCZM4.jpg)
![avatar](https://cdn.jsdelivr.net/gh/mxfj/cdn/img/WIN10KQYCZM4-1.jpg)

## 结束说明
大部分正常系统的电脑在配置以上操作后就可以打开远程桌面功能，小生完的电脑多了见的古怪的远程故障也多，确实有见过按照以上操作后无法进行远程的PC，大概率都是阉割版的windows系统，服务功能不全导致的。遇到问题多google一下可能可以学到更多！也可以在下方留言和我咨询哦！
