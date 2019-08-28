# Laria
Edge Computing Platform

## Transaction
- normal transaction
  - coin in = tn.${wallet.address}
  - coin out = { to, asset, value }
  - data
  - [tn] = hash(coin in x coin out x data)
  - signature = wallet.sign(tn)

- reward transaction
  - coin in = null
  - coin out = { to, asset, value }
  - data
  - [tn] = hash(coin in x coin out x data)
  - signature = wallet.sign(tn)

## Block
- chain id
- pre block
- transactions
- signature

## LVM
- create coin
- transfer coin
- read
- write
- get balance
- get coin
- get asset list

## Auditor
- verify signature
- verify coin
- verify transaction
- verify block
- verify package

## Feature
- 儲值卡
- 安全錢包（多重簽名）
- 質押鑄幣
- 合約交易
- 延遲生效
