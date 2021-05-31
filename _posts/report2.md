---
layout: post
author: Dcy
---

# WEB应用软件开发实训--第二次作业--开发一个静态网站实验报告

网站公网网址: Dcyuan8195.github.io
网站源代码github仓库网址: https://github.com/Dcyuan8195/Dcyuan8195.github.io.git

## 网站目录结构  

![网站目录结构](https://github.com/Dcyuan8195/Dcyuan8195.github.io/blob/master/%E7%BD%91%E7%AB%99%E7%9B%AE%E5%BD%95%E7%BB%93%E6%9E%84.png)    

## 二.网站截图


## 三.实验过程



## 四.实验小结

遇到问题；
1：bundle 时出现  
Don't run Bundler as root. Bundler can ask for sudo if it is needed,   and installing your bundle  
as root will break this application for all non-root users on this machine.  
解决：RUN bundle config --global silence_root_warning 1  

2：root@MSI:~# service nginx status  
 * nginx is not running  
解决：sudo service nginx start  