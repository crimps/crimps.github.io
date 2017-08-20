---
layout:     post
title:      "git status 中文乱码解决"
subtitle:   ""
date:       2017-08-20 12:00:40
author:     "Crimps"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - git
---
git status 在windows系统下显示乱码
![中文乱码图](/img/in-post/2017-08-20-img2.png)
将全局core.quotepath属性置为false即可
```
git config --global core.quotepath false
```
执行后的效果图
![执行后效果图](/img/in-post/2017-08-20-img1.png)