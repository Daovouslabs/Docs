# enclaves\_dex

## 1. Table: EnclavesDEX\_event\_Cancel\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-08-30 16:30:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6241563                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b28ecda77ea694b7d0ed885f4abf31bf913a5a1f1b3767e772c38166998999f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf45f4280cfbe7c2d2515a7d984b8c71c15e82b7                         | Address of the contract that produced the log                |
| tokenGet          | VARCHAR   | 0xf3cfbca4e083b1418f89545754c7da90d2418b10                         |                                                              |
| amountGet         | VARCHAR   | 10000000000000000000000000                                         |                                                              |
| tokenGive         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amountGive        | VARCHAR   | 1000000000000000                                                   |                                                              |
| expires           | VARCHAR   | 10000000000                                                        |                                                              |
| nonce             | VARCHAR   | 7748955252647094                                                   |                                                              |
| user              | VARCHAR   | 0xb1d5c1653f24a702981421c264d40c9c70efd756                         |                                                              |
| v                 | VARCHAR   | 27                                                                 |                                                              |
| r                 | VARCHAR   | 0x78a4bb8bad26661d979921be44091ca755198872b904fe729c03a7195f4ecb65 |                                                              |
| s                 | VARCHAR   | 0x0e7ae1a30a45e683d17749a5fecaafa7f8d82554173f6c791a5ea300f0060fb1 |                                                              |

## 2. Table: EnclavesDEX\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-04 13:31:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5731005                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9bf23462c61d8bc94ce16735673fb7dcd5352369492a6971f927682d6ab666b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf45f4280cfbe7c2d2515a7d984b8c71c15e82b7                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| user              | VARCHAR   | 0x0405bf7ffc76fc5d83cc89f59bf903fdc35f475b                         |                                                              |
| amount            | VARCHAR   | 3000000000000000                                                   |                                                              |
| balance           | VARCHAR   | 3000000000000000                                                   |                                                              |

## 3. Table: EnclavesDEX\_event\_Order\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tokenGet          | VARCHAR   |                                                              |             |
| amountGet         | VARCHAR   |                                                              |             |
| tokenGive         | VARCHAR   |                                                              |             |
| amountGive        | VARCHAR   |                                                              |             |
| expires           | VARCHAR   |                                                              |             |
| nonce             | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 4. Table: EnclavesDEX\_event\_Rebalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-05-22 12:54:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5657583                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92a9f5451b9bbe0f81535cd40521e3de78b52b69940dfe183ad5b3f9e034eed1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf45f4280cfbe7c2d2515a7d984b8c71c15e82b7                         | Address of the contract that produced the log                |
| dex               | VARCHAR   | 0xbf45f4280cfbe7c2d2515a7d984b8c71c15e82b7                         |                                                              |
| token             | VARCHAR   | 0xc42209accc14029c1012fb5680d95fbd6036e2a0                         |                                                              |
| amount            | VARCHAR   | 970000000000000000000                                              |                                                              |

## 5. Table: EnclavesDEX\_event\_Trade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-17 04:01:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7583055                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03ac2d1efd09f304324d182c37e55dfb3b2a6da565eb55b19536e3f834054b8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf45f4280cfbe7c2d2515a7d984b8c71c15e82b7                         | Address of the contract that produced the log                |
| tokenGet          | VARCHAR   | 0x8f7dbf90e71285552a687097220e1035c2e87639                         |                                                              |
| amountGet         | VARCHAR   | 10000000000000                                                     |                                                              |
| tokenGive         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amountGive        | VARCHAR   | 11000000000000000                                                  |                                                              |
| get               | VARCHAR   | 0x8811d0ef9f39fe7150c024270e12d3fe10593b63                         |                                                              |
| give              | VARCHAR   | 0xb9307de3a136c00b6e6980dfe4638df30f6df1f8                         |                                                              |
| exchange          | VARCHAR   | 1                                                                  |                                                              |

## 6. Table: EnclavesDEX\_event\_WithdrawPreSigned\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| feeToken          | VARCHAR   |                                                              |             |
| feeValue          | VARCHAR   |                                                              |             |
| feeReceiver       | VARCHAR   |                                                              |             |

## 7. Table: EnclavesDEX\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-03 12:05:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7168355                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc62df05d54d99d15a4b89d503b23604a36ee7294ab006102c8aa53bc352685cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf45f4280cfbe7c2d2515a7d984b8c71c15e82b7                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0235fe624e044a05eed7a43e16e3083bc8a4287a                         |                                                              |
| user              | VARCHAR   | 0xd61555213a8205697ba4714b4d9f61d7db2215ef                         |                                                              |
| amount            | VARCHAR   | 86017195767195                                                     |                                                              |
| balance           | VARCHAR   | 0                                                                  |                                                              |
