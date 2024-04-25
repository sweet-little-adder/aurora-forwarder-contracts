# Aurora Forwarder Contracts

<3 Design: https://www.figma.com/file/T675bEOAtGNnvwiWmmLtit/aurora-forwarder-contracts?type=design&node-id=0%3A1&mode=design&t=3ORdnqO2VwrcnbGG-1


[![CI](https://github.com/aurora-is-near/aurora-forwarder-contractrs/actions/workflows/rust.yml/badge.svg?branch=main)](https://github.com/aurora-is-near/aurora-forwarder-contractrs/actions/workflows/rust.yml)

The repository contains smart contracts needed for the Aurora Forwarder project.

### Build contracts which could be used in production

```shell
cargo make build
```

### Run unit and integration tests:

```shell
cargo make tests
```

### Run clippy linter:

```shell
cargo make clippy
```

