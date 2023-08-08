---
title: 第二十题的答案
subtitle:
date: 2023-07-17T6:47:15+08:00
draft: true
author:
  name:  #作者名字
  link:
  email:        #电子邮件
  avatar:
description: 加密内容
password: 2020
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
![](/img/2020.jpg) 

∆t 表示A的计时，同理 ∆t' 表示B的计时  
<font color=#F0F8FF size=3 face="宋体">
$$
(C∆t')^2 = (v∆t)^2 + (v∆t')^2 \\\\
(C∆t')^2 - (v∆t')^2 = (v∆t)^2 \\\\
∆t'^2(C^2-v^2)=C^2∆t^2 \\\\
\frac{∆t'^2(C^2-v^2)}{(C^2-v^2)} = \frac{C^2∆t^2}{(C^2-v^2)} \\\\
∆t'^2 = \frac{C^2}{(C^2-v^2)}∆t^2 \\\\
∆t'^2 = \frac{C^2}{(C^2-v^2)}∆t^2 \\\\
∆t' = \frac{∆t}{\sqrt{1 - \frac{v^2}{C^2}}}
$$
</font> 
***
再通过假设火车速度能达到光速 2% ，即火车速度等于0.02C  
> 代入公式：  
>> $
∆t' = \frac{∆t}{\sqrt{1 - \frac{0.02C^2}{C^2}}} \\\\
∆t' = \frac{∆t}{\sqrt{1 - 0.02^2}} \\\\
\sqrt{0.9996} = 0.99979997999599899971991597359142... \\\\
∆t' ≈ 1.0003∆t
$

用勾股定理演算出来的这个式子，就是科学史上赫赫有名的<font color=#FFFFFF size=4 face="宋体">洛伦兹变换</font> ，不过更确切的说应该叫因斯坦版本的洛伦兹变换，因为洛伦兹本人的原始版本比这个要复杂。
> 那个老师就是爱因斯坦


<!--more-->
