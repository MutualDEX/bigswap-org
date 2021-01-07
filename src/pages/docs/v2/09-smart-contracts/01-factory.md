---
title: Factory
tags: smart-contracts, documentation
---

# Address

`BigswapV2Factory` is deployed at `0x5C69bEe701ef814a2B6a3EDD4B1652CB9cc5aA6f` on the Ethereum [mainnet](https://etherscan.io/address/0x5C69bEe701ef814a2B6a3EDD4B1652CB9cc5aA6f),

## feeTo

```solidity
function feeTo() external view returns (address);
```

See <Link to='/docs/v2/advanced-topics/fees/#protocol-charge-calculation'>Protocol Charge Calculation</Link>.

## feeToSetter

```solidity
function feeToSetter() external view returns (address);
```

The address allowed to change [feeTo](#feeto).

# Interface


```solidity
pragma solidity >=0.5.0;

interface IBigswapV2Factory {
  event PairCreated(address indexed token0, address indexed token1, address pair, uint);

  function getPair(address tokenA, address tokenB) external view returns (address pair);
  function allPairs(uint) external view returns (address pair);
  function allPairsLength() external view returns (uint);

  function feeTo() external view returns (address);
  function feeToSetter() external view returns (address);

  function createPair(address tokenA, address tokenB) external returns (address pair);
}
```
