---
title: AION开发路线图
date: 2018-07-30 20:15:26
tags: roadmap
category:
- doc
---
### Roadmap to the internet, decentralized.
2018
### 阶段一： Kilimanjaro - 乞力马扎罗山，位于坦桑尼亚东北部，是非洲最高的山
#### Virtual Machine - FastVM with EVM Source Compatibility
#### 虚拟机 - 兼容以太虚拟机（EVM）源码的FastVM
Aion FastVM is an enhanced Ethereum Virtual Machine (EVM), featuring 128-bit data word size for better performance. It uses LLVM JIT as execution engine and runs decentralized application at native speed. Due to the architecture change, the instruction set and the energy cost of each instruction has been optimized. In addition, solidity compiler has been updated so that it can generate code for the Aion FastVM.
Aion FastVM是以太虚拟机（EVM）的增强版，128位数据字节长度赋予更好的性能。使用LLVM JIT作为执行引擎，去中心化应用运行速度无损耗。架构变化带来指令集和单指令能耗的优化。另外，solidity编译器更新后，可以为Aion FastVM生成代码。

#### Aion Interchain - Token Bridge and Interchain Communication
#### Aion跨链 - Token网桥和跨链通信
This bridge is designed to enable the decentralized movement of smart contract based tokens between blockchains. Creating multi-network tokens that maintain a consistent supply - unleashing tokens from solely existing within one blockchain. The Token Bridge for the Kilimanjaro release is built for the purpose of migrating our ERC-20 token supply to native AION coins using a trustless interchain mechanism.
Token网桥的设计是为了基于tokens的智能合约在区块链之间流转。创建多网络tokens保持一致供给 - 释放单独存在于单个区块链的tokens。Kilimanjaro发行版的Token网桥的构建是为了使用不可信的跨链机制将我们的ERC-20 token供给转移给AION币。

#### Aion Proof of Work - Equihash 210_9
#### AION 工作量证明（POW）- Equihash210_9共识算法
The Kilimanjaro Release utilizes an optimized equihash consensus algorithm we’ve named Equihash210_9. This is a modification to the equihash algorithm, which doubles the memory requirement while achieving the required block times.
Kilimanjaro发行版使用优化过的equihash共识算法，我们将其命名为Equihash210_9。修改后的equihash共识算法，在指定区块时间内完成需要两倍内存。

#### Aion Core - Multi-Chain Framework, Wire Protocol (P2P), Tx Pool, Event Manager
#### Aion Core - 多链框架，通信协议（P2P），交易内存池（Tx Pool），事件管理器
Aion Core is a collection of foundational modules necessary to run the Aion blockchain. The multi-chain framework contains the foundational structure for the modules that constitute the Aion blockchain. The Aion Wire module is a peer-to-peer (P2P) communications protocol. This protocol sets the standard for how Aion nodes interface between themselves by defining communication message structures. Event Manager (RPL) is the serialization solution, encoding arrays of binary data in a structure for Aion core.
Aion Core是指运行Aion区块链必不可少的基础模块集合。多链框架是组成Aion区块链各模块的基础结构。Aion通信模块是一种点对点（P2P）的通信协议。通过定义通信消息结构，该协议为Aion节点接口之间的通信设定了标准。事件管理器（RPL）是序列化解决方案，用于为Aion core将二进制数据数组编码成一种结构。

#### Aion APIs - Java API, Web3 API Compatibility
#### Aion APIs - Java 接口，Web3接口兼容
The Aion Web3 repo provides the tools for using the Aion compatible Web3 API. It contains the setup instructions, tutorial content, example use-cases and test multi-sig wallet. The API repo contains a Java implementation of the Aion blockchain kernel application programming interface, built using Java 8. It uses the ZMQ Java binding as the network transfer layer protocol for improved stability, reliability and security. This repo will also contain future API implementations.
Aion Web3库提供使用Aion可兼容Web3API的工具包。该工具包包含安装命令，教程，用例和测试多重签名钱包。API库包含Aion区块链内核应用编程接口的java实现，由Java8编译。它使用ZMQ Java binding作为网络传输层协议来提高稳定性，可靠性和安全性。未来，API实现也会放在这个库中。

### 阶段二: Denali - 德纳里山（原名麦金莱山）位于美国阿拉斯加州的中南部，阿拉斯加山脉中段，海拔6193 米，为北美洲的第一高峰
#### Aion Virtual Machine (AVM) Version 1
#### Aion虚拟机V1(AVM)
This AVM is a custom-built, lightweight, performant, and stable VM that leverages key characteristics of the Java Virtual Machine (JVM), providing concurrency and robustness within a blockchain-specific context. The AVM is responsible for running applications on top of Aion. The AVM will include its own scripting language.
该AVM是一个定制，轻量级，高性能和稳定的虚拟机，利用Java虚拟机（JVM）的关键特性，提供在区块链环境下的并发和鲁棒性。AVM负责在Aion上面运行应用。未来将会包含它自己的脚本语言。

#### Aion Scripting Language
#### Aion脚本语言
The Aion scripting language is used for writing chain logic that runs on Aion-Everest and potentially any connecting/participating network. The Aion language is compiled into AVM bytecode and executed by the AVM. The Aion language provides the following features: Defensive programming, Blockchain runtime environment, Blockchain context injection, Security.
Aion脚本语言用于在Aion-Everest和任何参与或者连接的其他网络上编写链逻辑。该脚本语言编译成AVM二进制代码并在AVM执行。同时，它提供如下特性：防御性程序设计，区块链运行时环境，区块链上下文注入，安全。

#### Proof-of-Intelligence Consensus Algorithm
#### 智力证明共识算法
An economic measure to deter denial of service attacks by requiring participants, solvers in Aion-Everest, to perform artificial intelligence (AI) computation. The intent is to motivate the creation of AI-specific or specialized hardware that could be used for machine learning and neural network training in the future.
通过要求参与者，处理者执行人工智能计算来推迟拒绝服务攻击的一种有经济效益的措施。目的是激励去创造未来可以被用于机器学习和神经网络训练的AI硬件。

2019
### 阶段三: Everest - 珠穆朗玛峰（珠峰）是喜马拉雅山脉的主峰，位于中国与尼泊尔边境线上，是世界海拔最高的山峰
#### Participating Network Bridging
#### 参与网络桥接
The generic bridge protocol is designed to enable the atomic movement of value and data between heterogeneous networks. This will enable the development of cross-blockchain contract logic and free-floating token supplies.
通用网桥协议的设计是为了数据的原子操作可以在多种多样的网络中执行，使得跨链合约逻辑的开发和不受约束的token供应成为可能。

#### Complete Validator Nomination
#### 完成验证者提名
The Hybrid DPoS / PoI consensus mechanism aims to achieve high performance while providing a fair and decentralized validator set. This is achieved through a token staking system and partly through a novel verification algorithm based on concepts used in modern neural networks called Proof-of- Intelligence.
混合DPoS/Pol共识机制是为了当提供公平和去中心化的验证者集合时还能拥有高性能。通过一个token存储系统和部分结合一个基于存在于现代神经网络中的概念-智力证明的创新验证算法。

#### Aion Virtual Machine (AVM) Version 2
#### Aion虚拟机V2(AVM)
This Virtual Machine will be an evolution of the AVM with a focus on higher performance with concurrent execution, and multiple language support.
这个虚拟机将会是AVM-V1的进化版，重点在于更高性能的并发执行速度，多语言支持。
