+++
date = '2024-11-18T16:43:46+08:00'
draft = false
title = 'Article Config'
+++

---
title: xxx
date: 2018-07-11T13:28:59+08:00
tags: [xxx,yyy]
categories: xxx
keywords: xxx,yyy
description: zzz
<!-- 只有指定了 post 类型的文章才会在首页显示 -->
type: "post"
<!-- 是否显示目录，由于目录的性能太低，现在我基本上不会使用这个功能了 -->
toc: false
<!-- 是否加载 mathjax，对于一些不会出现数学公式的文章，不加载这个库可以加快加载速度 -->
mathjax: true
<!-- 指定需要代码高亮的语言，highlight.js 针对每一种语言有一个特定的 js 文件 -->
codes: [json, bash, tex]
<!-- 是否需要加载 Disqus 评论模块，可以控制是否开放评论 -->
comments: true
<!-- 是否采用直排布局 -->
vertical: false
<!-- 文章是否包含图片，如果无图就可以不加载图片浏览模块 -->
image: true
<!-- Hugo 的设置，可以控制是否发布该文章 -->
draft: false
---