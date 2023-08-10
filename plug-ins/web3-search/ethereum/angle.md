# angle

## 1. Table: AngleRouter\_call\_addStableMaster\_history

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
| stablecoin         | VARCHAR   |                                                                                                                        |             |
| stableMaster       | VARCHAR   |                                                                                                                        |             |

## 2. Table: AngleRouter\_call\_burn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-07-12 03:36:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15125473                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xecee81a6776dfa8ad77b8f68a1c34321df60f603f5ec5395c62c18048135d385 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 18                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 18                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xbb755240596530be0c1de5dfd77ec6398471561d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| dest               | VARCHAR   | 0x42189f909e1efa409a4509070ddbc31a592422a8                         |                                                                                                                        |
| amount             | VARCHAR   | 103262344319868438786                                              |                                                                                                                        |
| minCollatAmount    | VARCHAR   | 0                                                                  |                                                                                                                        |
| stablecoin         | VARCHAR   | 0x1a7e4e63778b4f12a199c062f3efdd288afcbce8                         |                                                                                                                        |
| collateral         | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                                                                                        |

## 3. Table: AngleRouter\_call\_claimRewards\_history

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
| gaugeUser          | VARCHAR   |                                                                                                                        |             |
| liquidityGauges    | VARCHAR   |                                                                                                                        |             |
| perpetualIDs       | VARCHAR   |                                                                                                                        |             |
| stablecoins        | VARCHAR   |                                                                                                                        |             |
| collaterals        | VARCHAR   |                                                                                                                        |             |

## 4. Table: AngleRouter\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-30 04:55:52+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15048681                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xcc8f80b50a3c634ba12495753a18991c1511bb276ebc91964c616125d2853aae | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 270                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 24                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xbb755240596530be0c1de5dfd77ec6398471561d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| user               | VARCHAR   | 0x42189f909e1efa409a4509070ddbc31a592422a8                         |                                                                                                                        |
| amount             | VARCHAR   | 1154989360                                                         |                                                                                                                        |
| minStableAmount    | VARCHAR   | 0                                                                  |                                                                                                                        |
| stablecoin         | VARCHAR   | 0x1a7e4e63778b4f12a199c062f3efdd288afcbce8                         |                                                                                                                        |
| collateral         | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                                                                                        |

## 5. Table: AngleRouter\_call\_mixer\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-12 01:44:05+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15518216                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x23674572a7e08202ce1bb7786d8fb70335235357501512a1f84bf7b30c74266f                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 278                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xbb755240596530be0c1de5dfd77ec6398471561d                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| paramsPermit       | VARCHAR   |                                                                                                      |                                                                                                                        |
| paramsTransfer     | VARCHAR   | 0x853d955aCEf822Db058eb8505911ED77F175b99e,107000000000000000000                                     |                                                                                                                        |
| paramsSwap         | VARCHAR   |                                                                                                      |                                                                                                                        |
| actions            | VARCHAR   | 6                                                                                                    |                                                                                                                        |
| data               | VARCHAR   | 0x000000000000000000000000f6a10e74ca923ffc9900105c084d0cd2fd6c90d70000000000000000000000000000000000 |                                                                                                                        |

## 6. Table: AngleRouter\_call\_removePairs\_history

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
| stablecoins        | VARCHAR   |                                                                                                                        |             |
| collaterals        | VARCHAR   |                                                                                                                        |             |
| stableMasters      | VARCHAR   |                                                                                                                        |             |

## 7. Table: AngleRouter\_call\_removeStableMaster\_history

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
| stablecoin         | VARCHAR   |                                                                                                                        |             |

## 8. Table: AngleRouter\_call\_setLiquidityGauges\_history

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
| stablecoins        | VARCHAR   |                                                                                                                        |             |
| collaterals        | VARCHAR   |                                                                                                                        |             |
| newLiquidityGauges | VARCHAR   |                                                                                                                        |             |

## 9. Table: AngleRouter\_event\_CollateralToggled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-28 08:28:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14671807                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c29472230b86e40c95cc9556535bf5eae8efc8b615dad1b08dea62ea5e1c1ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbb755240596530be0c1de5dfd77ec6398471561d                         | Address of the contract that produced the log                |
| stableMaster      | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         |                                                              |
| poolManager       | VARCHAR   | 0x3f66867b4b6eceba0dbb6776be15619f73bc30a2                         |                                                              |
| liquidityGauge    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 10. Table: AngleRouter\_event\_Recovered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tokenAddress      | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 11. Table: AngleRouter\_event\_StablecoinAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| stableMaster      | VARCHAR   |                                                              |             |

## 12. Table: AngleRouter\_event\_StablecoinRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| stableMaster      | VARCHAR   |                                                              |             |

## 13. Table: PerpetualManagerFront\_call\_addToPerpetual\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-19 12:19:56+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14236466                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x16a8dfcea9a1b21acbad195f0821e5a6ea0d4fe5897c65847cf8d419a9fda2de | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 225                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5efe48f8383921d950683c46b87e28e21dea9fb5                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| perpetualID        | VARCHAR   | 153                                                                |                                                                                                                        |
| amount             | VARCHAR   | 2348000000                                                         |                                                                                                                        |

## 14. Table: PerpetualManagerFront\_call\_closePerpetual\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-17 11:28:29+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14022772                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1502a50eba03e2abc31d32d2321c94ab7bc7b8695d02f3a660cb05c26dda15a9 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 80                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5efe48f8383921d950683c46b87e28e21dea9fb5                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| perpetualID        | VARCHAR   | 78                                                                 |                                                                                                                        |
| to                 | VARCHAR   | 0x110ba807550eb898ce84330bec7ce8ede4dfb50e                         |                                                                                                                        |
| minCashOutAmount   | VARCHAR   | 0                                                                  |                                                                                                                        |

## 15. Table: PerpetualManagerFront\_call\_forceClosePerpetuals\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-21 05:00:50+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14046953                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x284e0e25ee9d2b3319c943d7df5544b8d6747777dc0310c481efd7d7157951d6 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 178                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x4121a258674e507c990cdf390f74d4ef27592114                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| perpetualIDs       | VARCHAR   | 31,36,37,26,35,28,43                                               |                                                                                                                        |

## 16. Table: PerpetualManagerFront\_call\_liquidatePerpetuals\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-31 17:23:39+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13914428                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf4d0a0f9de5d41d705199b16f43ac571b117b7f797802afedb30e3b5ace39b95 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 5                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2,0                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5efe48f8383921d950683c46b87e28e21dea9fb5                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| perpetualIDs       | VARCHAR   | 65                                                                 |                                                                                                                        |

## 17. Table: PerpetualManagerFront\_call\_openPerpetual\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-12 08:04:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13789112                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5c8f2176b8402d1962bca58989f6cf2ffe7b733c0c1f5c6a89f6be8ffb6e0067 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 243                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5efe48f8383921d950683c46b87e28e21dea9fb5                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| owner              | VARCHAR   | 0x41c247e7148a68b2853ad4cad9fc05f0e0d7e9ef                         |                                                                                                                        |
| margin             | VARCHAR   | 1000000000                                                         |                                                                                                                        |
| committedAmount    | VARCHAR   | 20761051014                                                        |                                                                                                                        |
| maxOracleRate      | VARCHAR   | 888063367960440973                                                 |                                                                                                                        |
| minNetMargin       | VARCHAR   | 933028263                                                          |                                                                                                                        |

## 18. Table: PerpetualManagerFront\_call\_removeFromPerpetual\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-06 18:54:45+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13953619                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6ad42554e254d52835eee11470430b304711b56b19d1b45f423622aa90d08c9e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 260                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5efe48f8383921d950683c46b87e28e21dea9fb5                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| perpetualID        | VARCHAR   | 75                                                                 |                                                                                                                        |
| amount             | VARCHAR   | 1                                                                  |                                                                                                                        |
| to                 | VARCHAR   | 0x7e65eaae216650c1198321564cf953b39f7e5720                         |                                                                                                                        |

## 19. Table: PerpetualManagerFront\_event\_HAFeesUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-11 08:55:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13983233                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x357459e1e8f82a6df46a799b5c12c2b1680b5b90fef016ad2ab20e91dee69b8b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5efe48f8383921d950683c46b87e28e21dea9fb5                         | Address of the contract that produced the log                |
| \_xHAFees         | VARCHAR   | 0,800000000,1000000000                                             |                                                              |
| \_yHAFees         | VARCHAR   | 1500000,2000000,2500000                                            |                                                              |
| deposit           | VARCHAR   | 1                                                                  |                                                              |

## 20. Table: PerpetualManagerFront\_event\_KeeperTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-18 10:26:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15166046                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xad80ff08c22e14ea074c926cc642608c39bcf10b22e51a08440461aa7d9e9a90 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5efe48f8383921d950683c46b87e28e21dea9fb5                         | Address of the contract that produced the log                |
| keeperAddress     | VARCHAR   | 0xcc617c6f9725eacc993ac626c7efc6b96476916e                         |                                                              |
| liquidationFees   | VARCHAR   | 318823836                                                          |                                                              |

## 21. Table: PerpetualManagerFront\_event\_PerpetualClosed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-01 15:51:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14121009                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd93de1019fdf13f8f91ce8d95c979d920fec7f24fb73678f97beb7d2be879412 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4121a258674e507c990cdf390f74d4ef27592114                         | Address of the contract that produced the log                |
| \_perpetualID     | VARCHAR   | 64                                                                 |                                                              |
| \_closeAmount     | VARCHAR   | 9971660314442458749855                                             |                                                              |

## 22. Table: PerpetualManagerFront\_event\_PerpetualOpened\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-22 22:24:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13667148                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3cac6b9b5cf7561a0b38dfe786e592fb4f7c076e2bc9633b9c6dc6490abb59c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfc8f9eefc5fce1d9dace2b0a11a1e184381787c4                         | Address of the contract that produced the log                |
| \_perpetualID     | VARCHAR   | 44                                                                 |                                                              |
| \_entryRate       | VARCHAR   | 890022873519228886                                                 |                                                              |
| \_margin          | VARCHAR   | 59687369460194141111                                               |                                                              |
| \_committedAmount | VARCHAR   | 577176862680077351824                                              |                                                              |

## 23. Table: PerpetualManagerFront\_event\_PerpetualUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-10 17:23:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13589782                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5b6371320966f795391eb761157abcd21adbd234728f111dd1e4881c70d441e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5efe48f8383921d950683c46b87e28e21dea9fb5                         | Address of the contract that produced the log                |
| \_perpetualID     | VARCHAR   | 31                                                                 |                                                              |
| \_margin          | VARCHAR   | 8500000050                                                         |                                                              |

## 24. Table: PerpetualManagerFront\_event\_PerpetualsForceClosed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-26 04:51:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14846049                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb019786b6f0c669730e7c38df5c614e8c7d635df5ac9f81191938e344848f32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfc8f9eefc5fce1d9dace2b0a11a1e184381787c4                         | Address of the contract that produced the log                |
| perpetualIDs      | VARCHAR   | 9                                                                  |                                                              |
| ownerAndCashOut   | VARCHAR   | 0xEC0c666ACd059E2bBf5DD055f1a282bF0EBf16FC,43257904805670964745813 |                                                              |
| keeper            | VARCHAR   | 0xcc617c6f9725eacc993ac626c7efc6b96476916e                         |                                                              |
| reward            | VARCHAR   | 0                                                                  |                                                              |

## 25. Table: PerpetualManagerFront\_event\_Recovered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tokenAddress      | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 26. Table: PerpetualManagerFront\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-01 16:20:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13722073                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4bb9a4a6ff09154dfd136d2a55865816ebc2567823ebc5c5f99799d021d20fcc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfc8f9eefc5fce1d9dace2b0a11a1e184381787c4                         | Address of the contract that produced the log                |
| \_reward          | VARCHAR   | 44931938112616438356164                                            |                                                              |

## 27. Table: PerpetualManagerFront\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-25 03:24:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14651429                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82e08540bd90e707daa56bae73d02e2cfd5885682223b43ab7a1a6c6fe89a6f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 297                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x98fdbc5497599eff830923ea1ee152adb9a4cea5                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0xba51f16c2a835a95937a29c522a999fe5fed62b6                         |                                                              |
| \_reward          | VARCHAR   | 13395244441601339536071                                            |                                                              |

## 28. Table: PerpetualManagerFront\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 09:12:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15307138                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5b8be026ab0f4e2cd320238828585bf7deccbbe96bd1eecde0ec88d7df1e005 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 506                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4121a258674e507c990cdf390f74d4ef27592114                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x4ec7f4bbc09d76b3e06a80c065fa3206e4a085c7                         |                                                              |
| tokenId           | VARCHAR   | 87                                                                 |                                                              |

## 29. Table: StableMasterFront\_call\_StocksUsersUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-15 09:59:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15146582                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c48ab5d6cd5e87510b5d89bcf661cb389109e9ad631863322141a1e42508493 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 313                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the contract that produced the log                |
| \_poolManager     | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         |                                                              |
| \_stocksUsers     | VARCHAR   | 0                                                                  |                                                              |

## 30. Table: StableMasterFront\_call\_accumulateInterest\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-25 03:48:19+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14453098                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf2cbc0a960eb0b7fdfa5281cb1b8225c2f25c2d302cf168dd24c84a2ad487316 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 132                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 11,0,3                                                             | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| gain               | VARCHAR   | 19701677876                                                        |                                                                                                                        |

## 31. Table: StableMasterFront\_call\_burn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-28 16:28:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15633033                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2e55118b3cd241cda7ae5df2496c06000dd3cbfeec6962446ead3464ec371464 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 32                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2,0                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 62266852178078523064686                                            |                                                                                                                        |
| burner             | VARCHAR   | 0x3b654e30633d44b05847aaf65cf1ad0c92bed248                         |                                                                                                                        |
| dest               | VARCHAR   | 0x3b654e30633d44b05847aaf65cf1ad0c92bed248                         |                                                                                                                        |
| poolManager        | VARCHAR   | 0xe9f183fc656656f1f17af1f2b0df79b8ff9ad8ed                         |                                                                                                                        |
| minCollatAmount    | VARCHAR   | 0                                                                  |                                                                                                                        |

## 32. Table: StableMasterFront\_call\_deployCollateral\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-10-23 10:38:52+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13473264                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9c946303bb534f30d6210f61ad9062a5d177dd09a1e0623c1bc7b97afdb87b50 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 99                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| poolManager        | VARCHAR   | 0xc9daabc677f3d1301006e723bd21c60be57a5915                         |                                                                                                                        |
| perpetualManager   | VARCHAR   | 0xfc8f9eefc5fce1d9dace2b0a11a1e184381787c4                         |                                                                                                                        |
| feeManager         | VARCHAR   | 0xe6d9bd6796bdaf9b391fac2a2d34bae9c1c3c1c4                         |                                                                                                                        |
| oracle             | VARCHAR   | 0x7ab641e661a9728913a44e06f6a4879481142ddb                         |                                                                                                                        |
| sanToken           | VARCHAR   | 0x7b8e89b0ce7bac2cfec92a371da899ea8cbdb450                         |                                                                                                                        |

## 33. Table: StableMasterFront\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-22 07:18:51+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13853581                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1a9d6359e3a8e34a11f4236d4579d2c7bd163619f8b6d72279e739d8192e50d2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 328                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 449678216110151111754865                                           |                                                                                                                        |
| user               | VARCHAR   | 0x854f1269b659a727a2268ab86ff77cfb30bfb358                         |                                                                                                                        |
| poolManager        | VARCHAR   | 0x6b4ee7352406707003bc6f6b96595fd35925af48                         |                                                                                                                        |

## 34. Table: StableMasterFront\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-23 11:56:14+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14829437                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x60f734ae13d027ba1185108664c861820e5c188a84b45c9e6d74632395965da7 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 140                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| user               | VARCHAR   | 0x10d98b4809efe5e3a4269afe6f5f4388ce4c38f1                         |                                                                                                                        |
| poolManager        | VARCHAR   | 0x3f66867b4b6eceba0dbb6776be15619f73bc30a2                         |                                                                                                                        |
| minStableAmount    | VARCHAR   | 1887461745813876058722                                             |                                                                                                                        |

## 35. Table: StableMasterFront\_call\_revokeCollateral\_history

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
| poolManager        | VARCHAR   |                                                                                                                        |             |
| settlementContract | VARCHAR   |                                                                                                                        |             |

## 36. Table: StableMasterFront\_call\_setUserFees\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-12 13:29:28+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14761334                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7ea8ec9f2ea945d447818928e4f4f097ebd907163772b8e75362a150cae79f2a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 60                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| poolManager        | VARCHAR   | 0x6b4ee7352406707003bc6f6b96595fd35925af48                         |                                                                                                                        |
| \_xFee             | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_yFee             | VARCHAR   | 15000000                                                           |                                                                                                                        |
| \_mint             | VARCHAR   | 1                                                                  |                                                                                                                        |

## 37. Table: StableMasterFront\_call\_signalLoss\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-13 08:32:50+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14576106                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc7ca97520272cee282a971b8b1734b3140ff5ecf0c84007fa085f984b949dfb5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 44                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,11,0,3                                                           | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| loss               | VARCHAR   | 1834572345                                                         |                                                                                                                        |

## 38. Table: StableMasterFront\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-12 09:25:41+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14569911                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6096f93f65fb1c9fa05e21ca5dd4708506eff9dcc6a52b061651e08f04399af0 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 101                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 25010000000                                                        |                                                                                                                        |
| burner             | VARCHAR   | 0xe629e1f7d250d39af4d704b486b094a4ba91ef3b                         |                                                                                                                        |
| dest               | VARCHAR   | 0xe629e1f7d250d39af4d704b486b094a4ba91ef3b                         |                                                                                                                        |
| poolManager        | VARCHAR   | 0xe9f183fc656656f1f17af1f2b0df79b8ff9ad8ed                         |                                                                                                                        |

## 39. Table: StableMasterFront\_event\_BurntStablecoins\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-28 09:20:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16067552                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x112298383dbe63f286ecf209433c0f5c8746baab222c8a6e8990d0f83ce71f52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the contract that produced the log                |
| \_poolManager     | VARCHAR   | 0xe9f183fc656656f1f17af1f2b0df79b8ff9ad8ed                         |                                                              |
| amount            | VARCHAR   | 201593873244688898455699                                           |                                                              |
| redeemInC         | VARCHAR   | 209690004504                                                       |                                                              |

## 40. Table: StableMasterFront\_event\_CollateralDeployed\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-10-23 10:38:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 13473264                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x9c946303bb534f30d6210f61ad9062a5d177dd09a1e0623c1bc7b97afdb87b50 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 168                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the contract that produced the log                |
| \_poolManager      | VARCHAR   | 0xc9daabc677f3d1301006e723bd21c60be57a5915                         |                                                              |
| \_perpetualManager | VARCHAR   | 0xfc8f9eefc5fce1d9dace2b0a11a1e184381787c4                         |                                                              |
| \_sanToken         | VARCHAR   | 0x7b8e89b0ce7bac2cfec92a371da899ea8cbdb450                         |                                                              |
| \_oracle           | VARCHAR   | 0x7ab641e661a9728913a44e06f6a4879481142ddb                         |                                                              |

## 41. Table: StableMasterFront\_event\_CollateralRevoked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_poolManager     | VARCHAR   |                                                              |             |

## 42. Table: StableMasterFront\_event\_MintedStablecoins\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2022-08-08 22:38:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 15304320                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xd08385334d0b57d3b35cd2d9e4aa3048d7c59064b52ae2a6842aa82f9f3b839f | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 263                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the contract that produced the log                |
| \_poolManager         | VARCHAR   | 0xe9f183fc656656f1f17af1f2b0df79b8ff9ad8ed                         |                                                              |
| amount                | VARCHAR   | 484372234                                                          |                                                              |
| amountForUserInStable | VARCHAR   | 474231638156359836125                                              |                                                              |

## 43. Table: StableMasterFront\_event\_SanRateUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-09 14:20:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14742892                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e835f0bc0bfa91190bda0fc9b3e1faac49c36c90b7af9277375b9e1e5a846e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the contract that produced the log                |
| \_token           | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         |                                                              |
| \_newSanRate      | VARCHAR   | 1008337823917242525                                                |                                                              |

## 44. Table: StableMasterFront\_event\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-29 09:41:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16074819                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8a769d24700aa38a88d3476ecba726515936d8d3bad863409412cbcd159689b5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 101                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5addc89785d75c86ab939e9e15bfbbb7fc086a87                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 98018432511040326684                                               |                                                                                                                        |
| burner             | VARCHAR   | 0x9ed3855e00c2816195458f770f80892395a2fa39                         |                                                                                                                        |
| dest               | VARCHAR   | 0x9ed3855e00c2816195458f770f80892395a2fa39                         |                                                                                                                        |
| poolManager        | VARCHAR   | 0x6b4ee7352406707003bc6f6b96595fd35925af48                         |                                                                                                                        |

## 45. Table: Treasury\_event\_Recovered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 46. Table: Treasury\_event\_VaultManagerToggled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-31 11:31:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16526522                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb79699c8693e8237924b1880e336c6a252376097e5b25216d55d24934549b3d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8667dbebf68b0bfa6db54f550f41be16c4067d60                         | Address of the contract that produced the log                |
| vaultManager      | VARCHAR   | 0xe1c084e6e2ec9d32ec098e102a73c4c27eb9ee58                         |                                                              |

## 47. Table: VaultManager\_call\_angle\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-29 19:44:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17800866                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5efc452b2da7c8da229c255f29273fa49ec369898c919508f001b10f382f7ddd                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 33                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0652b4b3d205300f9848f0431296d67ca4397f3b                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| actions            | VARCHAR   | 1                                                                                                    |                                                                                                                        |
| datas              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000006                                   |                                                                                                                        |
| from               | VARCHAR   | 0xdc7aa225964267c7e0efb35f4931426209e90312                                                           |                                                                                                                        |
| to                 | VARCHAR   | 0xe1a6d84604c5b17f5fd1fccba4c385a8b9670266                                                           |                                                                                                                        |
| who                | VARCHAR   | 0xe1a6d84604c5b17f5fd1fccba4c385a8b9670266                                                           |                                                                                                                        |
| repayData          | VARCHAR   | 0x000000000000000000000000dc7aa225964267c7e0efb35f4931426209e903120000000000000000000000000000000000 |                                                                                                                        |

## 48. Table: VaultManager\_event\_AccruedToTreasury\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-15 23:06:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16836447                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb3ab3cfa02aa0fff88334034cbe082ad7a7dfa32dd7abf9ae6a393f6034cd00 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 414                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe0c8b6c4ea301c8a221e8838ca5b80ac76e7a10b                         | Address of the contract that produced the log                |
| surplusEndValue   | VARCHAR   | 0                                                                  |                                                              |
| badDebtEndValue   | VARCHAR   | 0                                                                  |                                                              |

## 49. Table: VaultManager\_event\_CollateralAmountUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 08:44:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17541160                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x192cd3d496a32eb60d6149820f80e5649d885bb7469b1ae9e0173060bce6a627 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73aaf8694ba137a7537e7ef544fcf5e2475f227b                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 23                                                                 |                                                              |
| collateralAmount  | VARCHAR   | 5351111017882798340                                                |                                                              |
| isIncrease        | VARCHAR   | 1                                                                  |                                                              |

## 50. Table: VaultManager\_event\_DebtCeilingUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 15:59:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17443714                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x77c33e3d37806f85cbab5249477831966af17856cfd90fa6aec33a438f16e943 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x913e8e1ed659c27613e937a6b6119b91d985094c                         | Address of the contract that produced the log                |
| debtCeiling       | VARCHAR   | 500000000000000000000000                                           |                                                              |

## 51. Table: VaultManager\_event\_DebtTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-12 11:19:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16390382                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6381b7f0a79bc813bba207384196ba1ae486007be1c5d73e32561cf8271a767e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1bece8193f8dc2b170135da9f1fa8b81c7ad18b1                         | Address of the contract that produced the log                |
| srcVaultID        | VARCHAR   | 39                                                                 |                                                              |
| dstVaultID        | VARCHAR   | 2                                                                  |                                                              |
| dstVaultManager   | VARCHAR   | 0xdeee8e8a89338241fe622509414ff535fb02b479                         |                                                              |
| amount            | VARCHAR   | 10000000000000000000                                               |                                                              |

## 52. Table: VaultManager\_event\_InterestAccumulatorUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-05 09:20:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17413394                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6ada62a8b363016fc07d17af55949b871b5071c8f120293eafcde1f36f80bf7c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73aaf8694ba137a7537e7ef544fcf5e2475f227b                         | Address of the contract that produced the log                |
| value             | VARCHAR   | 1004863589639621619291545843                                       |                                                              |
| timestamp         | VARCHAR   | 1685956823                                                         |                                                              |

## 53. Table: VaultManager\_event\_InternalDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 23:56:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17837885                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe16e554a53486806b8b73f78e0094f53735eff48fc339d4d41742686be121202 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 265                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x96de5c30f2bf4683c7903f3e921f720602f8868a                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 2                                                                  |                                                              |
| internalAmount    | VARCHAR   | 119874249222536427123609                                           |                                                              |
| isIncrease        | VARCHAR   | 0                                                                  |                                                              |

## 54. Table: VaultManager\_event\_LiquidatedVaults\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-09 10:46:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15931969                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ee9b1aa80928815deb8c7d3f9747d9966aca66e45a355cbf62855825895c4ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x73aaf8694ba137a7537e7ef544fcf5e2475f227b                         | Address of the contract that produced the log                |
| vaultIDs          | VARCHAR   | 7                                                                  |                                                              |

## 55. Table: VaultManager\_event\_LiquidationBoostParametersUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_veBoostProxy    | VARCHAR   |                                                              |             |
| xBoost            | VARCHAR   |                                                              |             |
| yBoost            | VARCHAR   |                                                              |             |

## 56. Table: VaultManager\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-19 13:20:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17514053                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b2c03cdf84d2b1ac9dbe96cbdc70053c694df8aa8cccafe15921fc789168aee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 451                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ffc8a23eafc25635dae822ea9c4ff440226a001                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xfda462548ce04282f4b6d6619823a7c64fdc0185                         |                                                              |
| tokenId           | VARCHAR   | 1                                                                  |                                                              |

## 57. Table: agEUR\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-20 14:35:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15575319                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa7686bbc4346aa10defa79056562a55faeea2ae0bb89eee61c662b29c4758a81 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a7e4e63778b4f12a199c062f3efdd288afcbce8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x735a26a57a0a0069dfabd41595a970faf5e1ee8b                         |                                                              |
| to                | VARCHAR   | 0x6ac2c17b94b54643f000d1e33abe4d5bdbe34d1c                         |                                                              |
| value             | VARCHAR   | 52721603903557479565278                                            |                                                              |
