# state-diffs

Rollups are leveraging Ethereum for data availability. There are two types of ways to handle data availability for rollups:

- Publishing state diffs
- Publishing transaction data

This repository is focused on the first type, state diffs. Currently, the rollups that are using state diffs are:

- [Starknet](https://starknet.io)
- [ZkSync](https://zksync.io/)

## Collaboration ideas

- Create a common standard for state diffs format
- Create a common standard for state diffs compression
- Implement common shared libraries for state diffs handling
- Benchmarking tools

## Formats

- [Starknet state diff format](https://docs.starknet.io/documentation/architecture_and_concepts/Network_Architecture/on-chain-data/#data_availability_v0_11_0_and_forward)
- [ZkSync state diff format](https://docs.zksync.io/zk-stack/concepts/data-availability/overview.html#state-diffs)

## Compression

ZkSync is using compression for state diffs in order to reduce the amount of data that needs to be published on-chain. This results in cost savings for the rollup operator and hence the users.

## License

This repository is licensed under the [MIT License](LICENSE).
