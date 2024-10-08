> [English](./README.md) | [中文](./README_cn.md)



# AllTick 实时美股行情数据 API
### AllTick-实时美股行情数据API-NYSE-NASDAQ-WebSocket-低延迟-逐笔推送


欢迎使用 AllTick **实时美股行情数据 API**，这是一个为获取来自美国主要交易所（如纽约证券交易所 NYSE 和纳斯达克 NASDAQ）精准且低延迟的股票数据而设计的全方位解决方案。无论您是交易所开发者、交易员，还是金融分析师，这个 API 都能为您提供逐笔推送的实时市场数据，满足您的需求。



## 功能亮点：

- **实时美股数据：** 获取来自 NYSE、NASDAQ 及其他主要美股交易所的秒级股票信息。
- **广泛的股票代码覆盖：** 支持数千只美股股票的数据，包括所有主要股票指数。
- **逐笔推送更新：** API 提供高频率的数据推送，每一个交易变动都会实时推送，确保精准的市场追踪。
- **低延迟数据：** 我们的 WebSocket API 确保了超低延迟，平均延迟仅为 170 毫秒，非常适合实时交易应用。
- **全面的市场数据：** 提供美股价格、报价、交易量、买卖价差等综合市场数据。


## 使用场景

- **实时美股价格 API：** 非常适合需要获取秒级美股价格信息的应用程序。
- **高频交易：** 适合需要即时获取逐笔市场数据的算法交易者。
- **市场分析：** 使用 美股市场数据 API 进行深入的金融分析和市场监控。
- **交易平台：** 无缝集成 美股交易所 API 数据到您的交易系统中。

## 为什么选择 AllTick美股行情API？

AllTick 提供了强大的实时美股行情数据解决方案。通过我们提供的 美股 API，您将获得准确、可靠的数据，以支持高频交易、算法策略和市场研究。以下是 AllTick 的独特优势：

### 可靠的美股数据 API

AllTick 的 美股交易所 API 提供 **99.95%** 的运行时间，确保数据的高可用性和一致性。

### 广泛的市场覆盖

API 支持范围广泛的美股股票，涵盖 NYSE、NASDAQ 等交易所的**所有股票代码**。

### 超低延迟

通过 WebSocket 传输的数据，平均延迟仅**170 毫秒**，非常适合高频交易策略的实施。

### 逐笔推送的美股数据

接收实时的美股报价与价格，**每笔交易**都与交易所数据完全同步，确保准确无误。

  
## 官网
[https://alltick.co](https://alltick.co)

## 接入指南
- [接入指南](./access_guide_cn.md)
## 接口介绍
### 错误码说明
- [错误码说明](./error_code_description_cn.md)
### 产品code列表
- [产品code列表-A股](./product_code_list_A_stock_cn.md)
- [产品code列表-港股](./product_code_list_HK_stock_cn.md)
- [产品code列表-加密货币(数字币)](./product_code_list_cryptocurrency_cn.md)
- [产品code列表-美股](./product_code_list_US_stock_cn.md)
- [产品code列表-商品(贵金属)](./product_code_list_commodities_gold_cn.md)
- [产品code列表-外汇](./product_code_list_forex_cn.md)

### http接口
- [行情API地址说明](./http_interface/api_address_description_cn.md)
- [接口限制](./http_interface/interface_limitation_cn.md)
- [通用标准头](./http_interface/common_standard_header_cn.md)
- [获取最新成交报价查询](./http_interface/latest_transaction_price_query_cn.md)
- [最新盘口报价查询](./http_interface/latest_order_book_price_query_cn.md)
- [K线查询](./http_interface/kline_query_cn.md)
- [批量查询产品最新K线](./http_interface/batch_kline_query_cn.md)

### websocket接口
- [行情API地址说明](./websocket_interface/api_address_description_cn.md)
- [接口限制](./websocket_interface/interface_limitation_cn.md)
- [通用标准头](./websocket_interface/common_standard_header_cn.md)
- [心跳](./websocket_interface/heartbeat_cn.md)
- [实时成交报价订阅](./websocket_interface/realtime_transaction_quote_subscription_cn.md)
- [实时盘口报价订阅](./websocket_interface/realtime_order_book_quote_subscription_cn.md)
- [取消实时报价订阅](./websocket_interface/cancel_realtime_quote_subscription_cn.md)

## 免费token获取
- [token申请](./token_application_cn.md)

## 使用示例,超简单上手
### php:

- [http请求示例](./example/php/php_http_curl.php)
- [websocket请求示例](./example/php/php_websocket_workerman.php)

### python:

- [http请求示例](./example/python/http_python_example.py)
- [websocket请求示例](./example/python/websocket_python_example.py)

### go:
- [http请求示例](./example/go/http_go_example.go)
- [websocket请求示例](./example/go/websocket_go_example.go)

### java:
- [http请求示例](./example/java/HttpJavaExample.java)
- [websocket请求示例](./example/java/WebSocketJavaExample.java)


## 联系我们
Email: support@alltick.co

Skype: [https://join.skype.com/invite/xokTc695huNu](https://join.skype.com/invite/xokTc695huNu)

Telegram: [https://t.me/alltick001](https://t.me/alltick001)

## 作者：AllTick

## 其他作品
官网:[https://alltick.co](https://alltick.co)
