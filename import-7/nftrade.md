# nftrade

## 1. Table: NFTrade\_event\_Fill\_history

| Column                 | Type      | Example                                                                                              | Description                                                  |
| ---------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-07-11 06:01:28+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 17175156                                                                                             | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x7c46209488a60ded25530be66083a51ba26009712e940e0f908807e35733ba81                                   | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 12                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xcfb6ee27d82beb1b0f3ad501b968f01cd7cc5961                                                           | Address of the contract that produced the log                |
| makerAddress           | VARCHAR   | 0xb8948576f4f16725ff2639ac271d6fadc434884c                                                           |                                                              |
| feeRecipientAddress    | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| makerAssetData         | VARCHAR   | 0x0257179200000000000000000000000017aa4377207e3b91b60cf1216ec2ff4a6f29643d00000000000000000000000000 |                                                              |
| takerAssetData         | VARCHAR   | 0xf47261b0000000000000000000000000b31f66aa3c1e785363f0875a1b74e27b85fd66c7                           |                                                              |
| makerFeeAssetData      | VARCHAR   | 0x0257179200000000000000000000000017aa4377207e3b91b60cf1216ec2ff4a6f29643d00000000000000000000000000 |                                                              |
| takerFeeAssetData      | VARCHAR   | 0xf47261b0000000000000000000000000b31f66aa3c1e785363f0875a1b74e27b85fd66c7                           |                                                              |
| orderHash              | VARCHAR   | 0xe836e63b72e04522b86918d4f59e8ea386ea2a485c9795893036a11607804fef                                   |                                                              |
| takerAddress           | VARCHAR   | 0x6f8940df422765f278664c836e4e6931800fadab                                                           |                                                              |
| senderAddress          | VARCHAR   | 0x6f8940df422765f278664c836e4e6931800fadab                                                           |                                                              |
| makerAssetFilledAmount | VARCHAR   | 1                                                                                                    |                                                              |
| takerAssetFilledAmount | VARCHAR   | 100000000000000000                                                                                   |                                                              |
| makerFeePaid           | VARCHAR   | 0                                                                                                    |                                                              |
| takerFeePaid           | VARCHAR   | 0                                                                                                    |                                                              |
| protocolFeePaid        | VARCHAR   | 0                                                                                                    |                                                              |
