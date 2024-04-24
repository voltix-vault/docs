---
description: The purpose of the Voltix Token
---

# $VLTX

Voltix fulfils four important purposes:

1. To raise capital to accelerate the product during its bootstrap phase
2. To buy users and AUM as quickly as possible using an Airdrop
3. To provide incentives to contributors to build the product
4. To allow anyone to support the adoption trajectory of the product

### The Voltix Token $VLTX

* 100,000,000 starting supply
* 80% in launch liquidity
* 20% allocated to an airdrop
* ERC20 with ERC777 extensions: `approveAndCall()` and `_beforeTransferHook()`
* Ownable, but not mintable (to set launch params)
* Burnable

[https://github.com/voltix-vault/voltix-contracts/blob/feat/token-contracts/contracts/Voltix.sol](https://github.com/voltix-vault/voltix-contracts/blob/feat/token-contracts/contracts/Voltix.sol)

### Value Accrual

Voltix is a buy-burn model. All affiliate and bridge fees accumulated from platform useage will buy and burn the asset.&#x20;



| Fee                      | Amount          |
| ------------------------ | --------------- |
| THORChain Affiliate Fees | 50 basis points |
| THORChain Affiliate Fees | 50 basis points |
| Bridge Fees              | 10 basis points |
