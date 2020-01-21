---
layout: default
title: Clicky.com
permalink: /clicky-test/
---

# Clicky.com社交分享和流量缝隙代码测试页面

Attention: 本页包含来自[Clicky](https://clicky.com)的 **跟踪代码** ，它提供每个访问者的点击信息，C段IP地址，浏览器类型，操作系统。受[uBlock Origin](https://github.com/gorhill/uBlock)阻拦。

Clicky是仅次于Google Analytics的流量分析提供商，专注流量分析。

## 源代码

```html
<script>var clicky_site_ids = clicky_site_ids || []; clicky_site_ids.push(101232323);</script>
<script async src="//static.getclicky.com/js"></script>
<noscript><p><img alt="Clicky" width="1" height="1" src="//in.getclicky.com/101232323ns.gif" /></p></noscript>
```
## 查看方法
鼠标右键-> 查看网页源代码 (view page source)

## 查看后台
虽然Clicky泄露的用户信息较多，但对用户IP进行了模糊处理，仅仅靠C段IP并不能完全精准定位用户身份，只能定位到城市。

本测试页的后台流量分析界面对大家开放，点击[这里](http://clicky.com/?site_id=101232323&sitekey=0672abda48dec488)查看本页的流量统计。

Clicky的后台长这样子。**注意：访问者IP的最后一段统一被模糊化为0，即C段IP.** 完整的用户IP是D段IP。
![截图](https://raw.githubusercontent.com/diymysite/analytics/master/clicky.png)


Note: 这里分享出来的Clicky后台只能看不能改设置。


<script>var clicky_site_ids = clicky_site_ids || []; clicky_site_ids.push(101232323);</script>
<script async src="//static.getclicky.com/js"></script>
<noscript><p><img alt="Clicky" width="1" height="1" src="//in.getclicky.com/101232323ns.gif" /></p></noscript>
