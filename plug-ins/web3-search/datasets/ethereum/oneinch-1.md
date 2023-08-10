# oneinch

## 1. Table: AggregationRouterV3\_event\_Error\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-13 20:46:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12821013                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6cdd20de19ad2d5ee21b37cb091638817d02572d565975e7dcc0cac4db88c9be | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                         | Address of the contract that produced the log                |
| reason            | VARCHAR   | Swap failed: Error(Return amount is not enough)                    |                                                              |

## 2. Table: AggregationRouterV3\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-14 20:31:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12038871                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x171d916add942fb0e4ae8618c4105b6368ad897e123e9c92dac6f87807e6552d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xee4f7b6c39e7e87af01fb9e4cee0c893ff4d63f2                         |                                                              |
| newOwner          | VARCHAR   | 0x5e89f8d81c74e311458277ea1be3d3247c7cd7d1                         |                                                              |

## 3. Table: AggregationRouterV3\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-05 17:59:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17629321                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x915f4c2bf057ebbd21c63f47ce399b1ecdcb3d51bbfe7eeed7a7a9a11702ddde | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc8bfc3f7b676719ba57d27b58814865aed24b15d                         |                                                              |
| srcToken          | VARCHAR   | 0x383518188c0c6d7730d91b2c03a03c837814a899                         |                                                              |
| dstToken          | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dstReceiver       | VARCHAR   | 0xc8bfc3f7b676719ba57d27b58814865aed24b15d                         |                                                              |
| spentAmount       | VARCHAR   | 8750817234                                                         |                                                              |
| returnAmount      | VARCHAR   | 265022338131451090                                                 |                                                              |

## 4. Table: MerkleDistributor\_event\_Claimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-17 23:45:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13438466                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdd3c2016b43389b2a1395f5c81fbfffecdbbb9bafc2426937f08f530e3642a7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 213                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe295ad71242373c37c5fda7b57f26f9ea1088afe                         | Address of the contract that produced the log                |
| index             | VARCHAR   | 26789                                                              |                                                              |
| account           | VARCHAR   | 0x7c1add10d5a9781ba6d974b6fbc142bb8a8fcd10                         |                                                              |
| amount            | VARCHAR   | 653840777788065256383                                              |                                                              |

## 5. Table: OneInchExchange\_event\_History\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-02 16:08:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9987765                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x54f278c6eb87a43c92e3ad5b79f5c4d5923009871303d1094cb916aa1a7f8e2c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11111254369792b2ca5d084ab5eea397ca8fa48b                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x09e80bde912794fdbea1e5b68b0c37a346b73cfc                         |                                                              |
| fromToken         | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         |                                                              |
| toToken           | VARCHAR   | 0x77f973fcaf871459aa58cd81881ce453759281bc                         |                                                              |
| fromAmount        | VARCHAR   | 4997023568                                                         |                                                              |
| toAmount          | VARCHAR   | 971588218757950947                                                 |                                                              |

## 6. Table: OneInchExchange\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-28 16:33:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8638375                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x203aa4b734ed86b568e036101f36ed25174847ad4839c7e7368540f58e547af8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11111254369792b2ca5d084ab5eea397ca8fa48b                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x5fe3b8b19949c04da3f578c6468f3d444cd7a9bb                         |                                                              |

## 7. Table: OneInchExchange\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-10 05:30:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11025803                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2eb5ce29d9ca3988d9fe2ba5dff347ba4b7ddce234dc1b2f831340b20d1f8480 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11111254369792b2ca5d084ab5eea397ca8fa48b                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0x19810559df63f19cfe88923313250550edadb743                         |                                                              |
| toToken           | VARCHAR   | 0x1cbb83ebcd552d5ebf8131ef8c9cd9d9bab342bc                         |                                                              |
| referrer          | VARCHAR   | 0xe56148e96a5ca25df0ce31e6f6bbd3a0e9814efc                         |                                                              |
| fromAmount        | VARCHAR   | 4                                                                  |                                                              |
| toAmount          | VARCHAR   | 2241793470343220567                                                |                                                              |
| referrerFee       | VARCHAR   | 0                                                                  |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |

## 8. Table: OneInchExchange\_v2\_event\_Error\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-08 12:37:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11997899                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xadec9686a7ead53e8db4309fba6b8782285a84799552e87d0bb65780f7fbf625 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x111111125434b319222cdbf8c261674adb56f3ae                         | Address of the contract that produced the log                |
| reason            | VARCHAR   | Swap failed: Error(Return amount is not enough)                    |                                                              |

## 9. Table: OneInchExchange\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-04 13:00:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11190804                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf6b3fa703e6a960ca456cdc3f772af30de873cf9e7e606758808dc77834585f1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x111111125434b319222cdbf8c261674adb56f3ae                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x122950753fffde2601901aa11a8c331bb7399d37                         |                                                              |
| newOwner          | VARCHAR   | 0x68a17b587caf4f9329f0e372e3a78d23a46de6b5                         |                                                              |

## 10. Table: OneInchExchange\_v2\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 11. Table: OneInchExchange\_v2\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-13 01:00:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11246218                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf94826510193af624fc346fa59889b34a807d77cb4800eaf7148cd260a1eeba1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x111111125434b319222cdbf8c261674adb56f3ae                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x01e6fd0ae73d9194b19f9b376065577927a0d5f5                         |                                                              |
| srcToken          | VARCHAR   | 0x178c820f862b14f316509ec36b13123da19a6054                         |                                                              |
| dstToken          | VARCHAR   | 0x1c5db575e2ff833e46a2e9864c22f4b22e0b37c2                         |                                                              |
| dstReceiver       | VARCHAR   | 0x01e6fd0ae73d9194b19f9b376065577927a0d5f5                         |                                                              |
| amount            | VARCHAR   | 26837929885927437587                                               |                                                              |
| spentAmount       | VARCHAR   | 26837929885927437587                                               |                                                              |
| returnAmount      | VARCHAR   | 333906151                                                          |                                                              |
| minReturnAmount   | VARCHAR   | 323888966                                                          |                                                              |
| guaranteedAmount  | VARCHAR   | 333906151                                                          |                                                              |
| referrer          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 12. Table: OneInchExchange\_v2\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |
