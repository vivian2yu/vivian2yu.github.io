---
layout: post
title: "Jekyll blog 搭建"
description: ""
category: 
tags: []
---

## 首记
使用jekyll搭建blog
本地环境运行 blog
搭建ruby
http://blog.jsfor.com/skill/2013/09/07/jekyll-local-structures-notes/
http://stackoverflow.com/questions/20810653/how-do-i-configure-config-yml-so-that-i-can-install-devkit
搭建RubyGems
http://blog.csdn.net/jason314/article/details/6204781

https://rubygems.org/pages/download
安装jekyll
http://blog.csdn.net/jason314/article/details/6204781

http://www.oschina.net/news/24321/rubygems-taobao-mirror

DevKit  版本对应 ruby  
http://rubyinstaller.org/downloads/



启动jetyll,切到项目路径
$ jekyll serve
新增一篇文章
$ rake post title="Hello World"
新增一个页面
创建一个简单的页面

$ rake page name="about.md"
创建一个嵌套页面

$ rake page name="pages/about.md"
创建一个带路径的页面

$ rake page name="pages/about"
# this will create the file: ./pages/about/index.html
---
