---
layout: post
title:  "install jekyll at ubuntu"
date:   2013-08-30 16:38:46
categories: jekyll update
---
#ubuntu安装jekyll  
- 安装jekyll  
  - `sudo apt-get ruby`  
  - 国内用户最好先更新源`gem source -a http://ruby.taobao.org/`  
  - `gem install jekyll`  
-  到现在几乎就差不多了，如果有问题可能还有解析md等问题，不过总体就石这两步，检查一下依赖环境就ok来。可以用`gem list`来查看安装都东西  
-  多搜索。  
上面都是用以前都方法装的，但是好像也可以用`apt-get install jekyll`不过好像有问题，这次是两个混合都方式，下次用这个方式试一下。  
-  启动切换到本地jekyll 目录`jekyll serve` 浏览器输入`http://localhost:4000/`    
