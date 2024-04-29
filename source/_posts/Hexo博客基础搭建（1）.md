---
title: Hexo博客基础搭建（1）
date: 2024-04-21 08:32:29
tags: 博客
categories: Hexo博客
cover: https://images.win-horror.eu.org/file/834f5dbff1c57285e45ac.png
---

# 折腾了几天，这博客算是搞好了，写个这玩意试试

-----------------------------------分割线-----------------------------------

# 让我们开始吧：
(作者注：本教程适用于Windows，Linux要将个别步骤小改！)
## 本章准备材料：
一台电脑（不能用手机！！！）、一个你觉得用得顺手点的浏览器（以及代码编辑器）、一个好用的脑子

# 安装Node.js与Hexo
## Node.js
首先我们要进入Node.js的 官网：https://nodejs.org ，然后点击那个大大的 Download Node.js 按钮，下载下来的安装包直接一路OK即可，剩下的可以自己去配置，就不赘述了。
## Hexo
Hexo倒没多难，直接执行以下命令：
```bash
npm install hexo-cli -g
```
简单而又高效

# 让我们创建一个新博客吧
转到你想放博客位置的父目录，执行以下命令：
```bash
npx hexo init [你想放博客的位置]
```
就能看见你想放博客的位置里面有许多东西，先别动它，执行以下两行命令看看效果（记得转到你放博客的目录）：
```bash
npx hexo cl
npx hexo server
```
这两行代码以后会经常用到（用于调试）
如果一切无误的话，访问localhost:4000就会出现你博客的页面了。

水完了，写作业去了。