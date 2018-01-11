---
title: Hexo发布到Github丢失readme和CNAME解决方案
date: 2018-01-11 17:48:31
tags:
---
## 方法一（推荐）：将需要上传至github的内容放在source文件夹，例如CNAME、favicon.ico、images等，这样在 hexo d 之后就不会被删除了。
## 方法二：安装插件实现永久保留.
### $ npm install hexo-generator-cname --save //安装此插件实现
### 之后在_config.yml中添加一条
    Plugins:
- hexo-generator-cname

### 需要注意的是：如果是在github上建立的CNAME文件，需要先clone到本地，然后安装插件，在deploy上去即可。CNAME只允许一个域名地址。