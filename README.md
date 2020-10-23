# uniswap-lib

[![Tests](https://github.com/ant-swap/antswap-libs/workflows/Tests/badge.svg)](https://github.com/ant-swap/antswap-libs/actions?query=workflow%3ATests)
[![Static Analysis](https://github.com/ant-swap/antswap-libs/workflows/Static%20Analysis/badge.svg)](https://github.com/ant-swap/antswap-libs/actions?query=workflow%3A%22Static+Analysis%22)
[![Lint](https://github.com/ant-swap/antswap-libs/workflows/Lint/badge.svg)](https://github.com/ant-swap/antswap-libs/actions?query=workflow%3ALint)

Solidity libraries that are shared across Uniswap contracts. These libraries are focused on safety and gas efficiency.

## Install

Run `yarn` to install dependencies.

## Test

Run `yarn test` to execute the test suite.

## Usage

Install this in another project via `yarn add @antswap/libs`

Then import the contracts via:

```solidity
import '@uniswap/lib/contracts/libraries/Babylonian.sol';

```
