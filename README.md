[TOC]

## 1inch学习过程记录
> - 经过两周左右的1inch学习，对其架构有一定的了解，留此记录，希望能帮助对1inch感兴趣的伙伴 （拙见）；
> - 最推荐1inch中文blog，尤其是解析器链下部分&链上部分；结合GPT更佳；
> - 仓库中其他md笔记不完整，应跳过。

## 1 1inch介绍
- DEX聚合器
  - 聚集了更多的流动性，路由更智能，价格更友好
- cross-chain
  - 通过fusion mode可以实现，借鉴atomic swap思想
- 省gas
  - fusion mode,交易者只需要签署订单，不需要付gas
  - resolver解析这来承担gas
  - 经过重重优化，执行本身的gas也比竞品有明显优势
- 防范MEV
  - fusion mode本身就防范了mev,批量提交
  - metamask 还有rabbit hole功能，可以防范MEV

## 2 需要理解的核心概念
- fusion-mode
  - 如何实现跨链
  - 荷兰拍卖
  - 部分成交
  - resolver
- resolver解析器
  - 链下交互
  - 链下交互
  - 盈利模式
- router，pathFinder
- 官方提供了哪些api
> 我目前也没能完全理解，只是对主要流程有所理解

## 3 学习过程&学习资料推荐

1 官网
https://portal.1inch.dev/documentation/overview
- 阅读建议：
- overview,
- swap-apis/overview
- swap-apis/fusion+/introduction
- fusion+ whitepaper   这个英文文档，时间充裕应该通读
- 其他部分看不太懂，可以先跳过



2 中文blog
https://blog-cn.1inch.io/
> 中文blog是我找到讲解最明白权威的资料了，非常推荐。（实现细节应该是不公开，也没找到更详细的资料）

- **推荐阅读-FUSION**：------------------------------------
- 1inch 推出重大更新功能：Fusion
  - https://blog-cn.1inch.io/1inch-tui-chu-zhong-da-geng-xin-gong-neng-fusion/
- Fusion 模式下的掉期解析器
  - https://blog-cn.1inch.io/fusion-mode-swap-resolving/
- Fusion掉期解析器：链下组件
  - https://blog-cn.1inch.io/fusion-mode-explain/
- Fusion 掉期解析器：链上组件
  - https://blog-cn.1inch.io/fusion-swap-resolving-onchain-component/
- 推荐阅读-API：--------------------------------------------
- 1inch 推出测试版开发者门户
  - https://blog-cn.1inch.io/1inch-released-dev-portal/
- 1inch 开发者门户开放全新 API
  - https://blog-cn.1inch.io/new-apis-added-to-the-1inch-developer-portal/
- 其他--------------------------------------------------------
- 关于 1inch 你可能不知道的五件事
  - https://blog-cn.1inch.io/five-things-you-might-not-know-about-the-1inch-network/
- 最常见的MEV类型和防毒策略
  - https://blog-cn.1inch.io/the-most-common-types-of-mev-and-protection-from-toxic-strategies/
- 1inch 路由 v5 版本现已推出
  - https://blog-cn.1inch.io/1inch-lu-you-v5-ban-ben-xian-yi-tui-chu/

3 帮助中心
- https://help.1inch.io/en/collections/2617056-guides


