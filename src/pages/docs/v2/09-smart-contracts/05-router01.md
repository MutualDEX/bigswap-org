---
title: Router01
tags: smart-contracts, documentation
---

<Info>
BigswapV2Router01 should not be used any longer, the fact that some methods do not work with tokens that take fees on transfer.
</Info>

# Address

`BigswapV2Router01` is deployed at `0xf164fC0Ec4E93095b804a4795bBe1e041497b92a` on the Ethereum [mainnet](https://etherscan.io/address/0xf164fC0Ec4E93095b804a4795bBe1e041497b92a), 
# Read-Only Functions


## WETH

```solidity
function WETH() external pure returns (address);
```

Returns the [canonical WETH address](https://blog.0xproject.com/canonical-weth-a9aa7d0279dd) on the Ethereum [mainnet](https://etherscan.io/address/0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2),


```
