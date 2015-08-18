---
layout: docs
title: 业务问题
order: 20
---

### 1. 七牛的费用是怎么计算的？

```
 七牛对存储、下载流量、请求次数分别计费。最终支付款项为三项之和。
 存储量取月度日均值，进行费用的结算。如存储量每日的绝对值为D1、D2、D3...D31 ，则最终月度结算费用时为(D1+D2+...+D31)/31。
 下载流量和请求次数以新增的数量进行累积计算。
```