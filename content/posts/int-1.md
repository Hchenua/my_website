---
title: 第一题
subtitle:
date: 2022-08-02T5:47:15+08:00
draft: false
author:
  name:
  link:
  email:
  avatar:
description:
keywords:
license:
comment: false
weight: 0
tags:
  - 数学建模测试阶段-题目
categories:
  - 题目
hiddenFromHomePage: false
hiddenFromSearch: false
summary:
resources:
  - name: featured-image
    src: featured-image.jpg
  - name: featured-image-preview
    src: featured-image-preview.jpg
toc: true
math: true
lightgallery: false
password:
message:
repost:
  enable: true
  url:

# See details front matter: https://fixit.lruihao.cn/documentation/content-management/introduction/#front-matter
---
##### 问题：
罗马帝国时期，犹太士兵被罗马人包围决定集体自杀。。。  
> 自杀的方式是所有人围成一个圆，例如：六个人
>> 给他们标记 1-6  
1杀2、3杀4、5杀6;  
1杀3、5杀1、5自杀。
***
现在罗马人又包围了 38 个犹太士兵  
假设：这些人之中，有一个叫 赫切努阿 他想要投降保命，但又不敢明说。  
那么赫切努阿应该站在哪个位置，才能成为最后一个剩下的人？这样他就不用自杀。
***
| 士兵总人数 | 存活的位置 |
| ------ | ----------- |
|   1    | 1           |
|   2    | 1           |
|   3    | 3           |
| 4      | 1           |
| 5      | 3           |
| 6      | 5           |
| 7      | 7           |
| 8      | 1           |
| 9      | 3           |
| 10     | 5           |
| 。。。  | ？          |
***

<!--more-->
