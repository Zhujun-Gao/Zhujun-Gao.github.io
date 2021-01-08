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

![image-20210108175937101](/images/posts/blogImages/image-20210108175937101.png)

显示下述结果

![image-20210108180023245](/images/posts/blogImages/image-20210108180023245.png)

步骤3：输入`pwd`查看当前位置，输入`cd .ssh`，进入该目录下，输入`ls`，查看内容，输入`cat id_rsa.pub`，抓取公钥

![image-20210108180200201](/images/posts/blogImages/image-20210108180200201.png)



步骤4：下载github文件，输入`git clone ssh链接`

![image-20210108180644395](/images/posts/blogImages/image-20210108180644395.png)

步骤5：ls查看ssh发现有可识别用户known_hosts，设置成功

![image-20210108180542954](/images/posts/blogImages/image-20210108180542954.png)
