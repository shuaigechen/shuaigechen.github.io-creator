---
title: "HTML入门笔记1"
date: 2019-08-16T10:51:31+08:00
draft: false
---

# HTML入门笔记1

今天是19年8月16号，这周学习了HTML入门，这是本周学到的知识总结，写博客记录下来

HTML是Tim Berners-Lee（李爵士）发明的

HTML起手先输入！
<code>
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
<meta http-equiv="X-UA-Compatible" content="ie=edge">
</head>
<body>
</body>
</html>
</code>
HTML常用的章节标签有

* 标题  h1-h6

* 章节  section

* 文章  article

* 段落  p

* 头部  header

* 脚部  footer

* 主要内容 main

* 旁支内容 aside

* 划分  div

HTML全局属性有

* class 用来给你的标签加样式

* contenteditable 可以使任意元素被编辑

* hidden 让一个东西看不见

* id 赋予一个元素值（认为id具有唯一性，html不报错id，css里可以直接调用id，不到万不得已不使用）

* style 每一个元素可以写style属性

* tabindex 用tab切换元素的顺序，0最后访问，-1别访问，123按顺序访问

* title    鼠标放上去显示完整内容

HTML常用的内容标签有

* ol+li 有顺序的列表

* ul+li 无顺序的列表

* dl+dt+dd 描述列表

* pre HTML格式默认只保留一个空格，回车，如果需要保留多个空格，用pre包起来

* code code让里面的内容等宽，为了方便填写代码

* hr 分格线

* br 中断现在这行，进行换行

* a  a标签，超链接一个链接，可以直接访问

* em 强调 强调语气

* strong 重要，本身就重要

* quote 引用

* blockquote 换行引用，结果进行换行

