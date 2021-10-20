# Skeleton Web3 Interface

> A boilerplate web3-enabled interface forked from Uniswap interface. Some leftover Uniswap specific code.

[![nodejs](https://github.com/sambacha/uniswap-skeleton2/workflows/nodejs/badge.svg)](https://github.com/sambacha/uniswap-skeleton2/actions?query=workflow:"nodejs")
[![GitHub tag](https://img.shields.io/github/tag/sambacha/uniswap-skeleton2?include_prereleases=&sort=semver&color=blue)](https://github.com/sambacha/uniswap-skeleton2/releases/)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue)](#license)
[![Styled With Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io/)

## Overview

This is an refactored fork of [ianlapham's skeleton-web3-interface](https://github.com/ianlapham/skeleton-web3-interface)

### Development

```bash
yarn
```

### Run

```bash
yarn start
```

### Configuring the environment (optional)

To have the interface default to a different network when a wallet is not connected:

1. Make a copy of `.env` named `.env.local`
2. Change `REACT_APP_NETWORK_ID` to `"{YOUR_NETWORK_ID}"`
3. Change `REACT_APP_NETWORK_URL` to e.g. `"https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}"`

Note that the interface only works on testnets where both
[Uniswap V2](https://uniswap.org/docs/v2/smart-contracts/factory/) and
[multicall](https://github.com/makerdao/multicall) are deployed.
The interface will not work on other networks.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

## License

Released under [GPL-3.0](/LICENSE)
