# 独角数卡USDT支付插件
## 插件介绍
dujiaoka_usdt_payment 依托于Coinpay.vip提供的加密货币支付网关，能快速使你的 独角数卡 发卡系统支持 波场、以太坊、币安智能链、火币生态链、OKX生态链上所有加密火币支付。
## 集成方法
### 全新安装
如果您的dujiaoka系统是全新这装的请按以下方法安装插件
#### 1、将app和routes目录覆盖到网站根目录
#### 2、打开发卡后台 配置设置 >支付网关 > 点击新增，照着下面的内容添加
- 支付名称：Coinpay
- 商户ID：PID
- 商户key：KEY
- 商户密钥：网关，查看下方网关
- 支付标识：支付方式，查看下方支付方式
- 支付场景：通用
- 支付方式：跳转
- 支付处理路由：/pay/Coinpayvip
- 商户ID, 商户KEY 请到Coinpay.vip 官网注册获取.

网关、支付方式，请[点击这里查看](https://callback.vip/news-details.php?id=14)

### 非全新安装(已在运营中的dujiaoka，建议不要直接覆盖)
#### 1、为不影响你之前已集成的其它支付，请先打开网站根目录下/routes/common/pay.php
#### 2、在最下方 }); 前加入如下代码(具体代码请在 插件包中/routes/common/pay.php获取)
#### 3、将app目录覆盖到网站根目录(routes目录不要覆盖)。
#### 4、打开发卡后台 配置设置 >支付网关 > 点击新增，照着下面的内容添加
- 支付名称：Coinpay
- 商户ID：PID
- 商户key：KEY
- 商户密钥：网关，查看下方网关
- 支付标识：支付方式，查看下方支付方式
- 支付场景：通用
- 支付方式：跳转
- 支付处理路由：/pay/Coinpayvip
- 商户ID, 商户KEY 请到Coinpay.vip 官网注册获取.

网关、支付方式，请[点击这里查看](https://callback.vip/news-details.php?id=14)
