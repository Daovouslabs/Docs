# balancer

## 1. Table: V2\_BalancerPoolToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-05 20:14:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19883586                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf746a0bdedb54e608424e7218db032ef72b378feaeae4441a5250bf2005d2e13 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 442                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0297e37f1873d2dab4487aa67cd56b58e2f27875                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xecdac24abe18924b2dbe4e59f853c87aa3f735dd                         |                                                              |
| value             | VARCHAR   | 1525255925137473240                                                |                                                              |

## 2. Table: V2\_ComposableStablePoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-09 12:11:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40144844                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11d2688d7342358137de1fbc22a03905abbe7d89c79e3ef2cbbf53338666efc6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bc6c0e73edaa66ef3f6e2f27b0ee8661834c6c9                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x9c50e62afe9bfc76fbead12ea8877bfaadc4ac47                         |                                                              |

## 3. Table: V2\_ComposableStablePool\_event\_AmpUpdateStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-21 12:34:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44167828                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x37dac3f9bae683c3d0921cb2f92417cca3ae01fbeded4532ecb65a46e45fd2ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a77ef015ddcd972fd9ba2c7d5d658689d090f1a                         | Address of the contract that produced the log                |
| startValue        | VARCHAR   | 597965                                                             |                                                              |
| endValue          | VARCHAR   | 1000000                                                            |                                                              |
| startTime         | VARCHAR   | 1687350855                                                         |                                                              |
| endTime           | VARCHAR   | 1688107982                                                         |                                                              |

## 4. Table: V2\_ComposableStablePool\_event\_AmpUpdateStopped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-29 07:49:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33704911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7dd2081e43679c9a1bf362d66a4bb5ee82ad004fc4b4315a1183467063008f93 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa48d164f6eb0edc68bd03b56fa59e12f24499ad1                         | Address of the contract that produced the log                |
| currentValue      | VARCHAR   | 200000                                                             |                                                              |

## 5. Table: V2\_ComposableStablePool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-10 19:10:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39145544                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd45f0cd4a147e4b5c3d665603357144def751e9b6f25c6eae433e1253464e8e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 825                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7d60a4cb5ca92e2da965637025122296ea6854f9                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x83f1bc1d214be8fbea32ef47fa1e867267d89606                         |                                                              |
| spender           | VARCHAR   | 0x0593e77cbfa4ca5472d8070e19e2b92e9e95a33c                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: V2\_ComposableStablePool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 7. Table: V2\_ComposableStablePool\_event\_ProtocolFeePercentageCacheUpdated\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-03-20 12:35:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 40565477                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x3cb11721cc24c4ef1466baa403dfd8424365a07a309152e4819c2b1f75ed4a7c | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x36a0ee903841584f47e3c774b59e0cbfba46080f                         | Address of the contract that produced the log                |
| feeType               | VARCHAR   | 2                                                                  |                                                              |
| protocolFeePercentage | VARCHAR   | 500000000000000000                                                 |                                                              |

## 8. Table: V2\_ComposableStablePool\_event\_RecoveryModeStateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 12:56:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37742710                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc43d37b2afe0495fbe2399a801b2c7571085ee3c5427f4a4ac6064292c2aa5e1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d46979fd4c5f7a04f65111399cff3da2dab5bd9                         | Address of the contract that produced the log                |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 9. Table: V2\_ComposableStablePool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 12:03:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45381606                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08b8d706cc0321f7ec3058a1102446ecee3798a97dcc810e112178bf848ebad3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x48e6b98ef6329f8f0a30ebb8c7c960330d648085                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 50000000000000                                                     |                                                              |

## 10. Table: V2\_ComposableStablePool\_event\_TokenRateCacheUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-30 04:29:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34972738                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6508678e0e3c4713dad6c6ab5d0823ea3520cb62de744cd27bd487a76df8c6f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x48e6b98ef6329f8f0a30ebb8c7c960330d648085                         | Address of the contract that produced the log                |
| tokenIndex        | VARCHAR   | 0                                                                  |                                                              |
| rate              | VARCHAR   | 1000000000000000000                                                |                                                              |

## 11. Table: V2\_ComposableStablePool\_event\_TokenRateProviderSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-13 12:17:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40297469                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a771f82b7a7977fb2b8b746a4a10c8a54d9c8cb2b351d7c9153582b8bec83d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9a020bdc2faff5bd24c6acc2020d01ff9f2c627a                         | Address of the contract that produced the log                |
| tokenIndex        | VARCHAR   | 1                                                                  |                                                              |
| provider          | VARCHAR   | 0x9e34631547adcf2f8cefa0f5f223955c7b137571                         |                                                              |
| cacheDuration     | VARCHAR   | 1800                                                               |                                                              |

## 12. Table: V2\_ComposableStablePool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-22 00:15:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38368480                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7efcb83097fcf29c0b42cec019f592aea96f7bcc79cbbef191d94130c0664d0c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 477                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x05f21bacc4fd8590d1eaca9830a64b66a733316c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0fa7c71a07af3784b0784d058ad104a1471afa36                         |                                                              |
| to                | VARCHAR   | 0xa02883e738854a17a7cd37f0871e9c2c0ed8cf7f                         |                                                              |
| value             | VARCHAR   | 9216750521700945772                                                |                                                              |

## 13. Table: V2\_LiquidityBootstrappingPoolFactory\_call\_create\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-07 04:27:46+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 22226308                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7e54d5903d172f23638ac8541aa4d5527ca3fe5516c75312b9c209fb61af8716                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 72                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x751a0bc0e3f75b38e01cf25bfce7ff36de1c87de                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name               | VARCHAR   | ELM Copper Launch                                                                     |                                                                                                                        |
| symbol             | VARCHAR   | ELM\_TLA                                                                              |                                                                                                                        |
| tokens             | VARCHAR   | 0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619,0x8296dD15f2DB0bC5f8AA18A9cc4B0F8612E32BD7 |                                                                                                                        |
| weights            | VARCHAR   | 10000000000000000,990000000000000000                                                  |                                                                                                                        |
| swapFeePercentage  | VARCHAR   | 300000000000000                                                                       |                                                                                                                        |
| owner              | VARCHAR   | 0x39399478937ee3bfa406ac648ea30466f4d2a63b                                            |                                                                                                                        |
| swapEnabledOnStart | VARCHAR   | false                                                                                 |                                                                                                                        |

## 14. Table: V2\_LiquidityBootstrappingPoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-01 23:35:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22029012                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1bb3945627fc771fb1892f5f17f63f1be728fbeec7c6e4037f9c8b085f57e9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 286                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x751a0bc0e3f75b38e01cf25bfce7ff36de1c87de                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x76d1730b061a30e5f2713481b8de1e7f584f72b6                         |                                                              |

## 15. Table: V2\_LiquidityBootstrappingPool\_event\_GradualWeightUpdateScheduled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-20 04:55:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21581593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x313501b89d04cbcd495600068e1d552655d6af37b70c3bff7b95d7eeeae760d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 407                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x205ef52dc36917e2cf3b8f2e6a759caec3094fed                         | Address of the contract that produced the log                |
| startTime         | VARCHAR   | 1637384130                                                         |                                                              |
| endTime           | VARCHAR   | 1637384130                                                         |                                                              |
| startWeights      | VARCHAR   | 390000000000000000,610000000000000000                              |                                                              |
| endWeights        | VARCHAR   | 390000000000000000,610000000000000000                              |                                                              |

## 16. Table: V2\_LiquidityBootstrappingPool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 17. Table: V2\_LiquidityBootstrappingPool\_event\_SwapEnabledSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-14 01:15:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21340150                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0c5b75ca38c1f07ede78677862bdc8790709cd21500ac4ec8d084b28302a04bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 657                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6aa8a7b23f7b3875a966ddcc83d5b675cc9af54b                         | Address of the contract that produced the log                |
| swapEnabled       | VARCHAR   | true                                                               |                                                              |

## 18. Table: V2\_LiquidityBootstrappingPool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-10 15:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21213927                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38bff521eb72cda16cdcf12da232aac0a41e42c2d95235b922e1a14ed5e42321 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 320                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9234f3a62154f7fcda5346c35d8d53f608651864                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 10000000000000000                                                  |                                                              |

## 19. Table: V2\_LiquidityBootstrappingPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-24 02:33:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21729328                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x186b9a38c1246ee55bccac2d767838d83700668724cd2c25706bd83e3b8e609c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 485                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b7f8107de88c75603f3cb9152ce8a4d43910fa8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xf1ef7a69fa5e767691b0b9bbf3bbe0432e3497ea                         |                                                              |
| value             | VARCHAR   | 19998594640523602                                                  |                                                              |

## 20. Table: V2\_MetaStablePoolFactory\_call\_create\_history

| Column                 | Type      | Example                                                                               | Description                                                                                                            |
| ---------------------- | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp       | TIMESTAMP | 2022-10-31 10:45:33+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number          | INTEGER   | 35023862                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash      | VARCHAR   | 0xeb22bb71a2059c69168fca577580ee26b92e00eb532e82fff7a9bdd7097b0dfb                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index     | INTEGER   | 48                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address         | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address            | VARCHAR   | 0xdae7e32adc5d490a43ccba1f0c736033f2b4efca                                            | Address of the called contract                                                                                         |
| status                 | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                  | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name                   | VARCHAR   | Python Test MetaStable Pool                                                           |                                                                                                                        |
| symbol                 | VARCHAR   | PTMSP                                                                                 |                                                                                                                        |
| tokens                 | VARCHAR   | 0x0d500B1d8E8eF31E21C99d1Db9A6444d3ADf1270,0x3A58a54C066FdC0f2D55FC9C89F0415C92eBf3C4 |                                                                                                                        |
| amplificationParameter | VARCHAR   | 50                                                                                    |                                                                                                                        |
| rateProviders          | VARCHAR   | 0x87393BE8ac323F2E63520A6184e5A8A9CC9fC051,0x0000000000000000000000000000000000000000 |                                                                                                                        |
| priceRateCacheDuration | VARCHAR   | 10,10                                                                                 |                                                                                                                        |
| swapFeePercentage      | VARCHAR   | 100000000000000                                                                       |                                                                                                                        |
| oracleEnabled          | VARCHAR   | true                                                                                  |                                                                                                                        |
| owner                  | VARCHAR   | 0x326da15e2dccdc96c77b1046b239ad552a3c224e                                            |                                                                                                                        |

## 21. Table: V2\_MetaStablePoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-11 15:57:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37949056                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1858e3c0b1c40ca62f289a9902fc0a730443d595ad16b343cb70915fe1c9b9d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 446                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdae7e32adc5d490a43ccba1f0c736033f2b4efca                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x34a81e8956bf20b7448b31990a2c06f96830a6e4                         |                                                              |

## 22. Table: V2\_MetaStablePool\_event\_AmpUpdateStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-02 12:34:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25494694                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x655ba0abb39b3b358bb24c8c522f5e06f286ad066d81b58732d0a378ef03ff1a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x76f20de6f13523d3870e93bd37a2028d13666833                         | Address of the contract that produced the log                |
| startValue        | VARCHAR   | 50000                                                              |                                                              |
| endValue          | VARCHAR   | 50000                                                              |                                                              |
| startTime         | VARCHAR   | 1646224479                                                         |                                                              |
| endTime           | VARCHAR   | 1646224479                                                         |                                                              |

## 23. Table: V2\_MetaStablePool\_event\_AmpUpdateStopped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 13:19:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34169472                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08a51f32f7bee81a92d2144839184f9020e4f2ad5e7e93ca36e893a17c51d468 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 426                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf6d037883cc52cad1a8238064b3041c754a0baa9                         | Address of the contract that produced the log                |
| currentValue      | VARCHAR   | 50000                                                              |                                                              |

## 24. Table: V2\_MetaStablePool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-20 10:41:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40562367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x54603c63106e14a5f4cd7ed5ec92c2a4b6cfb3957b2933144bb450418ba01e6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaf5e0b5425de1f5a630a8cb5aa9d97b8141c908d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x8fc2779b86f1034b696585acbfb202dbf9cc48c8                         |                                                              |
| spender           | VARCHAR   | 0x755e426a8b445eae53b1c051c1e7aca7381fcdb7                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 25. Table: V2\_MetaStablePool\_event\_OracleEnabledChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-10 23:49:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37921111                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x574b9e90b313ed52f66487c1a883b04d6d991f48233b97988104861037b863a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf6ca5db5f1b2a0764bd7609787ba6928ecda1c17                         | Address of the contract that produced the log                |
| enabled           | VARCHAR   | false                                                              |                                                              |

## 26. Table: V2\_MetaStablePool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 27. Table: V2\_MetaStablePool\_event\_PriceRateCacheUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-15 20:29:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39332821                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x389751bddc9935e4d8cb1515ccdfcc5caa6269d240434e751992bb254d539a72 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34a81e8956bf20b7448b31990a2c06f96830a6e4                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xaf0d9d65fc54de245cda37af3d18cbec860a4d4b                         |                                                              |
| rate              | VARCHAR   | 1033649459242384177                                                |                                                              |

## 28. Table: V2\_MetaStablePool\_event\_PriceRateProviderSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-16 07:21:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41589448                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xadb0a2d48a0e00dbf4c84e128b099eae8fbe2fc63fbed23646f82b8920cfec82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9817e42134245e4b77487387c264834f70ffb6b5                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x3d468ab2329f296e1b9d8476bb54dd77d8c2320f                         |                                                              |
| provider          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| cacheDuration     | VARCHAR   | 21600                                                              |                                                              |

## 29. Table: V2\_MetaStablePool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-05 11:24:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44710288                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8e9d0f030e74738fb730b34ec61e541606e49b755d9ebdb03e35fb99462ef71 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 123                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc17636e36398602dd37bb5d1b3a9008c7629005f                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 60000000000000                                                     |                                                              |

## 30. Table: V2\_MetaStablePool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 21:13:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25778641                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x126ea9a5a46465cc806cfe9159f2726a2fb14672ed342b12e44a8d917d23d5b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xaf5e0b5425de1f5a630a8cb5aa9d97b8141c908d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x952198e93051d8157dec65a9ee3982ff741bf4a1                         |                                                              |
| value             | VARCHAR   | 1376755788128146156                                                |                                                              |

## 31. Table: V2\_StablePoolFactory\_call\_create\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-22 10:40:26+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 27439148                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xea49a78b5ac4477111f32b9d14c5b79015f78b0f23552a6829589391668d76e0                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 23                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc66ba2b6595d3613ccab350c886ace23866ede24                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name               | VARCHAR   | Balancer polygon tetuBal-BPT-80BAL-20WETH Stable Pool                                 |                                                                                                                        |
| symbol             | VARCHAR   | Polygon tetuBAL-80BAL-20WETH                                                          |                                                                                                                        |
| tokens             | VARCHAR   | 0x3d468AB2329F296e1b9d8476Bb54Dd77D8c2320f,0x7fC9E0Aa043787BFad28e29632AdA302C790Ce33 |                                                                                                                        |
| weights            | VARCHAR   | None                                                                                  |                                                                                                                        |
| swapFeePercentage  | VARCHAR   | 3000000000000000                                                                      |                                                                                                                        |
| owner              | VARCHAR   | 0xaaa01cb6c7570733ae3eded876a98c9bc373803b                                            |                                                                                                                        |

## 32. Table: V2\_StablePoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-26 14:48:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19538901                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb723e2b71093ecddf1354e422c81ebe9442ed99b531b1943eb0bbc5a3e94f076 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc66ba2b6595d3613ccab350c886ace23866ede24                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x6641a8c1d33bd3dec8dd85e69c63cafb5bf36388                         |                                                              |

## 33. Table: V2\_StablePool\_event\_AmpUpdateStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-19 16:02:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20384985                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18c7e1c9235c6e93878e55a87ed249f9d0ceb9d12ee584794e92f80f7645686d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d34e5dd4d8f043557145598e4e2dc286b35fd4f                         | Address of the contract that produced the log                |
| startValue        | VARCHAR   | 600000                                                             |                                                              |
| endValue          | VARCHAR   | 600000                                                             |                                                              |
| startTime         | VARCHAR   | 1634659358                                                         |                                                              |
| endTime           | VARCHAR   | 1634659358                                                         |                                                              |

## 34. Table: V2\_StablePool\_event\_AmpUpdateStopped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-22 10:40:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27439148                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea49a78b5ac4477111f32b9d14c5b79015f78b0f23552a6829589391668d76e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32c471dd7ed2df5d62c6fc498fe6293fbfd66597                         | Address of the contract that produced the log                |
| currentValue      | VARCHAR   | 500000                                                             |                                                              |

## 35. Table: V2\_StablePool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-03 11:15:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18699385                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x697c3f3dc4c96081734365a3b36ae587c2867924177ed375f2e210c7249e6d11 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06df3b2bbb68adc8b0e302443692037ed9f91b42                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x1c634804ba4f83a66134cd92961066f7adc6b928                         |                                                              |
| spender           | VARCHAR   | 0x4aa8def481d19564596754cd2108086cf0bdc71b                         |                                                              |
| value             | VARCHAR   | 1162228325820                                                      |                                                              |

## 36. Table: V2\_StablePool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 37. Table: V2\_StablePool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-26 14:48:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19538901                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb723e2b71093ecddf1354e422c81ebe9442ed99b531b1943eb0bbc5a3e94f076 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6641a8c1d33bd3dec8dd85e69c63cafb5bf36388                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 400000000000000                                                    |                                                              |

## 38. Table: V2\_StablePool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 12:36:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37782351                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea6e6b14bcf34916b2f1f159d221c34c525ff057ffc8862c3b7d539baebff019 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 305                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06df3b2bbb68adc8b0e302443692037ed9f91b42                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x67586cb5bcab1db5949d0638712d364a74de4cc1                         |                                                              |
| value             | VARCHAR   | 780178858090758734                                                 |                                                              |

## 39. Table: V2\_Vault\_call\_batchSwap\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-12 19:35:12+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37996799                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa33c608f9a054a9fe17ec504e778a9a9821b0b2e790bfad66bd4ef299193e3b1                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 8                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| kind               | VARCHAR   | 1                                                                                                    |                                                                                                                        |
| swaps              | VARCHAR   | 0x8f9dd2064eb38e8e40f2ab67bde27c0e16ea9b080002000000000000000004ca,1,2,79999256877441699378,0x,0x029 |                                                                                                                        |
| assets             | VARCHAR   | 0x0000000000000000000000000000000000000000,0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619,0x431CD3C9AC9F |                                                                                                                        |
| funds              | VARCHAR   | 0xbEd4308884405AAB39a78fD3C863076155bd4e5a,false,0xbEd4308884405AAB39a78fD3C863076155bd4e5a,false    |                                                                                                                        |
| limits             | VARCHAR   | 2710567300000000000,0,-80000000000000000000,0                                                        |                                                                                                                        |
| deadline           | VARCHAR   | 1673558087                                                                                           |                                                                                                                        |

## 40. Table: V2\_Vault\_call\_swap\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-13 13:16:04+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 43865279                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x00395e95cd95df55a3417989e491b2608caf9f7cedae8772043d6b082b4b002c                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 32                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| singleSwap         | VARCHAR   | 0x43894de14462b421372bcfe445fa51b1b4a0ff3d000000000000000000000b36,0,0x7ceB23fD6bC0adD59E62ac2557827 |                                                                                                                        |
| funds              | VARCHAR   | 0x04951322D576126B6BEfAe150C4bB506c7b1daC6,false,0xd18d5D377eb23362e54Fa496597d7E962d56C554,true     |                                                                                                                        |
| limit              | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| deadline           | VARCHAR   | 1686665748                                                                                           |                                                                                                                        |

## 41. Table: V2\_Vault\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 00:07:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42633164                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcbe19cab89d39692221d743f0ef96502ea385ba3d8db1728ca7dc850815ecc82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| recipient         | VARCHAR   | 0x17dad6e5a36e26220f7716d39d9da3d45f998206                         |                                                              |
| token             | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| amount            | VARCHAR   | 101000000000000000000                                              |                                                              |
| feeAmount         | VARCHAR   | 0                                                                  |                                                              |

## 42. Table: V2\_Vault\_event\_InternalBalanceChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-03 23:04:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32656655                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82f3f8adf055f6e78a566373f06819ba0060c03624d17a7eb3d4876fdd42dd1b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0000e0ca771e21bd00057f54a68c30d400000000                         |                                                              |
| token             | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                         |                                                              |
| delta             | VARCHAR   | 4178662646600                                                      |                                                              |

## 43. Table: V2\_Vault\_event\_PoolBalanceChanged\_history

| Column             | Type      | Example                                                                                              | Description                                                  |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-01-01 17:04:03+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 23229161                                                                                             | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x909f7528662c9a62e2ec76dfafd4a2f2ee0e04ad5e6a0fb5bb599047ab66af66                                   | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 222                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                                                           | Address of the contract that produced the log                |
| poolId             | VARCHAR   | 0x514f35a92a13bc7093f299af5d8ebb1387e42d6b000100000000000000000058                                   |                                                              |
| liquidityProvider  | VARCHAR   | 0xeda18bbf6d77a93ba70fee0d2f317bdd23032770                                                           |                                                              |
| tokens             | VARCHAR   | 0x0d500B1d8E8eF31E21C99d1Db9A6444d3ADf1270,0x24834BBEc7E39ef42f4a75EAF8E5B6486d3F0e57,0x2791Bca1f2de |                                                              |
| deltas             | VARCHAR   | 7118093121493733017,0,0,0,0,0                                                                        |                                                              |
| protocolFeeAmounts | VARCHAR   | 147108704550051540,0,0,0,0,0                                                                         |                                                              |

## 44. Table: V2\_Vault\_event\_PoolBalanceManaged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 10:04:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42053701                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6bb8fdf2900e5abf7ee279d3f2370b27f7df1e0563cec3a2166bbdc1f6fe164 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 152                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x7c82a23b4c48d796dee36a9ca215b641c6a8709d000000000000000000000acd |                                                              |
| assetManager      | VARCHAR   | 0xf30d0756053734128849666e01a0a4c04a5603c6                         |                                                              |
| token             | VARCHAR   | 0x236975da9f0761e9cf3c2b0f705d705e22829886                         |                                                              |
| cashDelta         | VARCHAR   | 0                                                                  |                                                              |
| managedDelta      | VARCHAR   | -91669442689                                                       |                                                              |

## 45. Table: V2\_Vault\_event\_PoolRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-19 10:39:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35798465                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x120a0f204ed2bbe253c289b6a799cd2c6506f8973af19bb2e94b3d75f650ae66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x56decb6fff1be2209f6dd536fc42042f5630e2320002000000000000000008f5 |                                                              |
| poolAddress       | VARCHAR   | 0x56decb6fff1be2209f6dd536fc42042f5630e232                         |                                                              |
| specialization    | VARCHAR   | 2                                                                  |                                                              |

## 46. Table: V2\_Vault\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-08 22:41:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41306449                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f3de80ac7e499cc0972194a276b8f3ad6a0ba320149c49bca829ee97691b6d3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 361                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba12222222228d8ba445958a75a0704d566bf2c8                         | Address of the contract that produced the log                |
| poolId            | VARCHAR   | 0x8a8fcd351ed553fc75aecbc566a32f94471f302e000100000000000000000081 |                                                              |
| tokenIn           | VARCHAR   | 0x00e5646f60ac6fb446f621d146b6e1886f002905                         |                                                              |
| tokenOut          | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                         |                                                              |
| amountIn          | VARCHAR   | 30582943848661075499                                               |                                                              |
| amountOut         | VARCHAR   | 43315528128169182                                                  |                                                              |

## 47. Table: V2\_WeightedPool2TokensFactory\_call\_create\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-07-01 23:39:02+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16382704                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7c47bb296deeb418d16e4187fdf1f44fd9bf96fe76093e7c4deeef7f13163f8e                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 4                                                                                     | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa5bf2ddf098bb0ef6d120c98217dd6b141c74ee0                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name               | VARCHAR   | Balancer 80 BIFI 20 WETH                                                              |                                                                                                                        |
| symbol             | VARCHAR   | B-80BIFI-20WETH                                                                       |                                                                                                                        |
| tokens             | VARCHAR   | 0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619,0xFbdd194376de19a88118e84E279b977f165d01b8 |                                                                                                                        |
| weights            | VARCHAR   | 200000000000000000,800000000000000000                                                 |                                                                                                                        |
| swapFeePercentage  | VARCHAR   | 2500000000000000                                                                      |                                                                                                                        |
| oracleEnabled      | VARCHAR   | true                                                                                  |                                                                                                                        |
| owner              | VARCHAR   | 0x0000000000000000000000000000000000000000                                            |                                                                                                                        |

## 48. Table: V2\_WeightedPool2TokensFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-14 15:23:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20213910                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf80bfb8c876b9e90fb56b1e9ba0a681548626087dee2fa2b88374ca2ad90e415 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 192                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa5bf2ddf098bb0ef6d120c98217dd6b141c74ee0                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0xaac98ee71d4f8a156b6abaa6844cdb7789d086ce                         |                                                              |

## 49. Table: V2\_WeightedPool2Tokens\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 01:56:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44932387                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce6e9dfb31c57c1b706bd8673b03c4ea585c01f8c886cc108a49e5e21f53ecc1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x186084ff790c65088ba694df11758fae4943ee9e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x1a1608d260d0044f91b0d1721deb14ad6c8bac0f                         |                                                              |
| spender           | VARCHAR   | 0x2b33060a91b98ed782676ebfb8c004126bc226a1                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 50. Table: V2\_WeightedPool2Tokens\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 51. Table: V2\_WeightedPool2Tokens\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-09 18:36:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23527727                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1867b474802c2582b35bcabede6aedcbe00fba86d90e595a57599e571118b914 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f1f16b025f703ee985b58ced48daf93dad2f7ef                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 10000000000000000                                                  |                                                              |

## 52. Table: V2\_WeightedPool2Tokens\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 16:16:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29361830                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4dd98b071c99a0e7dac9fd5c0e406a79052660bf51269290e7c15ab14a338aab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 246                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c6ee304399dbdb9c8ef030ab642b10820db8f56                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x8a5f3e8978f4d7e3578f5b3197a528a68f3f7dee                         |                                                              |
| value             | VARCHAR   | 8915930470085793170299                                             |                                                              |

## 53. Table: V2\_WeightedPoolFactory\_call\_create\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-07 19:33:01+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 23451657                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1d3b0fd219573aa655f7a7ab83011a046a8630256aee192c6a60bbf5c6527a67                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 101                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x8e9aa87e45e92bad84d5f8dd1bff34fb92637de9                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| name               | VARCHAR   | 30CRV-70DAI                                                                           |                                                                                                                        |
| symbol             | VARCHAR   | DAI-CRV                                                                               |                                                                                                                        |
| tokens             | VARCHAR   | 0x172370d5Cd63279eFa6d502DAB29171933a610AF,0x8f3Cf7ad23Cd3CaDbD9735AFf958023239c6A063 |                                                                                                                        |
| weights            | VARCHAR   | 300000000000000000,700000000000000000                                                 |                                                                                                                        |
| swapFeePercentage  | VARCHAR   | 3000000000000000                                                                      |                                                                                                                        |
| owner              | VARCHAR   | 0xba1ba1ba1ba1ba1ba1ba1ba1ba1ba1ba1ba1ba1b                                            |                                                                                                                        |

## 54. Table: V2\_WeightedPoolFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 14:34:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19173636                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6eab2865a070a5262fdcef5917ace4bc9de35953bf1512098a3f97ecaf7c4bb5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e9aa87e45e92bad84d5f8dd1bff34fb92637de9                         | Address of the contract that produced the log                |
| pool              | VARCHAR   | 0x6fe95fafe2f86158c77bf18350672d360bfc78a2                         |                                                              |

## 55. Table: V2\_WeightedPool\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-07 21:17:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22254175                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23cc9fa659e1b6f13aa00e831db59fb9f57b9086651898d3effc3d844d3ded03 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 313                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0297e37f1873d2dab4487aa67cd56b58e2f27875                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x41222a33d9b40173118bd8b80114a9ce3617664e                         |                                                              |
| spender           | VARCHAR   | 0x5c6bc2287c48a2c9fc2f0533de2b2acfe7a9230a                         |                                                              |
| value             | VARCHAR   | 956215560392395657740199                                           |                                                              |

## 56. Table: V2\_WeightedPool\_event\_PausedStateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| paused            | VARCHAR   |                                                              |             |

## 57. Table: V2\_WeightedPool\_event\_SwapFeePercentageChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 11:26:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36738186                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfca2a95294931789bb8b63620894e31eb1b256ec37e5e96484c2c5e11b5abc08 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 359                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe81de84008853f6d100a27d456a46e5fda0f1efb                         | Address of the contract that produced the log                |
| swapFeePercentage | VARCHAR   | 1000000000000000                                                   |                                                              |

## 58. Table: V2\_WeightedPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-22 13:26:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26228384                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x91ecb7d1c3356cc51f0a4a067bbb4dbcbe2ac1ed4c303e88928004c2afd0dd3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0297e37f1873d2dab4487aa67cd56b58e2f27875                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x751d37902d0bba8dfce5fd97e1ab99a21fa36c1b                         |                                                              |
| value             | VARCHAR   | 5631420336327656030                                                |                                                              |
