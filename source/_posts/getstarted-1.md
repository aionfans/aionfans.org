---
title: aion节点
date: 2018-08-29 20:15:26
tags: aion节点
category:
- doc
---
aion节点搭建
---
基于aion进行构建或者挖矿的第一步就是构建aion节点。然后你才能和aion的主链进行同步和交互

#### 系统要求
- Ubuntu 16.04 或者更高的版本
- 8GB 内存
- cpu要支持SSE4.2

#### 安装步骤

1.  下载节点程序  https://github.com/aionnetwork/aion/releases/download/v0.3.0/aion-v0.3.0.284fa1e-2018-08-21.tar.bz2
2.   解压到指定目录 切换到aion目录，执行
./aion.sh  -a create
提示框中输入密码 XXXX
再次输入密码：XXXXX
两次输入成功且一直后
会显示账号地址，请copy出来并保存好。
3.   账号创建后，会有也关联的keystore文件产生在 aion/keystore 文件夹下
keystore文件名中会包含你之前创建的账号地址。
4.   切换到aion目录，执行./aion.sh
程序会自动同步网络节点数据。




aion桌面钱包
---
这里你能够获取关于你的aion账号的更多信息，其中包括如何设置和使用钱包。


```
请注意，这个钱包是在你的桌面上运行，而不是通过云
的方式。因此，在你使用钱包进行交易之前，必须先完全同步数据才行。
```

安装 Aion钱包的步骤
1. 下载 https://github.com/aionnetwork/aion_ui/releases/download/v1.0.0/aion_wallet-v1.0.0.e446419e-2018-07-05.tar.bz2
2. 解压至本地目录
3. 切换到aion_wallet 目录
4. 运行./aion_wallet.sh文件
运行后此脚本将会自动安装必要的组件和运行钱包的接口
安装成功后将会看到这个界面
![image](https://files.readme.io/90cc2c2-1-accounts.png)

