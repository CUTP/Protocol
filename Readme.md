# CUTP - Controllable UTXO Token Protocol

CUTP is a controllable layer 1 UTXO Token protocol. The overall concept is shown below.

![图片](./images/image01.png)

Each different color output is a different contract. The input and output of each transaction has a contractId that points to the genesis contract, ultimately forming a transaction chain.

The protocol uses a bitcoin script to do all the work. The security of the Token system is maintained by the bitcoin miner system together with the issuer and other witnesses.

The protocol supports Token, NFT, and Sale and Swap functions.

The protocol supports the contract upgrade.

The protocol supports the use of SPV and P2P transfer.


[Protocol English version](./Protocol_EN.md)

[Protocol Chinese version](./Protocol_CN.md)

If there are any language errors or logic problems, please let us know.

---

CUTP是一个可控的层一UTXO Token协议。

每个不同的颜色输出是不同的合约。每个交易的输入和输出都有一个指向创世合约的contractId，最终形成一条交易链。

协议使用比特币脚本实现全部的功能。由比特币矿工体系和发行者以及其他见证人共同维持Token系统的安全。

协议同时支持Token，NFT以及销售和交换等功能。

协议支持合约升级。

协议支持使用SPV验证，以及P2P的转账。

[中文版协议](./Protocol_CN.md)

[英文版协议](./Protocol_EN.md)

如果有任何语言错误或者逻辑问题，请告知

**Copyright (c) 2020 LI Long, ChainBow Co. Ltd.**

**All rights reserved.**

lilong@chainbow.io
