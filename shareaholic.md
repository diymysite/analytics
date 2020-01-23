---
layout: default
title: Shareaholic.com
permalink: /shareaholic-test/
---

# Shareaholic.com社交分享和流量分析代码测试页面

Attention: 本页包含来自[Shareaholic](https://shareaholic.com)的 **跟踪代码** ，它提供访问者的点击信息，但不会向网站部署方泄露用户敏感信息。受[uBlock Origin](https://github.com/gorhill/uBlock)阻拦。

shareaholic主要提供侧边栏的社交平台分享按钮，同时分析网页访问量和社交分享量。

## 源代码

```html
<!-- BEGIN SHAREAHOLIC CODE -->
<link rel="preload" href="https://cdn.shareaholic.net/assets/pub/shareaholic.js" as="script" />
<meta name="shareaholic:site_id" content="0282611820784d5193442745b0e9708f" />
<script data-cfasync="false" async src="https://cdn.shareaholic.net/assets/pub/shareaholic.js"></script>
<!-- END SHAREAHOLIC CODE -->
```
## 查看方法
鼠标右键-> 查看网页源代码 (view page source)

如果你装了[uBlock Origin](https://github.com/gorhill/uBlock)浏览器插件，你会发现它不但阻拦了shareaholic的插件，还阻拦了Google Analytics的插件。因为Shareaholic里面也用了GA。

<!-- BEGIN SHAREAHOLIC CODE -->
<link rel="preload" href="https://cdn.shareaholic.net/assets/pub/shareaholic.js" as="script" />
<meta name="shareaholic:site_id" content="0282611820784d5193442745b0e9708f" />
<script data-cfasync="false" async src="https://cdn.shareaholic.net/assets/pub/shareaholic.js"></script>
<!-- END SHAREAHOLIC CODE -->
