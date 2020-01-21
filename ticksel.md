---
layout: default
title: Ticksel.com
permalink: /ticksel-test/
---

# Ticksel.com跟踪代码测试页面

Attention: 本页包含来自[ticksel.com](https://ticksel.com)隐私友好的 **跟踪代码** ，它提供访问者的点击信息，但不会泄露用户敏感信息。

Note: Ticksel流量分析脚本不使用cookies，受[uBlock Origin](https://github.com/gorhill/uBlock)信任。

## 源代码

```html
<!-- Ticksel v1.0 -->
<script type="text/javascript">
  var _tcfg = _tcfg || [];
  (function() {
    _tcfg.push(["tags", "diymysite,analytics"]);
    var u="https://cdn.ticksel.com/js/analytics_v1.0.js"; _tcfg.push(["account_id", 3416238]);
    var d=document, g=d.createElement("script"), s=d.getElementsByTagName("script")[0];
    g.type="text/javascript"; g.async=true; g.src=u; g.setAttribute("crossorigin", "anonymous");
    g.setAttribute("integrity", "sha256-7grd8jMivCG0iCcJ7m/Ny4gvWb0mPVpFhRQovLkaUl8=");
    s.parentNode.insertBefore(g,s);
  })();
</script>
<noscript><img src="https://beacon.ticksel.com/beam?account_id=3416238&referrer=&tags=diymysite,analytics" style="border:0;" width="0" height="0" alt="" /></noscript>
<!-- End Ticksel Code -->
```
## 查看方法
鼠标右键-> 查看网页源代码 (view page source)


<!-- Ticksel v1.0-->
<script type="text/javascript">
  var _tcfg = _tcfg || [];
  (function() {
    _tcfg.push(["tags", "diymysite,analytics"]);
    var u="https://cdn.ticksel.com/js/analytics_v1.0.js"; _tcfg.push(["account_id", 3416238]);
    var d=document, g=d.createElement("script"), s=d.getElementsByTagName("script")[0];
    g.type="text/javascript"; g.async=true; g.src=u; g.setAttribute("crossorigin", "anonymous");
    g.setAttribute("integrity", "sha256-7grd8jMivCG0iCcJ7m/Ny4gvWb0mPVpFhRQovLkaUl8=");
    s.parentNode.insertBefore(g,s);
  })();
</script>
<noscript><img src="https://beacon.ticksel.com/beam?account_id=3416238&referrer=&tags=diymysite,analytics" style="border:0;" width="0" height="0" alt="" /></noscript>

<!-- End Ticksel Code -->
