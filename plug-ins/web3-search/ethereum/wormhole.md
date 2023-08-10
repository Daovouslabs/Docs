# wormhole

## 1. Table: Migrator\_call\_add\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-09 01:46:34+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14548629                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x4821dd87c6ec24a4eb7c8af399d78b03be6c4fd64f4c36c8152d48231d7f1f40 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 216                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 18999000000000                                                     |                                                                                                                        |

## 2. Table: Migrator\_call\_approve\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-18 18:50:33+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14800454                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x562ec453d82bc7429d637e4c77902e7681bbd7810ac6971ba4eb9dad64bc3d5b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 104                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| spender            | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         |                                                                                                                        |
| amount             | VARCHAR   | 111111111111111111111111111111111111111111111                      |                                                                                                                        |

## 3. Table: Migrator\_call\_claim\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-14 10:09:56+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14773002                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5a9bd0467878541c308cfcd6c98520b5aaa29fd416deb56b946a6af9a97651dd | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 20                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 75864000000                                                        |                                                                                                                        |

## 4. Table: Migrator\_call\_decreaseAllowance\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| spender            | VARCHAR   |                                                                                                                        |             |
| subtractedValue    | VARCHAR   |                                                                                                                        |             |

## 5. Table: Migrator\_call\_increaseAllowance\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| spender            | VARCHAR   |                                                                                                                        |             |
| addedValue         | VARCHAR   |                                                                                                                        |             |

## 6. Table: Migrator\_call\_migrate\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-20 10:45:18+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14422785                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x507da8671051f5d06d1e41e9dc46499d25fb402a5dcff945ad1f90f472cec998 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 77                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 140012302030538120340174                                           |                                                                                                                        |

## 7. Table: Migrator\_call\_remove\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-15 02:34:05+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13617722                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1d7d717aae65b737451275beffbb6480d9027253fa95b153a6481a0778c8fbf8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 146                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 1000000000000                                                      |                                                                                                                        |

## 8. Table: Migrator\_call\_transferFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-07-28 22:06:27+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15233566                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9968a738676b7e831fee387aa5baae7585a8c9e8aaa7458345963a6aa37dd019 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 178                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| sender             | VARCHAR   | 0xf977814e90da44bfa03b6295a0616a897441acec                         |                                                                                                                        |
| recipient          | VARCHAR   | 0xcc91fcb1b761e7bc5276770dde398528cb170612                         |                                                                                                                        |
| amount             | VARCHAR   | 10000000000000000000000000                                         |                                                                                                                        |

## 9. Table: Migrator\_call\_transfer\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| recipient          | VARCHAR   |                                                                                                                        |             |
| amount             | VARCHAR   |                                                                                                                        |             |

## 10. Table: Migrator\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-13 00:48:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14375278                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4a723c23301b39ae5bc12e6711f65ccbb99266e7bc0e8c6a66ef9e6a8f1fd95c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x60ee0c8bb493b79286a54997322904f74fba3736                         |                                                              |
| spender           | VARCHAR   | 0x60ee0c8bb493b79286a54997322904f74fba3736                         |                                                              |
| value             | VARCHAR   | 999999999999999999999999999999999                                  |                                                              |

## 11. Table: Migrator\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-10 13:19:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14748784                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4e0db25776203379ca8bf944cb654a9e5280cdc46dadb41a1d6e4a1a6cf9514 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf39c29d8f6851d87c40c83b61078eb7384f7cb51                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x66b870ddf78c975af5cd8edc6de25eca81791de1                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 3026255231533                                                      |                                                              |

## 12. Table: TokenBridge\_call\_attestToken\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-29 01:24:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17148470                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa51c87187e77782c2ac033d2f69c17e0941c47e4a2d680ec2412d9cc955b5b03 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 59                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| tokenAddress       | VARCHAR   | 0x8e870d67f660d95d5be530380d0ec0bd388289e1                         |                                                                                                                        |
| nonce              | VARCHAR   | 2400780288                                                         |                                                                                                                        |

## 13. Table: TokenBridge\_call\_completeTransferAndUnwrapETH\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-13 21:40:04+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14579615                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x712d6a084f9c21732fedf917dedcf0fd7264d66bec0107a564f6f35d1e9ae9c9                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 27                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| encodedVm          | VARCHAR   | 0x01000000010d0121e62672d13f976193acf8a1a441b4e146e0d1afb888ca800298e11e0378d39a0e637325e4ac3b873f42 |                                                                                                                        |

## 14. Table: TokenBridge\_call\_completeTransfer\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-04 14:21:32+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13740278                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xfa16c8d8ce39642b31c67c10e9aa4661e479ab6903cdbee58094bc6508a810ac                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 259                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| encodedVm          | VARCHAR   | 0x01000000010d00d68636ef09381ca5f09fb041e7a4cc4be76d4afffdd969855d908b3d33f6d9de7fa57572e57b89d38553 |                                                                                                                        |

## 15. Table: TokenBridge\_call\_createWrapped\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-20 14:58:32+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14043111                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1a5fcf990b4d5fd45c2cdd13d257348c0779512cafc1500531961660ab2b48a4                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 216                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| encodedVm          | VARCHAR   | 0x01000000010d0233dd66abae4d7f3b0191059bdd741141ad199c050af0a9c9829cad003c40de6e394cad9e566430fd2168 |                                                                                                                        |

## 16. Table: TokenBridge\_call\_encodeAssetMeta\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| meta               | VARCHAR   |                                                                                                                        |             |

## 17. Table: TokenBridge\_call\_encodeTransfer\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| transfer           | VARCHAR   |                                                                                                                        |             |

## 18. Table: TokenBridge\_call\_initialize\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-26 05:56:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16052213                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1a06d8baa2dada74de23f9fe69bdb510ab17f84df9d3d6eb54f32996dc33e40b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 141                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 19. Table: TokenBridge\_call\_parseAssetMeta\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| encoded            | VARCHAR   |                                                                                                                        |             |

## 20. Table: TokenBridge\_call\_parseRegisterChain\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| encoded            | VARCHAR   |                                                                                                                        |             |

## 21. Table: TokenBridge\_call\_parseTransfer\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-21 12:27:37+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14628283                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbc76763b5af87895dacafd1a196e2e2382f23a623d73f24f9e4a636c1f3ea025                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 152                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                                                    | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| encoded            | VARCHAR   | 0x0100000000000000000000000000000000000000000000000000000000dd26c069000000000000000000000000a0b86991 |                                                                                                                        |

## 22. Table: TokenBridge\_call\_parseUpgrade\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| encoded            | VARCHAR   |                                                                                                                        |             |

## 23. Table: TokenBridge\_call\_registerChain\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-30 14:18:22+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15440846                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x94bd648898d57b9559234f920d2e198c3b4f5b2b7966dc3c308a6db9d466888e                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 177                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| encodedVM          | VARCHAR   | 0x01000000020d009391f4e4d74d097dbaae292a2191e1b3e47505d444f1eee2e7727a5d1541de0402fbcecfcb0898b61b14 |                                                                                                                        |

## 24. Table: TokenBridge\_call\_transferTokens\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-21 02:19:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17738504                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5815caf0d9d8f8740b37983608295629762ffc2359c08a439df2cb0504b4d6bf | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 74                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| token              | VARCHAR   | 0x1fced53ddb60ce39cf7e8cce2674524c22c648d2                         |                                                                                                                        |
| amount             | VARCHAR   | 74871589668497360                                                  |                                                                                                                        |
| recipientChain     | VARCHAR   | 4                                                                  |                                                                                                                        |
| recipient          | VARCHAR   | 0x000000000000000000000000a52db5fdbed5dd5eaf75499a1519e97722406e2a |                                                                                                                        |
| arbiterFee         | VARCHAR   | 0                                                                  |                                                                                                                        |
| nonce              | VARCHAR   | 1889337344                                                         |                                                                                                                        |

## 25. Table: TokenBridge\_call\_updateWrapped\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-06 17:21:15+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13564281                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xde418b78aa78755a0259cf4098683c2d54f363775910a649833d55e71ea53d41                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 198                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| encodedVm          | VARCHAR   | 0x01000000010d02b3e1c39f0c673a8ca5b8ce4bf738055525b58cfe380bbd7469eddf54f2f2498707ee20ca02c810cf9310 |                                                                                                                        |

## 26. Table: TokenBridge\_call\_upgrade\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-27 16:35:52+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14088802                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xd52dad3dcd2412fed086ff08a67b8169ba84be9b4ab20c4ec779057e41664d67                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 78                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| encodedVM          | VARCHAR   | 0x01000000010d025befa2139addaf1985aaa05ea32482b9570e0d925dabd9e41339231e4e4b564731f43c486e34113418a7 |                                                                                                                        |

## 27. Table: TokenBridge\_call\_wrapAndTransferETH\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-10 11:24:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17662943                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x266ec52eebb796cb273324db7499c6d8ef2bbb5eb92ead48b5374300a444a49e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 101                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| recipientChain     | VARCHAR   | 1                                                                  |                                                                                                                        |
| recipient          | VARCHAR   | 0x00bb92d08783c6c5fef909428cde09b14c3b327f0916a88e8c041753fc944e97 |                                                                                                                        |
| arbiterFee         | VARCHAR   | 1073088025410725                                                   |                                                                                                                        |
| nonce              | VARCHAR   | 2850750464                                                         |                                                                                                                        |

## 28. Table: TokenBridge\_event\_AdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousAdmin     | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 29. Table: TokenBridge\_event\_BeaconUpgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| beacon            | VARCHAR   |                                                              |             |

## 30. Table: TokenBridge\_event\_ContractUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-27 16:35:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14088802                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd52dad3dcd2412fed086ff08a67b8169ba84be9b4ab20c4ec779057e41664d67 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                         | Address of the contract that produced the log                |
| oldContract       | VARCHAR   | 0x67145cdb0d69678e9c48106f646c1b7ef69813a4                         |                                                              |
| newContract       | VARCHAR   | 0x91175aee6dac41b9c1f749ded077568ad93b84ca                         |                                                              |

## 31. Table: TokenBridge\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-01 14:23:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15453374                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x681919e52611294f53e270f03a6615fe624deebfba3aa6de7bc842bd64b1d3b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ee18b2214aff97000d974cf647e7c347e8fa585                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0xfa71b241b168d2876722c6d8856d3e4f311b8c1e                         |                                                              |

## 32. Table: Wormhole\_call\_lockAssets\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-02-27 04:01:52+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11937086                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x39c1c5949ba6dc31df3610f93446e3034434ff46aa9c358ffc929eb929de53b2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 125                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf92cd566ea4864356c5491c177a430c222d7e678                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| asset              | VARCHAR   | 0xe6f1994edb6a06e13d4d035af71e907cf3431974                         |                                                                                                                        |
| amount             | VARCHAR   | 200000000                                                          |                                                                                                                        |
| recipient          | VARCHAR   | 0x970dc0118b70e1e7b3b614b73da50036e8124fb37e5919f1e210acef580e4d1f |                                                                                                                        |
| target\_chain      | VARCHAR   | 1                                                                  |                                                                                                                        |
| nonce              | VARCHAR   | 10                                                                 |                                                                                                                        |
| refund\_dust       | VARCHAR   | false                                                              |                                                                                                                        |

## 33. Table: Wormhole\_call\_lockETH\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-04-26 05:24:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12314031                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x053f97027daa37e4444d2d39a051d399801e5c27e71305b8924eba9ae2d08ef8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 246                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf92cd566ea4864356c5491c177a430c222d7e678                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| recipient          | VARCHAR   | 0xf0bba1ca6276c2136283b1dd7b48280b0ccf90eb4b4ce4c4ed52b047f44daca4 |                                                                                                                        |
| target\_chain      | VARCHAR   | 1                                                                  |                                                                                                                        |
| nonce              | VARCHAR   | 301                                                                |                                                                                                                        |

## 34. Table: Wormhole\_call\_submitVAA\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-08-18 16:45:58+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13050352                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe0e61e9c64cd45fe7da59106af6e1370f02e3ac1cbad5eaf2fd19f760e56f658                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 173                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf92cd566ea4864356c5491c177a430c222d7e678                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| vaa                | VARCHAR   | 0x01000000010d005f06d9e1268224a3d25ed5b6775e7ee695d6b0caa196bc471004e083508ab2c2462297f1834145b9b7a6 |                                                                                                                        |

## 35. Table: Wormhole\_event\_LogGuardianSetChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-02 23:54:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11779889                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x833e7bec034d9904713d6a7dc13d197ec41af2d0611122603289a1e69ae72c43 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 280                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf92cd566ea4864356c5491c177a430c222d7e678                         | Address of the contract that produced the log                |
| oldGuardianIndex  | VARCHAR   | 0                                                                  |                                                              |
| newGuardianIndex  | VARCHAR   | 1                                                                  |                                                              |

## 36. Table: Wormhole\_event\_LogTokensLocked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-29 01:57:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16072511                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2366d2ff952dff097ba2938c43ec0a381a733b134162f7c09f32b895a2c266b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf92cd566ea4864356c5491c177a430c222d7e678                         | Address of the contract that produced the log                |
| target\_chain     | VARCHAR   | 1                                                                  |                                                              |
| token\_chain      | VARCHAR   | 2                                                                  |                                                              |
| token\_decimals   | VARCHAR   | 9                                                                  |                                                              |
| token             | VARCHAR   | 0x000000000000000000000000c02aaa39b223fe8d0a0e5c4f27ead9083c756cc2 |                                                              |
| sender            | VARCHAR   | 0x000000000000000000000000e2e2d9e31d7e1cc1178fe0d1c5950f6c809816a3 |                                                              |
| recipient         | VARCHAR   | 0x475bb5a0d71cb08ab6d6bdd3ae4f648a3aad4b3937ea6c77ffef9d447f204db1 |                                                              |
| amount            | VARCHAR   | 1000000                                                            |                                                              |
| nonce             | VARCHAR   | 129                                                                |                                                              |
