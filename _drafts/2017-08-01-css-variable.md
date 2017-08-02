---
layout: post
title:  "CSS Variable - CSS 变量"
date:  2017-08-01 09:44:47 +0800
categories: CSS
---

CSS 变量是通过扩展 CSS property 来实现的，即 [CSS custom property](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)。

CSS 变量的使用有以下要点：

- 定义
- 使用
- 继承及 fallback

## 定义

``` css
element {
  --main-bg-color: brown;
}
```

## 使用

``` css
element {
  background-color: var(--main-bg-color);
}
```

## 继承及 fallback



## 参考资料

[W3C](https://www.w3.org/TR/css-variables/) / [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_variables)