---
layout: page
title:  "总结笔记"
subtitle: "Summary notes"
date:   2020-09-10 18:14:00 +0530
categories: ["学习"]
---

# 搭建个人技术博客

> 使用 GitHub Pages + Jekyll 快速部署个人博客

> - GitHub Pages 
>    - 定义：GitHub网站给所有用户提供了一个个人主页
>    - 如何访问：个人域名：用户名.github.io
>    - 如何编写主页：建立一个用域名为项目名的远程版本仓库，只需要向该远程版本仓库中的master分支提交代码即可(该代码中必须用一个文件为index.html文件)
> - Jekyll 
>     - 定义：可以将markdow语法自动编译为HTM语法的一个工具
>     - 安装：不需要自己安装，在GitHub网站当中预安装的
>     - 使用：不用人为的使用，当你请求个人域名的时候，GitHub服务器会读取仓库（以个人域名命名的那个远程版本库）中的master分支中的代码，如果该代码为markdow语法会自动调用Jekyll将其编译为HTML代码并返回客户端

- 建立一个以个人域名为项目名的远程版本仓库
- 访问一个网址：主题为：http://jekyllthemes.org/ 选择一个主题，将其代码复制到仓库中的master分支
- 以上两步可以合成一步，在主题仓库中点击fork，点击setting设置仓库名即可
- 将远程版本库中的代码克隆到本地
    - 从远程版本库克隆下来的代码会自动创建本地版本仓库
- 修改配置文件以及页面内容
- 书写博客

# 复制别人主页快捷操作
- 进入网址:https://github.com/knhash/Pudhina => 点击Fork =>   setting =>重命名(用户名：github.io)

