# vesta\_finance

## 1. Table: VestaFarming\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 20:37:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 93718772                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55fd0b52e5cf6baa0c26bf38cd6569c2b41d72c01cb31785de31c5ae80c6a7f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65207da01293c692a37f59d1d9b1624f0f21177c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xb6f5de39742eeca134a2b4cda5ad4f43617e8f65                         |                                                              |
| amount            | VARCHAR   | 5126070000000000000                                                |                                                              |

## 2. Table: VestaFarming\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 20:29:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9708600                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78c75498f0c24dd8b553a5c6003178ef2051397588c71cf8fa1bce44bf8bcd65 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65207da01293c692a37f59d1d9b1624f0f21177c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x52c8fe1c30a22af561b1bf1e1d6a476b37d61c68                         |                                                              |
| amount            | VARCHAR   | 447100000000000000000                                              |                                                              |
