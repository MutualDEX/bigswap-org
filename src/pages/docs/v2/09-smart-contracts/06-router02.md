---
title: Router02
tags: smart-contracts, documentation
---

Because routers are stateless and do not hold token balances, they can be replaced safely and trustlessly, if necessary. This may happen if more efficient smart contract patterns are discovered, or if additional functionality is desired. For this reason, routers have _release numbers_, starting at `01`. This is currently recommended release, `02`.

# Address

`BigswapV2Router02` is deployed at `0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D` on the Ethereum [mainnet](https://etherscan.io/address/0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D), 
# Read-Only Functions


## WETH

```solidity
function WETH() external pure returns (address);
```

Returns the [canonical WETH address](https://blog.0xproject.com/canonical-weth-a9aa7d0279dd) on the Ethereum [mainnet](https://etherscan.io/address/0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2),
