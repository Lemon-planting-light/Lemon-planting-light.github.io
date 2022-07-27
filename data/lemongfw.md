---
title: 柠檬被围墙阻拦的解决方法
---

现状：一句话概括，柠檬被三大流氓运营商DNS劫持了，换个DNS就行

```
公共dns列表：
114dns：114.114.114.114
阿里dns：
    IPv4地址：223.5.5.5和223.6.6.6
    IPv6地址：2400:3200::1 和 2400:3200:baba::1
阿里DoH：https://dns.alidns.com/dns-query

```


## 简单粗暴法
用梯子

## 改DNS法（完全安全免费不要下载软件！

推荐：修改你的dns为114.114.114.114

### for IOS
[iOS 基础教程：如何更改设备网络的 DNS 设置 - 少数派 (sspai.com)](https://sspai.com/post/26455#!)


**第一步：** 打开「设置」应用程序。

**第二步：** 点击「无线局域网」进入 Wi-Fi 列表，并选择连接上可用的 Wi-Fi 网络。

![](https://cdn.sspai.com/attachment/origin/2014/08/10/93235.png?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

![](https://cdn.sspai.com/attachment/origin/2014/08/10/93234.png?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

**第三步：** 连接上可用的 Wi-Fi 网络后，然后点击该 Wi-Fi 网络名称右方的「显示信息」按钮（字母「i」）。

**第四步：** 在该 Wi-Fi 网络的「IP 地址」详情部分，向下滚动，找到「DNS」选项，然后点击右侧的 DNS 数值部分。

![](https://cdn.sspai.com/attachment/origin/2014/08/10/93236.png?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

![](https://cdn.sspai.com/attachment/origin/2014/08/10/93237.png?imageView2/2/w/1120/q/90/interlace/1/ignore-error/1)

**第五步：** 接下来设备底部将滑入键盘，你可以输入你需要更改后的 DNS 数值。我们使用 114 提供的「114.114.114.114」。


### for Android

若手机型号不匹配请自行百度


**wifi网络**：

任意点击一个wifi，进入详情页，选择静态ip。

系统：vivo手机。（其他大同小异

把dns修改成114.114.114.114，即可正常访问。

如果需要手动填写ip地址，可以先在网上查询自己的ip，再填进去。

或者：https://www.alidns.com/knowledge?spm=a2c4g.11186623.0.0.73757312LyVhjY&type=SETTING_DOCS#user_android

**移动数据：**



设置-网络和互联网-高级-私人DNS

私人DNS提供商主机名，填入 [dns.opendns.com ](http://dns.opendns.com)

或其他支持**DoT**的服务商的**域名**

关于国内外的公共DNS，这里有个列表

[https://www.cccitu.com/2205354.html ](https://www.cccitu.com/2205354.html)

关于如何设置私人DNS，可参考这里

[https://www.cccitu.com/2205385.html ](https://www.cccitu.com/2205385.html)


### for Windows and MacOS

参阅https://www.alidns.com/knowledge?spm=a2c4g.11186623.0.0.73757312LyVhjY&type=SETTING_DOCS#user



## 改浏览器dns

edge：
设置里头搜索dns，选择使用安全DNS，然后输入 https://dns.alidns.com/dns-query

firefox:
设置里头搜索dns，然后开启安全DNS，输入 https://dns.alidns.com/dns-query