---
layout: post
title: 03-ssh
date: 2021-01-08
description: 学习了使用ssh
tags: ssh   
---



##### github中ssh

步骤1：输入 cd .. 进入主目录，输入ssh-keygen

步骤2：文件保存位置，输入该处的目录

<img src="/images/posts/blogImages/image-20210108175937101.png" width=800>

显示下述结果

<img src="/images/posts/blogImages/image-20210108180023245.png" width=800>

步骤3：输入`pwd`查看当前位置，输入`cd .ssh`，进入该目录下，输入`ls`，查看内容，输入`cat id_rsa.pub`，抓取公钥

<img src="/images/posts/blogImages/image-20210108180200201.png" width=800>



步骤4：下载github文件，输入`git clone ssh链接`

<img src="/images/posts/blogImages/image-20210108180644395.png" width=800>

步骤5：ls查看ssh发现有可识别用户known_hosts，设置成功

<img src="/images/posts/blogImages/image-20210108180542954.png" width=800>
