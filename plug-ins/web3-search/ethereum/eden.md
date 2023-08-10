# eden

## 1. Table: EdenToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 07:53:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17249706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xceabb3c1e304fb03c5edad32606d2ebb0d0585c3ad1601b77d0df3d3fe401133 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 267                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1559fa1b8f28238fd5d76d9f434ad86fd20d1559                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x29dd26b1cd7317bcc34d863db4df2381052df988                         |                                                              |
| spender           | VARCHAR   | 0x827179dd56d07a7eea32e3873493835da2866976                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: EdenToken\_event\_AuthorizationUsed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| authorizer        | VARCHAR   |                                                              |             |
| nonce             | VARCHAR   |                                                              |             |

## 3. Table: EdenToken\_event\_MetadataManagerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-28 17:04:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15847935                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6aa957283a4b0fe627ed89e57ef93dd1c9ee669f0aa964e46a05cfa9838c603f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1559fa1b8f28238fd5d76d9f434ad86fd20d1559                         | Address of the contract that produced the log                |
| oldManager        | VARCHAR   | 0x37165892032fc439e4b5e059087cfde55d1df79b                         |                                                              |
| newManager        | VARCHAR   | 0xe2cf1f948c2279916ded3908c693b388e58099e8                         |                                                              |

## 4. Table: EdenToken\_event\_RoleAdminChanged\_history

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

## 5. Table: EdenToken\_event\_RoleGranted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-28 23:46:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12917366                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb28c14a60d8f5a560537b5b4a4c018e52354d239f9075d82dd65dfce8202a409 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1559fa1b8f28238fd5d76d9f434ad86fd20d1559                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x9f2df0fed2c77648de5860a4cc508cd0818c85b8b8a1ab4ceeef8d981c8956a6 |                                                              |
| account           | VARCHAR   | 0xdfccb0225ce7618f9ece7297635c4bb703d566cf                         |                                                              |
| sender            | VARCHAR   | 0xfdf8be775bb5e2ba1983dc7b26a655321502e104                         |                                                              |

## 6. Table: EdenToken\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-02 21:51:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12948454                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26e09f7ed9fe846f2480da0e053114ce9eebf3602ba0f846ea0414c65f07b817 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 230                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1559fa1b8f28238fd5d76d9f434ad86fd20d1559                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0xfdf8be775bb5e2ba1983dc7b26a655321502e104                         |                                                              |
| sender            | VARCHAR   | 0xfdf8be775bb5e2ba1983dc7b26a655321502e104                         |                                                              |

## 7. Table: EdenToken\_event\_TokenMetaUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 17:17:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17146058                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf35bf4f062fb6b7b9807b0f92d82e71a82f77cb07b66d16b5f22c71e5d47eda | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 317                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1559fa1b8f28238fd5d76d9f434ad86fd20d1559                         | Address of the contract that produced the log                |
| name              | VARCHAR   | 0x99bc8e72a63018f735480e8834a13afe9b3cc6a5c8e65c19ca9f72e554f5ac00 |                                                              |
| symbol            | VARCHAR   | 0x99bc8e72a63018f735480e8834a13afe9b3cc6a5c8e65c19ca9f72e554f5ac00 |                                                              |

## 8. Table: EdenToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 17:21:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17750124                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a9ad133792bae40a69139fbcb17d5254fc62e657e7ee89e106a9e1f7ce74235 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 316                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1559fa1b8f28238fd5d76d9f434ad86fd20d1559                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x23ebcd701fd92867235aeb0174b7c444b9b2b3ad                         |                                                              |
| to                | VARCHAR   | 0x74de5d4fcbf63e00296fd95d33236b9794016631                         |                                                              |
| value             | VARCHAR   | 3264547384488852209588                                             |                                                              |
