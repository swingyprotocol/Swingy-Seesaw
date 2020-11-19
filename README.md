# Swingy Seesaw

[![Build Status](https://travis-ci.com/ampleforth/token-geyser.svg?token=o34Gqy9mFp6fX3Y6jzyy&branch=master)](https://travis-ci.com/ampleforth/token-geyser)&nbsp;&nbsp;[![Coverage Status](https://coveralls.io/repos/github/ampleforth/token-geyser/badge.svg?branch=master&t=LdZfUk)](https://coveralls.io/github/ampleforth/token-geyser?branch=master)
Used in conjunction with the Swingy token to reward SWING liquidity provders based off of current Uniswap prices.

A smart-contract based mechanism to distribute tokens over time, inspired loosely by Compound and Uniswap.

Implementation of [Continuous Vesting Token Distribution](https://github.com/ampleforth/RFCs/blob/master/RFCs/rfc-1.md)

The official Geyser contract addresses are (by target):
- UniswapV2 [ETH/SWING] Pool: tbd

## Table of Contents

- [Install](#install)
- [Testing](#testing)
- [Contribute](#contribute)
- [License](#license)


## Install

```bash
# Install project dependencies
npm install

# Install ethereum local blockchain(s) and associated dependencies
npx setup-local-chains
```

## Testing

``` bash
# You can use the following command to start a local blockchain instance
npx start-chain [ganacheUnitTest|gethUnitTest]

# Run all unit tests
npm test

# Run unit tests in isolation
npx mocha test/staking.js --exit
```

## Contribute

To report bugs within this package, please create an issue in this repository.
When submitting code ensure that it is free of lint errors and has 100% test coverage.

``` bash
# Lint code
npm run lint

# View code coverage
npm run coverage
```

## License

[GNU General Public License v3.0 (c) 2020 Fragments, Inc.](./LICENSE)
