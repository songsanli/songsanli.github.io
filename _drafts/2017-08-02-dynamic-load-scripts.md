---
layout: post
title: "Dynamic Load Scripts"
date: 2017-08-02 10:46:00 +0800
categories: HTML
---

从 Chrome DevTool 来看，当 `<script>` 标签被 append 到 document 之后，浏览器会发一个 GET request 拿指定的脚本，拿到之后会评估脚本（evaluate script）、编译再执行。

## 参考文章

- https://www.html5rocks.com/en/tutorials/speed/script-loading/#toc-first-script

