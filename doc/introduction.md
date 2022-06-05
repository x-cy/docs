# 区块链技术入门学习指引

## 引言
给迷失在如何学习区块链技术的同学一个指引，区块链技术是随比特币诞生，因此要搞明白区块链技术，应该先了解下比特币。
但区块链技术不单应用于比特币，还有非常多的现实应用场景，想做区块链应用开发，可进一步阅读以太坊系列。

## 比特币
如果你是还不知比特币是什么，那就看看[比特币是什么](https://learnblockchain.cn/2017/10/23/whatisbitcoin/)
### 基础入门
接下来可以通过下面这几篇文章了解比特币大概的运行原理：

* [区块链记账原理](https://learnblockchain.cn/2017/10/25/whatbc/)
  通过这篇可以了解到区块链是一个怎样的结构

* [比特币所有权及隐私问题](https://learnblockchain.cn/2017/11/02/bitcoin-own/)
  通过这篇可以了解到地址私钥 非对称加密应用 等概念

* [比特币如何挖矿](https://learnblockchain.cn/2017/11/04/bitcoin-pow/)
  通过这篇了解工作量证明

* [比特币如何达成共识 - 最长链的选择](https://learnblockchain.cn/2017/12/07/bitcoin-sonsensus/)
  通过这篇可以了解共识机制。

### 补充阅读
* [什么是拜占庭将军问题](https://learnblockchain.cn/2018/02/05/bitcoin-byzantine/)

### 进阶
在基础入门之后，可以进一步阅读以下几篇，理解分布式网络，交易验证。

* [分析比特币网络：一种去中心化、点对点的网络架构](https://learnblockchain.cn/2017/11/07/bitcoin-p2p/)
* [比特币区块结构 Merkle 树及简单支付验证分析](https://learnblockchain.cn/2017/11/10/bitcoin-script/)
* [比特币脚本及交易分析 - 智能合约雏形](https://xiaozhuanlan.com/topic/1402935768)

看完上面这些，区块链应该理解差不多了，就可以尝试实现一个简单的区块链了。参考这篇[用Python从零开始创建区块链](https://learnblockchain.cn/2017/10/27/build_blockchain_by_python/)。

## 以太坊
一个技术要落地还得靠应用， 以太坊就这样一个建立在区块链技术之上，去中心化的应用平台。可以阅读几下几篇，这部分以开发为主，需要大家多发时间实践。

* [以太坊开发入门](https://learnblockchain.cn/2017/11/20/whatiseth/)
* [智能合约开发环境搭建及Hello World合约](https://learnblockchain.cn/2017/11/24/init-env/)
* [搭建智能合约开发环境Remix IDE及使用](https://learnblockchain.cn/2018/06/07/remix-ide/)
* [以太坊客户端Geth命令用法-参数详解](https://learnblockchain.cn/2017/11/29/geth_cmd_options/)
* [Geth控制台使用实战及Web3.js使用](https://learnblockchain.cn/2017/12/01/geth_cmd_short/)
* [如何搭建以太坊私有链](https://learnblockchain.cn/2018/03/18/create_private_blockchain/)
* [深入浅出以太坊虚拟机](https://learnblockchain.cn/2019/04/09/easy-evm/)

### 智能合约及应用开发

* [完全理解以太坊智能合约](https://learnblockchain.cn/2018/01/04/understanding-smart-contracts/)
* [程序员如何切入区块链去中心化应用开发](https://learnblockchain.cn/2018/08/31/devDapp/#more)
* [一步步教你开发、部署第一个Dapp应用](https://learnblockchain.cn/2018/01/12/first-dapp/)
* [一步步教你创建自己的数字货币（代币）进行ICO](https://learnblockchain.cn/2018/01/12/create_token/)
* [实现一个可管理、增发、兑换、冻结等高级功能的代币](https://learnblockchain.cn/2018/01/27/create-token2/)
* [如何通过以太坊智能合约来进行众筹（ICO）](https://learnblockchain.cn/2018/02/28/ico-crowdsale/)
* [剖析非同质化代币ERC721--全面解析ERC721标准](https://learnblockchain.cn/2018/03/23/token-erc721/)
* [Web3与智能合约交互实战](https://learnblockchain.cn/2018/04/15/web3-html/)
* [Web3监听合约事件](https://learnblockchain.cn/2018/05/09/solidity-event/)
* [如何编写一个可升级的智能合约](https://learnblockchain.cn/2018/03/15/contract-upgrade/)
* [美链BEC合约漏洞技术分析](https://learnblockchain.cn/2018/04/25/bec-overflow/)

### Solidity语言教程
全面学习Solidity语言可以购买图书：[精通以太坊智能合约](http://edu.upchain.pro/book.html)

* [Solidity 教程系列1 - 类型介绍](https://learnblockchain.cn/2017/12/05/solidity1/)
* [Solidity 教程系列2 - 地址类型介绍](https://learnblockchain.cn/2017/12/12/solidity2/)
* [Solidity 教程系列3 - 函数类型介绍](https://learnblockchain.cn/2017/12/12/solidity_func/)
* [Solidity 教程系列4 - 数据存储位置分析](https://learnblockchain.cn/2017/12/21/solidity_reftype_datalocation/)
* [Solidity 教程系列5 - 数组介绍](https://learnblockchain.cn/2017/12/21/solidity-arrays/)
* [Solidity 教程系列6 - 结构体与映射](https://learnblockchain.cn/2017/12/27/solidity-structs/)
* [Solidity 教程系列7 - 以太单位及时间单位](https://learnblockchain.cn/2018/02/02/solidity-unit/)
* [Solidity 教程系列8 - Solidity API](https://learnblockchain.cn/2018/03/14/solidity-api/)
* [Solidity 教程系列9 - 错误处理](https://learnblockchain.cn/2018/04/07/solidity-errorhandler/)
* [Solidity 教程系列10 - 完全理解函数修改器](https://learnblockchain.cn/2018/04/09/solidity-modify/)
* [Solidity 教程系列11 - 视图函数、虚函数讲解](https://learnblockchain.cn/2018/05/17/solidity-functions/)
* [Solidity 教程系列12 - 库的使用](https://learnblockchain.cn/2018/08/09/solidity-library/)
* [Solidity 教程系列13 - 函数调用](https://learnblockchain.cn/2018/08/09/solidity-callfun/)
* [智能合约最佳实践 之 Solidity 编码规范](https://learnblockchain.cn/2018/05/04/solidity-style-guide/)
* [如何理解以太坊ABI - 应用程序二进制接口](https://learnblockchain.cn/2018/08/09/understand-abi/)


## 区块链扩容

* [深入理解Plasma（一）Plasma 框架](https://learnblockchain.cn/2018/10/20/plasma-framework/)
* [深入理解Plasma（二）Plasma 细节](https://learnblockchain.cn/2018/10/24/plasma-in-detail/)
* [深入理解Plasma（三）Plasma MVP](https://learnblockchain.cn/2018/11/03/plasma-mvp/)
* [深入理解Plasma（四）Plasma Cash](https://learnblockchain.cn/2018/11/16/plasma-cash/)


### 钱包开发系列

* [理解开发HD 钱包涉及的 BIP32、BIP44、BIP39](https://learnblockchain.cn/2018/09/28/hdwallet/)
* [以太坊钱包开发系列1 - 创建钱包账号](https://learnblockchain.cn/2018/10/25/eth-web-wallet_1/)
* [以太坊钱包开发系列2 - 账号Keystore文件导入导出](https://learnblockchain.cn/2018/10/25/eth-web-wallet_2/)
* [以太坊钱包开发系列3 - 展示钱包信息及发起签名交易](https://learnblockchain.cn/2018/10/26/eth-web-wallet_3/)
* [以太坊钱包开发系列4 - 发送Token(代币）](https://learnblockchain.cn/2018/10/26/eth-web-wallet_4/)

### 如可开发一款以太安卓钱包

* [登链钱包（一款功能强大的以太坊钱包）完全开源](https://learnblockchain.cn/2019/03/07/wallet-annouce/)
* [如何开发一款以太坊（安卓）钱包系列1 - 通过助记词创建账号](https://learnblockchain.cn/2019/03/13/eth_wallet_dev_1/)
* [如何开发一款以太坊（安卓）钱包系列2 - 导入账号及账号管理](https://learnblockchain.cn/2019/03/18/eth-wallet-dev-2/)
* [如何开发一款以太坊安卓钱包系列3 - 资产信息展示](https://learnblockchain.cn/2019/03/24/eth_wallet_dev_3/)
* [如何开发一款以太坊安卓钱包系列4 - 获取以太及Token余额](https://learnblockchain.cn/2019/03/26/eth-wallet-dev-4/)
* [如何开发一款以太坊安卓钱包系列5 - 发送转账交易](https://learnblockchain.cn/2019/04/04/eth-wallet-dev-5/)

## 柚子EOS

* [什么是EOS](https://learnblockchain.cn/2018/07/17/whatiseos/)

## 跨链研究

* [跨链技术的分析和思考](https://learnblockchain.cn/2019/03/23/blockchain_interoperability/)


## IPFS

* [站在Web3.0 理解IPFS是什么](https://learnblockchain.cn/2018/12/12/what-is-ipfs/)
* [IPFS 使用入门](https://learnblockchain.cn/2018/12/25/use-ipfs/)

## Substrate
[Substrate 入门（1）- 环境配置与编译 ](https://learnblockchain.cn/article/273)
[Substrate 入门（2）- 运行与调试](https://learnblockchain.cn/2019/12/21/substrate-run-debug)
[Substrate 入门（3）- 具备状态的链](https://learnblockchain.cn/2019/12/22/substrate-state)
[Substrate 入门（4）- 项目结构](https://learnblockchain.cn/2019/12/23/substrate-struct)
[Substrate 入门（5）- 区块头](https://learnblockchain.cn/2019/12/30/substrate-header)
[Substrate 入门（6）- 交易体](https://learnblockchain.cn/article/330)
[Substrate 入门（7）- Substrate的模型设计](https://learnblockchain.cn/article/331)
[Substrate 入门（8）- Runtime概要](https://learnblockchain.cn/article/348)
[Substrate 入门（9）- Runtime的wasm与native](https://learnblockchain.cn/article/382)
[认识 Substrate 及开发准备](https://learnblockchain.cn/2018/10/20/substrate-base)
[Substrate 总览(1) - 设计](https://learnblockchain.cn/2019/03/02/substrate-project)
[Substrate 总览(2) - 项目结构](https://learnblockchain.cn/2019/03/10/substrate-structure)
[Substrate 总览(3) - 入门参考](https://learnblockchain.cn/2019/11/05/substrate-start)

## FileCoin

* [1 filecoin概念](https://learnblockchain.cn/2019/02/18/filecoin-code-analysis-1/)
* [2 filecoin通用语言理解](https://learnblockchain.cn/2019/02/20/filecoin-code-analysis-2/)
* [3 filecoin开发网使用](https://learnblockchain.cn/2019/02/22/filecoin-code-analysis-3/)
* [4 filecoin源码顶层架构分析](https://learnblockchain.cn/2019/02/28/filecoin-code-analysis-4/)
* [5 filecoin源码协议层分析之心跳协议](https://learnblockchain.cn/2019/03/04/filecoin-code-analysis-5/)
* [6 filecoin源码协议层分析之hello握手协议](https://learnblockchain.cn/2019/03/04/filecoin-code-analysis-6/)
* [7 filecoin源码协议层分析之存储协议](https://learnblockchain.cn/2019/03/05/filecoin-code-analysis-7/)
* [8 filecoin源码协议层分析之检索协议](https://learnblockchain.cn/2019/03/05/filecoin-code-analysis-8/)
* [9 filecoin源码分析之支撑包分析(1)](https://learnblockchain.cn/2019/03/06/filecoin-code-analysis-9/)
* [10 filecoin源码分析之支撑包分析(2)](https://learnblockchain.cn/2019/03/07/filecoin-code-analysis-10/)
* [11 filecoin源码分析之内部接口层api包分析](https://learnblockchain.cn/2019/03/07/filecoin-code-analysis-11/)
* [12 filecoin源码分析之内部接口层plumbing＆porcelain接口](https://learnblockchain.cn/2019/03/07/filecoin-code-analysis-12/)
* [13 filecoin源码分析之服务层actor及vm](https://learnblockchain.cn/2019/03/08/filecoin-code-analysis-13/)
* [14 filecoin源码分析之服务层链同步、共识协议及挖矿](https://learnblockchain.cn/2019/03/09/filecoin-code-analysis-14/)
* [15 filecoin源码分析之节点运行逻辑](https://learnblockchain.cn/2019/03/10/filecoin-code-analysis-15/)

## go实现区块链(Bitcoin)
[golang 实现区块链(Bitcoin)系列 1 - 基本原型](https://learnblockchain.cn/article/577)  
[golang 实现区块链(Bitcoin)系列 2 - 工作量证明](https://learnblockchain.cn/article/580)  
[golang 实现区块链(Bitcoin)系列 3 - 持久化和命令行接口](https://learnblockchain.cn/article/586)  
[golang 实现区块链(Bitcoin)系列 4 - 交易(1)](https://learnblockchain.cn/article/619)  
[golang 实现区块链(Bitcoin)系列 5 - 地址](https://learnblockchain.cn/article/637)  
[golang 实现区块链(Bitcoin)系列 6 - 交易(2)](https://learnblockchain.cn/article/674)
[golang实现区块链(Bitcoin)系列7 - 网络](https://learnblockchain.cn/article/677)

## 其他

* [理解去中心化 稳定币 DAI](https://learnblockchain.cn/2019/03/19/understand_dai/)
