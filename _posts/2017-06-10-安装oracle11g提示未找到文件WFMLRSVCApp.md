---
layout:     post
title:      "2017-06-10-安装oracle11g提示未找到文件WFMLRSVCApp"
subtitle:   ""
date:       2017-06-10 12:00:40
author:     "Crimps"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - Oracle
---
##问题
今天安装oracle 11g 64位版本，报了一个错误

“未找到文件C:app\\...\WFMLRSVCApp.ear”

![错误图片](/img/in-post/安装oracle11G错误.png)

##解决方案
oracle 11g的压缩包有2个，在解压的时候只解压了第一个，第二个没有解压，在安装的时候缺少第二个压缩包的文件。
将第二个压宿包解压到同一目录下即可。