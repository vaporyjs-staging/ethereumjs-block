<p align="center">
  <a href="https://github.com/ethereumjs/ethereumjs-vm/tree/master/packages/block">
    <img src="https://user-images.githubusercontent.com/47108/78554503-42c47000-77d9-11ea-8935-2d93981d50df.png" width="309">
  </a>
</p>

# SYNOPSIS

[![NPM Package](https://img.shields.io/npm/v/ethereumjs-block.svg)](https://www.npmjs.org/package/ethereumjs-block)
[![Actions Status](https://github.com/ethereumjs/ethereumjs-block/workflows/block-test/badge.svg)](https://github.com/ethereumjs/ethereumjs-block/actions)
[![Coverage Status](https://img.shields.io/coveralls/ethereumjs/ethereumjs-block.svg)](https://coveralls.io/r/ethereumjs/ethereumjs-block)
[![Gitter](https://img.shields.io/gitter/room/ethereum/ethereumjs-lib.svg)](https://gitter.im/ethereum/ethereumjs)

Implements schema and functions related to Ethereum's block.

# INSTALL

`npm install ethereumjs-block`

# BROWSER

This module works with `browserify`.

# API

[Documentation](./docs/README.md)

# TESTING

Tests in the `tests` directory are partly outdated and testing is primarily done by running the `BlockchainTests` from within the [ethereumjs-vm](https://github.com/ethereumjs/ethereumjs-vm) repository.

To avoid bloating this repository with [ethereum/tests](https://github.com/ethereum/tests) JSON files, we usually copy specific JSON files and wrap them with some metadata (source, date, commit hash). There's a helper to aid in that process and can be found at [wrap-ethereum-test.sh](https://github.com/ethereumjs/ethereumjs-block/blob/master/scripts/wrap-ethereum-test.sh).

# EthereumJS

See our organizational [documentation](https://ethereumjs.readthedocs.io) for an introduction to `EthereumJS` as well as information on current standards and best practices.

If you want to join for work or do improvements on the libraries have a look at our [contribution guidelines](https://ethereumjs.readthedocs.io/en/latest/contributing.html).

# LICENSE

[MPL-2.0](<https://tldrlegal.com/license/mozilla-public-license-2.0-(mpl-2)>)
