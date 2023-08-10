# qdao

## 1. Table: QDAO\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-26 14:07:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8426289                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2c0ee3c81c226659b6bd9aaaa246f231d679cf9ad9ecc59352f2519ac8e49893 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xdea43b1487c6689fe815b7d8394f6f7a7f8479c7                         |                                                              |
| spender           | VARCHAR   | 0x2a0c0dbecc7e4d658f48e01e3fa353f44050c208                         |                                                              |
| value             | VARCHAR   | 300000000000000000                                                 |                                                              |

## 2. Table: QDAO\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-02 08:24:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11176538                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac945d82bed1f8229903ae135249fa0f47cc2a698aa286f4c1b90e3c05dbc3db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0x71e0d074bb70fdc5345f986e3435117f52afcebb                         |                                                              |
| value             | VARCHAR   | 3000000000000000000                                                |                                                              |

## 3. Table: QDAO\_event\_GovernanceContractAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-10 10:16:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8322296                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17afd8a3afbb4f8db066a7236a2fc59f43c5bbdd541c5adff1ae6e237f65b0f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0xe0a4a032102f11a7983207201f38925e157a2ac9                         |                                                              |

## 4. Table: QDAO\_event\_GovernanceContractRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-10 10:10:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8322283                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x99888bb244d568e8652f29dc5a3b0e329b78644b79bba7bfed71c6ef40558d25 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0xd9adad001475114c050ff4cb5beaeddcf1ce803e                         |                                                              |

## 5. Table: QDAO\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-09 17:01:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8317626                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdff8262f5f3e3fc44adad78b14ac5c8a2b79e8022e1539574102cb25f933b403 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x5a6a52a7bf22813882e988135a7d2be805bb0649                         |                                                              |
| amount            | VARCHAR   | 22431564000000000000000                                            |                                                              |

## 6. Table: QDAO\_event\_OperationCancelled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| operation         | VARCHAR   |                                                              |             |
| lastCanceller     | VARCHAR   |                                                              |             |

## 7. Table: QDAO\_event\_OperationCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-10 09:56:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8322218                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b41253b925449268b2cbac0a43da17ddc07c2d80606fecfeb8701e38ba7dde7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 30                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| operation         | VARCHAR   | 0xe28468a8da92d70ea1d785fd5cfef534b9c14147cde8e45efcf42fb67a046cba |                                                              |
| howMany           | VARCHAR   | 4                                                                  |                                                              |
| ownersCount       | VARCHAR   | 6                                                                  |                                                              |
| proposer          | VARCHAR   | 0x168630128e92967e37fbb835e91d217426063f72                         |                                                              |

## 8. Table: QDAO\_event\_OperationDownvoted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| operation         | VARCHAR   |                                                              |             |
| votes             | VARCHAR   |                                                              |             |
| ownersCount       | VARCHAR   |                                                              |             |
| downvoter         | VARCHAR   |                                                              |             |

## 9. Table: QDAO\_event\_OperationPerformed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-01 12:08:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11952239                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x754216cc5d0a9de49c63327a10693563afa921baefa48a50c170b8605ec7a830 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| operation         | VARCHAR   | 0x11dfb98a3cd748e609518b55ab5efed61481c73e43b8ff8903d02d9eb77ec0b7 |                                                              |
| howMany           | VARCHAR   | 4                                                                  |                                                              |
| ownersCount       | VARCHAR   | 6                                                                  |                                                              |
| performer         | VARCHAR   | 0x0230c3b379a4948008d9fd78f4b3482e883fee2c                         |                                                              |

## 10. Table: QDAO\_event\_OperationUpvoted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-01 12:01:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11952207                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x345fe2b19ff47058379919e81c401a877688a0d890102e696a59d2fd42406a0f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 356                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| operation         | VARCHAR   | 0x11dfb98a3cd748e609518b55ab5efed61481c73e43b8ff8903d02d9eb77ec0b7 |                                                              |
| votes             | VARCHAR   | 1                                                                  |                                                              |
| howMany           | VARCHAR   | 4                                                                  |                                                              |
| ownersCount       | VARCHAR   | 6                                                                  |                                                              |
| upvoter           | VARCHAR   | 0x623534d7cd1bda347790fab7c668309a7e2ad141                         |                                                              |

## 11. Table: QDAO\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 12. Table: QDAO\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-04 13:26:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7893118                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b19147eb3c0cf330c80f1c51194bb01e6287068b671f327d6eb5951b533e559 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x7f5c5d68c03952837c1265f7b23c68804bfd20b4                         |                                                              |
| newOwner          | VARCHAR   | 0x0230c3b379a4948008d9fd78f4b3482e883fee2c                         |                                                              |

## 13. Table: QDAO\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 14. Table: QDAO\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-23 08:56:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8795752                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x653d892f12d717b7bfac05b134e3c2dd394d0ee2f4da7faaccc928af0b2bbdc3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3166c570935a7d8554c8f4ea792ff965d2efe1f2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xde8c92f001099f9aa1d0866eeb3271e7e156df1a                         |                                                              |
| to                | VARCHAR   | 0x2eacf64590a71142308910e31bc0e3baffca9c17                         |                                                              |
| value             | VARCHAR   | 100000000000000000                                                 |                                                              |

## 15. Table: QDAO\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
