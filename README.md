# open62541-sys

[![crates.io](https://img.shields.io/crates/v/open62541-sys.svg)](https://crates.io/crates/open62541-sys)
[![Docs](https://docs.rs/open62541-sys/badge.svg)](https://docs.rs/open62541-sys)
[![Dependencies](https://deps.rs/repo/github/HMIProject/open62541-sys/status.svg)](https://deps.rs/repo/github/HMIProject/open62541-sys)
[![Testing](https://github.com/HMIProject/open62541-sys/actions/workflows/test.yaml/badge.svg)](https://github.com/HMIProject/open62541-sys/actions/workflows/test.yaml)
[![License: MPL 2.0](https://img.shields.io/badge/License-MPL_2.0-blue.svg)](https://opensource.org/licenses/MPL-2.0)

This crate provides low-level, unsafe bindings for the C99 library
[open62541](https://www.open62541.org), an open source and free implementation of
[OPC UA](https://opcfoundation.org/about/opc-technologies/opc-ua/).

## Development

Make sure to check out `open62541` with submodules:

```shell
git submodule update --init --recursive
```
