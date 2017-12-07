# billing

[![Build Status](https://travis-ci.org/drakeet/billing.svg)](https://travis-ci.org/drakeet/billing)
![maven-central](https://img.shields.io/maven-central/v/me.drakeet.billing/billing.svg)

Google 官方的 billing 库自 1.0 发布以来，一直存在着许多问题，许多人向官方提交 bug 和 issue，却迟迟得不到修复：

https://issuetracker.google.com/u/1/issues?q=componentid:311487%20status:open

于是本项目从 billing 的 aar 中重新拼凑出源码，欲自行对其进行 bug 修复。

### Usage

Just change your ~~`implementation 'com.android.billingclient:billing:1.0'`~~ to: 

```groovy
implementation 'me.drakeet.billing:billing:1.0.1'
```

That's all.

####

本项目遵循 Google billing 原开源协议，如有侵权可以随时与我联系。

附：

![](https://ws1.sinaimg.cn/large/86e2ff85gy1fm8ex01nboj21ym10ctlu.jpg)
