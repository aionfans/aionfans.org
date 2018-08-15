---
title: token
date: 2018-08-15 20:08:29
tags:
---

#Token分析:Aion(AION)

> [翻译自](https://medium.com/@Edward.Ward_53210/token-analysis-aion-aion-469f9186b160)
> 一个多层的区块链系统 旨在解决存在于区块链网络中未解决的多种问题 包括：伸缩性(scalability)，私有性(privacy)以及互操作性(interoperability)

## 团队

`AION Network`由前德勤区块链高管组建的团队`Nuco`创建. Mathew Spoke是Aion的有效发言人，除了是`Nuco`的CEO之外,他也是以太坊企业联盟的董事会成员和安大略证券委员会的FinTech顾问.

`Nuco`始创于2016年, 在构建企业级区块链方案活跃的主要成员. 在开发Aion平台时, 过往的经验教训非常有价值. 在已经为企业用户和广泛的区块链社区建立了重要关系下, `Nuco`将能够利用这些信息用于合作伙伴关系和设计方法，解决以前识别的企业顾客的痛点

由于他们团队坐落在多伦多，使得受益于区块链的生态,包括以太坊的出现和靠近滑铁卢大学

团队的关键数据:

1. 团队大小: 20到30(计划在2018年快速扩张)
2. 位置: 加拿大多伦多(计划在2018构建全球工作室和分布式成员)
3. 50:50的工程人员/其他雇员
4. 运营时间2年

## Token 销售/融资

Aion分别实行了两次Token融资,并且在2017年12月取消了第三方公开售卖. 一次私募销售了30,000,000 AION Token和后续的一次预发售10,000,000 AION Token, 总共集资大约`$23,010,994`(我不知道这个价值是不是从以太到美元的换算，这个信息很重要，因为从USD转换的话会大于2X ？）

团队给出了三个原因解释为何取消了原定于2017年12月下旬的公开售卖

* 前期的融资已经获得了足够的资金进行开发
* 市场状况已转向高度波动和不确定性
* 将100％的注意力集中在建立团队和产品而不是使用重要的人力资源 上更有意义

实际上我认为取消公开售卖的主要原因是AION在公开市场以低于$1的价格进行交易(基于TRS机制会有更多打折), 而事先目标定于最低$1的价格出售, 很大可能迎来失败. 我估计这就是他们团队所说的市场状况的高度波动，而我也认同他们取消发售的原因.


AION承诺通过使用基金会持有的现有Token进行任一进一步的公开销售，从而不会进一步稀释现有的Token持有人

> “Any additional private or public sales will be based out of the founders token supply”
> 任何私募或者公募都将基于基金会提供的Token数来进行

## Token数预估

* 私募30M
* 公开预发售 10M
* Aion基金会 185M -- 锁定三年
* TRS 奖赏 120M -- 用于针对私募和公开预售阶段参加锁仓的投资者 --锁仓一年
* 团队奖励 120M -- 锁仓三年
* 截止2020年一共465M

## The Token Release Schedule (TRS)

AION token的发售和分发的额外的复杂是因为存在 Token释放计划. TRS允许用户使用AION签订一个合同, 并在未来的12个月中间隔的获得大量的AION回报. 下面表格展示了非TRS和TRS不同的AION获取量

![TABLE](https://cdn-images-1.medium.com/max/1250/1*A8F-K1q0iih5wkEGRaQB5w.png)

融资关键参数

1. 一共$23,010,994
2. 循环量: 71M AION
3. 一年循环量: 261 AION
4. 总量: 465M AION
5. 创始团队占: 185M AION(~$ 925M 文章发表时价格), 未来也可以被用于项目融资

## 网络现状

AION Token现在以一种ERC20 token在以太坊上存在, 还没有公开测试网络或者主网启动. 一个beta版本的测试网大约在2月5号启动，当下AION团队已经对私有网络进行了重要测试.

> 因为现在已经启动主网这部分省略

## 网络特性

Aion旨在成为第三代区块链, 主要的目标是解决扩展性, 私密性和互操作性

![network](https://cdn-images-1.medium.com/max/1000/1*gKlRLgVoc2kZUdylKdC-TQ.png)

这个网络以一个核心理念构建，不同的特殊的自定义的区块链对于解决不同问题是必要存在的. 
该网络的构建还相信，连接不同的区块链有能力通过将每个区块链锚定到Aion网络来释放大量价值，连接数量将呈指数级增长，为每个区块链和Aion生态系统增加更多价值.

这个网络会以`Aion-1区块链`来启动, 这是一个Aion连接网络的第一版. Aion-1的主要目标是

* 为区块链(连接到Aion-1网络)提供和外部系统类似数据或者Oracles加密的连接
* 提供基础设施来提供构建高性能的区块链内部应用(例如 一个DApp的元素部署在不同区块链中, 这将允许输入/输出自大于一个区块链而不需要集中任何方面). 简单来说 Aion-1使用这样的逻辑: IF f(x)在 BlockChainA上发生那么在BlockChainB上运行 f(y)
* 创建具有强大且可持续的经济模型的网络，以确保网络的长寿和安全


Aion-1将是一个开放的网络，用户可以自由部署自己的相邻网络。除了作为一个连接网络，Aion-1还将作为一个功能齐全的智能合约区块链运行 - 启动它将使用一个适应EVM的实现，随着时间的推移，他们计划迁移到改进的AVM（Aion虚拟机）。网络将保持与EVM的向后兼容性。

## 桥

桥是连接Aion-1区块链的机制。任何人都可以创建到任何网络/区块链的桥梁，只要它与Aion兼容即可。许多现有的区块链不能完全兼容，但是可以做出妥协，并且区块链可以适应增加兼容性。预计Aion-1将通过与以太坊Blockchain的桥梁来启动

更多细节可以访问看[Aion白皮书](https://aion.network/downloads/aion.network_technical-introduction_en.pdf)

## Token价值来自哪里


AION Token与其实用程序中的ETH或类似令牌相当，此外它还有一些未包含在ETH中的激励。 Aion从以下能力中获得它的价值：

1. 价值由Aion-1 区块链体现
2. 为Aion-1区块链中的操作支付
3. 部署软件
4. 创建&加密区块链之间的桥接
5. 自定义，创建和连接新的参与区块链
6. 股权/验证来保证网络的完整性(POS)

访问[AION TOKEN使用说明书](https://aion.network/downloads/aion.network_token-use_en.pdf)来获取更多使用细节

## 关于共识的说明


Aion-1必须就链式交易和链间交易保持共识。重要的是区分每个因为链间交易的共识失败不会导致链上共识失败。


对于链上交易的共识将通过混合使用BFT（一种委托证明形式）和一种新的神经网络启发的验证算法（称为智能证明）来解决。 AION令牌的持有者将能够以两种方式成为验证者的支持者：（1）传统的赌注方法和（2）支持者运行智能证明算法的新解决机制。智能证明的长期目标是在Aion-1之上启用深度神经网络功能，并最终在区块链之上运行人工智能应用程序。

此外，Aion-1将采用声誉系统，允许潜在的支持者查看有关验证器的各种统计数据，以最大限度地降低选择不良参与者的风险。


链间交易由桥梁管理。桥梁使用来自主要Aion-1链的独特共识机制，并且每个桥通过个体共识是安全的。桥梁将通过轻量级BFT协议进行保护，如果> 2/3的验证者投票批准，则交易被视为有效。桥梁验证器将通过链间交易费和可能的部分块奖励来奖励。

> 这些共识机制的详细信息尚未公布，但请参阅技术白皮书以获取更具体的信息。

## 社区/社交媒体

Aion 拥有一个活跃的社区，目前正在加强社区工作，以期预测测试网和主网的发布。他们已经开始组织公众聚会并在全球招募社区代表。 Matt Spoke发布每周更新，让利益相关者了解项目的最新信息，并且在社区中很受欢迎，最容易找到这些的是youtube。


要更密切地关注项目，请使用以下链接：

[reddit](https://www.reddit.com/r/AionNetwork/)

[twitter](https://twitter.com/aion_network?lang=en)

[medium](https://blog.aion.network/)

[youtube](https://www.youtube.com/channel/UCu4u9tYEgUyNL9KMgrCZvXQ)

[telegram](https://t.me/aion_blockchain)

## 竞争项目


Aion在区块链互操作性领域的竞争非常激烈。竞争对手包括：

* Polkadot
* Cosmos
* Icon
* Wanchain
* Ark
* Cardano

## 合作伙伴

对aion的成功至关重要的是伙伴关系，早期这些将有助于引导网络，并在此过程中突出使用Aion将带来的优势。

aion宣布了以下合作伙伴关系：

* SingularityNET -> [利用Aion扩展SingularityNET平台](https://blog.aion.network/aionandsingularitynet-f0a9adddd305)
* Enigma -> [离线分散计算](https://blog.aion.network/aionenigma-3215097a29)
* SONM -> [为哈希/智能证明提供挖掘和计算能力](https://blog.aion.network/aionandsonm-cacb725aa5e5)
* Metaverse 跨链数字资产和Oracles
* Moog Inc -> [Nuco开发私有区块链以与Aion-1兼容](https://blog.aion.network/moogaionpartnership-6d37ce15b2fd)
* Bancor  -> [通过智能令牌实现链间流动性](https://blog.aion.network/aionbancor-687921632c36)\
* Bitt ->  [希望利用Aion作为其结算网络的一部分](https://blog.aion.network/bittwelcomesaion-ff5b073fe805)
* [Blockchain Interoperability Alliance](https://blog.aion.network/blockchaininteroperabilityalliance-cf595dd6010) -> Aion / Wanchain / Icon是该联盟的创始成员，其目标是确保互操作性平台之间的最佳/通用实践/标准和互操作性。他们鼓励其他互操作性协议加入

## 总览

Aion拥有一支强大的团队，能够理解和应对区块链互操作性的独特挑战，特别是私人/许可链如何与他们的平台互动。

### 优势/优点

* 锁定期将激励早期（TRS）投资者持有AION并成为该项目的长期支持者
* 一个良好规模的合作伙伴关系清单，预先启动，将催化网络活动。
* 私人和财团区块链将通过Aion-1轻松连接公共连锁。通过Aion引导私人链将变得更加简单
* 有真正使用案例的AION有多种激励措施
* 相对较小的当前市值，成功推出主网可能会导致增加
* 关于oracles和将数据传递到区块链的几个问题通过Aion Bridges解决
* 构建具有不同共识机制的多个区块链的优势允许主流DApp实现可伸缩性


### 风险/缺点

* 新的情报证明机制目前是实验性的，可能会失败
* 该平台目前尚未发布，可能存在延迟
* 随着时间的推移（参见时间表），区块链正在推出一些功能
* 许多竞争平台可能会从Aion中夺取市场份额
* 低流通量与总市值的比率掩盖了总市值，使得项目似乎比实际价值更低估


总的来说，我认为Aion是该领域互通性最有希望的途径之一，通过解决互操作性，扩展和隐私也可以部分解决。竞争很激烈，如果他们能够实现已经承诺的东西还有待观察，但是到目前为止团队已经可靠并且他们已经准备好获得市场的重要份额.