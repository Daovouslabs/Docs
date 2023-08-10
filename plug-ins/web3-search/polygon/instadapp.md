# instadapp

## 1. Table: InstaIndex\_event\_LogAccountCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 21:44:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40766758                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd29d9685bfab57e434253b9df887c8129341fce9ee1e47bcdf003836404ff82b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa9b99766e6c676cf1975c0d3166f96c0848ff5ad                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x2f3e438b66127355466c0b274c71d2425e81858e                         |                                                              |
| owner             | VARCHAR   | 0x2f3e438b66127355466c0b274c71d2425e81858e                         |                                                              |
| account           | VARCHAR   | 0xef0856af464f66bbdbeaa356f4e29ae58f431727                         |                                                              |
| origin            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 2. Table: InstaIndex\_event\_LogNewAccount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-03 00:25:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12795303                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3e88c3a0fb46dd5fa2a437912d623edd18d5ff0a7fc4bf002cfdfaf01e2fb57 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa9b99766e6c676cf1975c0d3166f96c0848ff5ad                         | Address of the contract that produced the log                |
| \_newAccount      | VARCHAR   | 0x28846f4051eb05594b3ff9de76b7b5bf00431155                         |                                                              |
| \_connectors      | VARCHAR   | 0x01fef4d2b513c9f69e34b2f93ef707fa9ff60109                         |                                                              |
| \_check           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 3. Table: InstaIndex\_event\_LogNewCheck\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| accountVersion    | VARCHAR   |                                                              |             |
| check             | VARCHAR   |                                                              |             |

## 4. Table: InstaIndex\_event\_LogNewMaster\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-25 11:03:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17252241                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc348344a6719418ad6bab5f5336bac5fe26da244115bfe53e570c3fe7da691c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa9b99766e6c676cf1975c0d3166f96c0848ff5ad                         | Address of the contract that produced the log                |
| master            | VARCHAR   | 0x90cf378a297c7ef6dabed36ea5e112c6646bb3a4                         |                                                              |

## 5. Table: InstaIndex\_event\_LogUpdateMaster\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-09 14:59:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13063649                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf373a71b2a6093536105a9d451024f856d9bb0be077bd4da8f9df9c772fe202 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa9b99766e6c676cf1975c0d3166f96c0848ff5ad                         | Address of the contract that produced the log                |
| master            | VARCHAR   | 0x31de2088f38ed7f8a4231de03973814eda1f8773                         |                                                              |
