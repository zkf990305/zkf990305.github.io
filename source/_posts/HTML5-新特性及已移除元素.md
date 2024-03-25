---
title: HTML5 新特性及已移除元素
top: false
cover: false
toc: true
mathjax: true
date: 2024-03-25 18:16:04
password:
summary:
tags:
- HTML
- 面试题
categories:
- 前端基础
---



HTML5 作为 HTML 的最新标准，引入了一系列新特性和改进，旨在提供更为丰富和强大的 Web 内容。然而，随着新特性的引入，HTML5 也对一些过时或不再推荐使用的元素进行了移除。

### 新特性

- 语义化标签： HTML5 引入了一系列新的语义化标签，如 `<header>`, `<footer>`, `<nav>`, `<article>`, `<section>` 等，用于更清晰地描述页面内容的结构。这些标签有助于提高页面的可读性和可访问性。
- 多媒体支持： 用于媒介回放的 `<video>` 和 `<audio>` 元素，使得在网页上嵌入音频和视频变得更加简单，无需依赖第三方插件。
- Canvas 绘图： HTML5 引入了 `<canvas>` 元素，使得通过 JavaScript 来绘制图形、动画和图表变得更加方便。
- 本地存储： HTML5 提供了本地存储能力，包括 Web Storage（LocalStorage 和 SessionStorage）和 IndexedDB，使得 Web 应用能够在客户端存储数据，提高了离线应用的体验和性能。
  - `localStorage` 长期存储数据， 浏览器关闭后数据不丢失
  - `sessionStorage` 的数据在浏览器关闭后自动删除
- 表单增强： HTML5 引入了一些新的表单元素和属性，如 `<input type="date">`, `<input type="email">`, `<input type="url">`, `<input type="number">`, `<input type="range">` 等，简化了表单输入和验证。
- 语义化内容： HTML5 引入了一些新的语义化元素，如 `<figure>`、`<figcaption>`、`<time>`、`<mark>` 等，有助于更准确地描述页面内容，提高页面的可访问性和 SEO。
- 响应式设计支持： HTML5 提供了更多的元素和 API，以支持响应式设计和移动设备优化，如 `<meta>` 标签中的 viewport 属性、媒体查询等。这使得开发的网站能够在不同的设备上呈现出最佳的布局和样式。
- 新的技术: `webworker` 、 `websocket` 、 `Geolocation`

### 移除的元素

- 过时的表单元素：如 `<acronym>`, `<applet>`, `<dir>`, `<frame>`, `<frameset>`, `<noframes>`, `<isindex>` 等也被移除了。
- 过时的引用元素：如 `<basefont>`, `<big>`, `<center>`, `<font>`, `<strike>`, `<tt>` 等也被移除了。
- 嵌套的表单： HTML5 不再允许嵌套的表单，即 `<form>` 元素不能再嵌套在另一个 `<form>` 元素内部。

总的来说，HTML5 的新特性和改进为开发者创造了更为便捷和强大的开发环境，同时移除过时的元素也有助于减少不必要的复杂性，提升了 HTML 的整体质量和规范性。