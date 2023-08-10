# artblocks

## 1. Table: GenArt721Core\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-25 00:09:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12104782                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8da64df32974ad05b3ebc964304be34240ea63e5e152d0ebf85b1d2cfc9c59d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7d8d9ef8d8ce8992df33d8b8cf4aebabd5bd270                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xa84f218ad6933e8f2dea6655895b70bd13ca5671                         |                                                              |
| operator          | VARCHAR   | 0xca1afcf4310014425d31b2c2ef48835f65438b48                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 2. Table: GenArt721Core\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 22:09:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13692306                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0bf898a8648abca8e2437f2bc780530d9d518681a4e7f0c548df34e9cc56add0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7d8d9ef8d8ce8992df33d8b8cf4aebabd5bd270                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x9794ea402a03b342dfddf07946445814a568be2e                         |                                                              |
| approved          | VARCHAR   | 0x6fc2226cc38fece07b6052fdb87ce7004401fe2a                         |                                                              |
| tokenId           | VARCHAR   | 180000042                                                          |                                                              |

## 3. Table: GenArt721Core\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-25 05:50:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14453656                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae4a6742f8239e151514bbcc211e331977581b0cdb0e9c50dc5c84cf70aec408 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 348                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7d8d9ef8d8ce8992df33d8b8cf4aebabd5bd270                         | Address of the contract that produced the log                |
| \_to              | VARCHAR   | 0xaeaa6e6e640e9db7447d9f064691796cadf7f9f1                         |                                                              |
| \_tokenId         | VARCHAR   | 207000390                                                          |                                                              |
| \_projectId       | VARCHAR   | 207                                                                |                                                              |

## 4. Table: GenArt721Core\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 21:07:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17858493                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ecfad67caf941b981c5f0714cceef52acc8d2e16ca877cbb5ad4ba107248eb0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7d8d9ef8d8ce8992df33d8b8cf4aebabd5bd270                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x6ec30fd91a504aad948839b985c7263888b2ad68                         |                                                              |
| to                | VARCHAR   | 0x00000000000a6d473a66abe3dbaab9e1388223bd                         |                                                              |
| tokenId           | VARCHAR   | 89000454                                                           |                                                              |

## 5. Table: GenArt721\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 05:28:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17682514                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2be02a9e86efad7858e93ca5301dbaadf3c12e4b8923f154306bbd7298cefd9f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 559                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x059edd72cd353df5106d2b9cc5ab83a52287ac3a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x14fa3d4f739403ac2c0060eafd25e1ec21359621                         |                                                              |
| operator          | VARCHAR   | 0x1e0049783f008a0085193e00003d00cd54003c71                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 6. Table: GenArt721\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-05 02:27:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17624704                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x322c0fe9dc647983061ef906e1c8ddf9dcb5a17619522d5121676db1ed4b1c41 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x059edd72cd353df5106d2b9cc5ab83a52287ac3a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x4c52ca29388a8a854095fd2beb83191d68dc840b                         |                                                              |
| approved          | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         |                                                              |
| tokenId           | VARCHAR   | 3788                                                               |                                                              |

## 7. Table: GenArt721\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-17 22:58:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11675584                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1218c976a38628196f770d90292e5461d27ec05adc574f8f822ff341cac356df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x059edd72cd353df5106d2b9cc5ab83a52287ac3a                         | Address of the contract that produced the log                |
| \_to              | VARCHAR   | 0xebf02c6e12c3ee119abba161c40bfeead0a06b15                         |                                                              |
| \_tokenId         | VARCHAR   | 9043                                                               |                                                              |
| \_projectId       | VARCHAR   | 0                                                                  |                                                              |
| \_invocations     | VARCHAR   | 9044                                                               |                                                              |
| \_value           | VARCHAR   | 35000000000000000                                                  |                                                              |

## 8. Table: GenArt721\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 17:42:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17351948                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a56240fbeb7e8c7d1059f650a3a808253d81d001a417093752dcae425703bec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x059edd72cd353df5106d2b9cc5ab83a52287ac3a                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x22514dce2d16ea7cd40b506592d69a93699f1e37                         |                                                              |
| to                | VARCHAR   | 0x1fdc057254476a7ae9c9fd994a7fa53e1c57c418                         |                                                              |
| tokenId           | VARCHAR   | 1312                                                               |                                                              |
