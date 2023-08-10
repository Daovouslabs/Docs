# linea

## 1. Table: ZkEvmV2\_call\_claimMessage\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-04 12:20:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17841580                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x29d778b9b8bf50fd896d82ac1467d31a23f76208497b4db26158d26d4b0b6201 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 257                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_from             | VARCHAR   | 0xaa967ac0d45cd4484ebe285a4126e0694ed54093                         |                                                                                                                        |
| \_to               | VARCHAR   | 0xaa967ac0d45cd4484ebe285a4126e0694ed54093                         |                                                                                                                        |
| \_fee              | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_value            | VARCHAR   | 102000000000000                                                    |                                                                                                                        |
| \_feeRecipient     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                                                                                        |
| \_calldata         | VARCHAR   | 0x                                                                 |                                                                                                                        |
| \_nonce            | VARCHAR   | 6408                                                               |                                                                                                                        |

## 2. Table: ZkEvmV2\_call\_sendMessage\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-05 07:31:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17847297                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6539550893623bfdbd77f65097dabb70919f3690d5463bf11f4a4d1bd8444f3a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 110                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_to               | VARCHAR   | 0x18480a75f76bb1968a9ef28b809fab2ca9c2d154                         |                                                                                                                        |
| \_fee              | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_calldata         | VARCHAR   | 0x                                                                 |                                                                                                                        |

## 3. Table: ZkEvmV2\_event\_AmountUsedInPeriodReset\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| resettingAddress  | VARCHAR   |                                                              |             |

## 4. Table: ZkEvmV2\_event\_BlockFinalized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-26 08:41:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17776128                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x36c21e6a93325cb0bde288c5a61285dc036de73633ba154115a8fd73c88ef1e5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| blockNumber       | VARCHAR   | 26680                                                              |                                                              |
| stateRootHash     | VARCHAR   | 0x259622013d6166fa9ece2699f7552d1954517b90479a0ac087eb11c1f000c703 |                                                              |

## 5. Table: ZkEvmV2\_event\_BlocksVerificationDone\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-07-22 09:21:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17747742                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xc03e2881a6ba5755959c925b144a9f07db00199a20369b44826eb5375c15e3d4 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| lastBlockFinalized | VARCHAR   | 5423                                                               |                                                              |
| startingRootHash   | VARCHAR   | 0x29115ddb5acd27a12c2f434d95a531b1812ea8fd01930b4407bb9e51c3e452f6 |                                                              |
| finalRootHash      | VARCHAR   | 0x1b8368ae6602d6f4633a7d964c3b77b0c40b12e05603df8077c7ccad669ffb32 |                                                              |

## 6. Table: ZkEvmV2\_event\_Initialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-12 11:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17677070                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3564f15a274bdc49a6ad8af161113d20a678d87efbd3d708540a9b4d026f1122 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| version           | VARCHAR   | 1                                                                  |                                                              |

## 7. Table: ZkEvmV2\_event\_L1L2MessagesReceivedOnL2\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-29 21:47:11+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17801472                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3d5d226cd87bf0047c8f5b304d823eaef2e0d052f7e4fae47b28505f7d6228c1                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                                                           | Address of the contract that produced the log                |
| messageHashes     | VARCHAR   | 0x02f5026d115d1bbf923018be6d3f59d9bf099c5b979a3e92f38311a7affa393d,0xf06e89271f0171f13bb38273bdfa8c1 |                                                              |

## 8. Table: ZkEvmV2\_event\_L2L1MessageHashAddedToInbox\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 20:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17743948                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec9991f2be4556e117292141412752d24a032c15b2832799e108e45b3e3ccb53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| messageHash       | VARCHAR   | 0x6675030e944844da9f424c35e467834e09c9863abaa488b82c4f3610f6b1e53e |                                                              |

## 9. Table: ZkEvmV2\_event\_LimitAmountChanged\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2023-07-24 08:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 17761640                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x86f92ceaafba1ca052474433638289f6a9666e0598fa34e329b84a9a3fba6ea1 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| amountChangeBy           | VARCHAR   | 0x892bb7eed71efb060ab90140e7825d8127991dd3                         |                                                              |
| amount                   | VARCHAR   | 400000000000000000000                                              |                                                              |
| amountUsedLoweredToLimit | VARCHAR   | false                                                              |                                                              |
| usedAmountResetToZero    | VARCHAR   | false                                                              |                                                              |

## 10. Table: ZkEvmV2\_event\_MessageClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 05:05:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17746472                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e0e61001207e3aa92d37316e178e4ee5759808ba16d5dc8cdaeae6d1f86ebf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| \_messageHash     | VARCHAR   | 0x363b039baf83004066eb73cc37eefe7e2dc74263897c0064e2edac62748e757e |                                                              |

## 11. Table: ZkEvmV2\_event\_MessageSent\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-29 05:12:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17796532                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e5ec72daeba71bc85dfc7388dde29c9261a7f8daf9460098d7e497bb831d281 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0b4e2bc9a1e8578d88e7a1b73ebc1f62c1f405ac                         |                                                              |
| \_to              | VARCHAR   | 0x0b4e2bc9a1e8578d88e7a1b73ebc1f62c1f405ac                         |                                                              |
| \_fee             | VARCHAR   | 0                                                                  |                                                              |
| \_value           | VARCHAR   | 2010000000000000                                                   |                                                              |
| \_nonce           | VARCHAR   | 91542                                                              |                                                              |
| \_calldata        | VARCHAR   | 0x                                                                 |                                                              |
| \_messageHash     | VARCHAR   | 0x894bdd54aa088cf71cc336e170a334d442406c8e51594bbbeb4673c68ffa1a56 |                                                              |

## 12. Table: ZkEvmV2\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-14 18:31:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17693496                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x555810d27e838df783b1236e04991fa667308402a50b274d73485b21b1e870bf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 267                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| messageSender     | VARCHAR   | 0x892bb7eed71efb060ab90140e7825d8127991dd3                         |                                                              |
| pauseType         | VARCHAR   | 0x06193bb948d6b7a6fcbe51c193ccf2183bb5d979b6ae5d3a6971b8851461d3b0 |                                                              |

## 13. Table: ZkEvmV2\_event\_RoleAdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| previousAdminRole | VARCHAR   |                                                              |             |
| newAdminRole      | VARCHAR   |                                                              |             |

## 14. Table: ZkEvmV2\_event\_RoleGranted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-12 11:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17677070                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3564f15a274bdc49a6ad8af161113d20a678d87efbd3d708540a9b4d026f1122 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x356a809dfdea9198dd76fb76bf6d403ecf13ea675eb89e1eda2db2c4a4676a26 |                                                              |
| account           | VARCHAR   | 0x892bb7eed71efb060ab90140e7825d8127991dd3                         |                                                              |
| sender            | VARCHAR   | 0x6dd3120e329dc5faa3d2cf65705ef4f6486f65f7                         |                                                              |

## 15. Table: ZkEvmV2\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |
| sender            | VARCHAR   |                                                              |             |

## 16. Table: ZkEvmV2\_event\_UnPaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-15 13:43:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17699154                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02ff740e3afe631e7329574dd367aaca22ae4eb537db303f13a9b2c30e0eaea3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| messageSender     | VARCHAR   | 0x892bb7eed71efb060ab90140e7825d8127991dd3                         |                                                              |
| pauseType         | VARCHAR   | 0x06193bb948d6b7a6fcbe51c193ccf2183bb5d979b6ae5d3a6971b8851461d3b0 |                                                              |

## 17. Table: ZkEvmV2\_event\_VerifierAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-12 11:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17677323                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc95cd5fbeefd46a279bf173d3f3533e9245165a9aef2b7c033286cdf84e8cf84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd19d4b5d358258f05d7b411e21a1460d11b0876f                         | Address of the contract that produced the log                |
| verifierAddress   | VARCHAR   | 0xa4f1155202d36348097b7488b0d2365fa91f8cac                         |                                                              |
| proofType         | VARCHAR   | 1                                                                  |                                                              |
| verifierSetBy     | VARCHAR   | 0x892bb7eed71efb060ab90140e7825d8127991dd3                         |                                                              |
