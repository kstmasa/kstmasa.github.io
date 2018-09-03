---
title: "【Jekyll】 使用Jekyll-Admin 編輯"
layout: post
date: '2018-09-03 21:00:55'
author: Masa
tags: Jekyll - Admin, 編輯, Jekyll編輯
comments: true
---

# Jekyll - Admin
Hello 歡迎來到Masa的Blog

今天會帶各位在Windows的環境上

安裝Jekyll-Admin的plugin

提升各位用jekyll寫Blog的效率優(應該吧)

-----------------------------------------------------


1.打開 Start Command Prompt with Ruby 
 
 ![](https://i.imgur.com/6SSXHg4.png) 

2.Key上

`gem install jekyll-admin`
3.打開你jekyll blog的Gemfile 加入以下這段

`gem 'jekyll-admin', "~> 0.8"`
	
![](https://i.imgur.com/GRdhuoE.png)

4.打開 _config.yaml, 在plugins底下加上   - jekyll-admin
  
![](https://i.imgur.com/4qGt7jc.png)

5.回到 CMD,  cd到你jekyll blog的folder

6.key上 jekyll serve
就大功告成囉~~~

-----------------------------------------------------

![](https://i.imgur.com/gFhubmd.png)
![](https://i.imgur.com/ZadBCIW.png)
![](https://i.imgur.com/6pQn2lw.png)