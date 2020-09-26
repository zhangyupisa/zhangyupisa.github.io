---
bg: "tools.jpg"
layout: post
title:  如何利用GitHub搭建自己的个人博客
crawlertitle: 博客搭建教程
summary: Own your own website
categories: posts
tags: ['教程']
date:   2020-09-26
author: lc
---
	使用这篇教程的前提是已经有GitHub账号，并且熟悉GitHub的基本操作。在我自己操作过程中走了不少弯路，所以教程里的部分步骤与我本人的实际操作不尽相同。

## 1 创建仓库

	新建一个新的仓库，重新命名为yourname.github.io，并用GitHub Desktop将新建的仓库克隆到本地。
## 2 下载主题

	从[jekyll主题网站](http://jekyllthemes.org)挑选自己喜欢的主题，下载后解压。比如我用的这个主题[Voyager](http://jekyllthemes.org/themes/voyager/)。

### Voyager

[![Voyager]({{ site.images | relative_url }}/Voyager.jpg)]({{ site.images | relative_url }}/Voyager.jpg)

	将解压后的文件复制到仓库中，并push。（可以忽略其中的.jekyll-cache文件）。用浏览器打开yourname.github.io，就可以看到博客的雏形了。

## 3 更改网站基本格局

	按照自己的要求更改"README.md""index.html""archive.md""about.md""_config.yml"的注释。

## 4 文章撰写

	打开_posts文件夹里，以markdown格式撰写文章，然后用GitHub Desktop随后进行push即可。