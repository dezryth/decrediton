# 在继续之前...

请理解 [闪电网络](https://docs.decred.org/lightning-network/overview/)
的开发仍在进行中，请谨慎使用。特别注意：

- 请阅读 [数据备份文档](https://docs.decred.org/lightning-network/backups/) 除了钱包种子外，还需要_备份闪电网络数据_才能收回闪电网络中的资金。

- 闪电网络需要节点（钱包）大部分时间都处于在线状态，因此_间歇性开启的_钱包（在很短时间内保持在线状态的钱包）会降低发送和接收付款的能力。

- 请注意，除非双方使用 [瞭望塔](https://docs.decred.org/lightning-network/watchtowers/) 服务，否则恶意交易的一方可能会从_间歇性开启的_钱包中窃取资金。

- 你只能发送和接收已开启通道中的余额，并且需等待6个确认(区块)才能使用。

- 当闪电网络钱包运行时，用于操作的钱包帐户会处于_解锁_状态，因此来自该帐户的资金可能会受到远程计算机或物理访问的风险。 建议使用拥有少量资金的单独帐户（或更好的是单独的_钱包_），以最大程度地降低风险。
