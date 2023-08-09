---
title: 第八题的答案
subtitle:
date: 2022-08-02T9:00:15+08:00
draft: false
author:
  name:  #作者名字
  link:
  email:        #电子邮件
  avatar:
description: 加密内容
password: 8888
message: 请输入十六位数
resources:
  - name: 
    src: 
tags:
  - 数学建模测试阶段-答案
categories:
  - 答案

# See details front matter: https://fixit.lruihao.cn/documentation/content-management/introduction/#front-matter
---

#### 答案如下：
思维法：  
5余4，尾数是4或9  
4余3，那尾数只能是9了  
3余2，尾数是9，那就只能是27+2=29  
然后，要满足3余2的要求，29要保留，所以结果是  
30n+29。(因为3×4×5=60，形成新的一轮循环，所以30n＜60)  
所以，结果是30+29=59  
***
规律解法：  
> 5 余 4   
>> 少1 —— 5 - 4 = 1  

> 4 余 3  
>> 少1 —— 4 - 3 = 1  

> 3 余 2  
>> 少1 —— 3 - 2 = 1    

所以此数只需要加上 1 便可以被 5、4、3 整除  
那就只需要  <center> 5 × 4 × 3 = 60 <center>
            <center> 60 - 1 =59 <center>
***

<!--more-->
