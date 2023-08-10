# argent

## 1. Table: ArgentENSManager\_event\_ManagerAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-04 13:39:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7173592                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf7e1bf9e76b69a85a3e760a2d245da2d960268c0ec63755cdcb2eacf854e8026 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x30b406dd3cc461112bcd0dd2a2eaf0641c1a1d62                         | Address of the contract that produced the log                |
| \_manager         | VARCHAR   | 0x851cc731ce1613ae4fd8ec7f61f4b350f9ce1020                         |                                                              |

## 2. Table: ArgentENSManager\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-04 13:49:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7173625                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88140a935a44980323b44371e4272e998a932aa3e4c01bf9579d02e96358872d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x30b406dd3cc461112bcd0dd2a2eaf0641c1a1d62                         | Address of the contract that produced the log                |
| \_newOwner        | VARCHAR   | 0xa5c603e1c27a96171487aea0649b01c56248d2e8                         |                                                              |

## 3. Table: ArgentENSManager\_event\_Registered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-11 00:02:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9256210                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43e214e4e030edc81f14be9955d6574238b966c511cb105e89a0d145ca1e0df5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x30b406dd3cc461112bcd0dd2a2eaf0641c1a1d62                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x2d0dd75ae9895cfb58f9bdb6345cf661e3183483                         |                                                              |
| \_ens             | VARCHAR   | headspin.argent.xyz                                                |                                                              |

## 4. Table: ArgentENSManager\_event\_RootnodeOwnerChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-30 13:10:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9773231                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x098de17d29f718d811d24c4d37c7b0425943ba4a1e3051196c72734a2225a8d0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x30b406dd3cc461112bcd0dd2a2eaf0641c1a1d62                         | Address of the contract that produced the log                |
| \_rootnode        | VARCHAR   | 0xf0b914d803bfbcc81715a4b6f6abb05dd0e6b106f3574a8c36ef7dce598567a4 |                                                              |
| \_newOwner        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 5. Table: ArgentENSManager\_v2\_event\_ENSResolverChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 6. Table: ArgentENSManager\_v2\_event\_ManagerAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-30 13:01:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9773188                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf325eeb805f13e16f2b325b3ee8a8cbf5a6e8935f2905961bebc0eeb13a41c83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4baabb5b7dff84aa8023183e3ca0ba3b2fee519                         | Address of the contract that produced the log                |
| \_manager         | VARCHAR   | 0x40c84310ef15b0c0e5c69d25138e0e16e8000fe9                         |                                                              |

## 7. Table: ArgentENSManager\_v2\_event\_ManagerRevoked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_manager         | VARCHAR   |                                                              |             |

## 8. Table: ArgentENSManager\_v2\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-30 13:01:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9773190                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb3de0de412700234456c18df5eb8b586bd803077742ca2d6ef0423ac42ab3bc1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 177                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4baabb5b7dff84aa8023183e3ca0ba3b2fee519                         | Address of the contract that produced the log                |
| \_newOwner        | VARCHAR   | 0xa5c603e1c27a96171487aea0649b01c56248d2e8                         |                                                              |

## 9. Table: ArgentENSManager\_v2\_event\_Registered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-21 04:30:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11696683                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83647f3db841e2c8ce7be59b02efe6d94804c33611f81ca31d9f7c5f46c0ab61 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4baabb5b7dff84aa8023183e3ca0ba3b2fee519                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x5c5f622472fe83d1d502ede620e630adc264fdf5                         |                                                              |
| \_ens             | VARCHAR   | lavie.argent.xyz                                                   |                                                              |

## 10. Table: ArgentENSManager\_v2\_event\_RootnodeOwnerChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-23 14:08:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12296888                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2de352686536c72f3f2ae40e8b6e89b09d6488250bcd5511587c94df2e28110f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 164                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4baabb5b7dff84aa8023183e3ca0ba3b2fee519                         | Address of the contract that produced the log                |
| \_rootnode        | VARCHAR   | 0xf0b914d803bfbcc81715a4b6f6abb05dd0e6b106f3574a8c36ef7dce598567a4 |                                                              |
| \_newOwner        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 11. Table: ArgentENSManager\_v2\_event\_Unregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_ens             | VARCHAR   |                                                              |             |

## 12. Table: ArgentENSManager\_v3\_event\_ENSResolverChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 13. Table: ArgentENSManager\_v3\_event\_ManagerAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-23 14:00:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12296845                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x756f5b11084acc394f54132f562d8ea6b7592207287c4ecd55ea352bb1497b27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 155                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf32fddef964b98b1d2d2b1c071ac60ed55d4d217                         | Address of the contract that produced the log                |
| \_manager         | VARCHAR   | 0xf27696c8bca7d54d696189085ae1283f59342fa6                         |                                                              |

## 14. Table: ArgentENSManager\_v3\_event\_ManagerRevoked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_manager         | VARCHAR   |                                                              |             |

## 15. Table: ArgentENSManager\_v3\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-23 14:06:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12296879                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x212fcbf37670a259d0ca24911e8da90d8d71b99889eb71040d5500947137d697 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf32fddef964b98b1d2d2b1c071ac60ed55d4d217                         | Address of the contract that produced the log                |
| \_newOwner        | VARCHAR   | 0xa5c603e1c27a96171487aea0649b01c56248d2e8                         |                                                              |

## 16. Table: ArgentENSManager\_v3\_event\_Registered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-27 07:51:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12321117                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc453b10ab7cb4b6e8b48bc197adeb32ca97877b2f345e286e2f7bcec437444b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 213                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf32fddef964b98b1d2d2b1c071ac60ed55d4d217                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x5c2dc9fa827fdced0f7f7fa1c440c4055ba038ef                         |                                                              |
| \_ens             | VARCHAR   | cryptodeetu.argent.xyz                                             |                                                              |

## 17. Table: ArgentENSManager\_v3\_event\_RootnodeOwnerChange\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_rootnode        | VARCHAR   |                                                              |             |
| \_newOwner        | VARCHAR   |                                                              |             |

## 18. Table: ArgentENSManager\_v3\_event\_Unregistered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_ens             | VARCHAR   |                                                              |             |

## 19. Table: BaseWallet\_event\_AuthorisedModule\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-28 11:35:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10153980                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04f67d2d85fbe3119a50857fb49cce7c16efc6f1b201051979cece2a2e6b49aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xab900becf2b87071e484652fdd3b707e5163c1a6                         | Address of the contract that produced the log                |
| module            | VARCHAR   | 0xa24783c07cdd995c56c1d33ce485e6ac39e0c018                         |                                                              |
| value             | VARCHAR   | true                                                               |                                                              |

## 20. Table: BaseWallet\_event\_EnabledStaticCall\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 16:08:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13237779                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd1c19db7895d40b25721aac207b2621a031931c33ae1e0560eff3a98f61b709a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 334                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd4f9da444ae3ddbae987370fcf9dde2598a263aa                         | Address of the contract that produced the log                |
| module            | VARCHAR   | 0x9d58779365b067d5d3fcc6e92d237acd06f1e6a1                         |                                                              |
| method            | VARCHAR   | 0x150b7a02                                                         |                                                              |

## 21. Table: BaseWallet\_event\_Invoked\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 09:52:59+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17662495                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83bed1f4316cd5b3fa8f9fba7bb73c6b61ad6dca7f84b44e6433b675c2847152                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 228                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc8a8020f93a27f68c0cb6357a2128dacd9f6db42                                                           | Address of the contract that produced the log                |
| module            | VARCHAR   | 0x9d58779365b067d5d3fcc6e92d237acd06f1e6a1                                                           |                                                              |
| target            | VARCHAR   | 0xa8b919680258d369114910511cc87595aec0be6d                                                           |                                                              |
| value             | VARCHAR   | 0                                                                                                    |                                                              |
| data              | VARCHAR   | 0xa9059cbb0000000000000000000000006017b1d17f4d7547dc4aac88fbd0aa1826e7e6ce00000000000000000000000000 |                                                              |

## 22. Table: BaseWallet\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 23:15:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17382047                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe337b030b7f9a145b5bd566ffcd9a6367f3d4fdbcb599f8b900a35c81026b072 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd7731bc42738827851d26a4d5fd5a58967685517                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x666d71f8938fd2e7fc0a87652381dafad9f5c070                         |                                                              |

## 23. Table: BaseWallet\_event\_Received\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-07 07:54:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15694864                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2d062834efe93d96a084d7bdb8de78ea20d7c46ef3336fb27ab9fae67d2955b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcddcd9e7766ed819bc1eb6ad66d75c7ec732a24f                         | Address of the contract that produced the log                |
| value             | VARCHAR   | 3703361153802707                                                   |                                                              |
| sender            | VARCHAR   | 0x283af0b28c62c092c9727f1ee09c02ca627eb7f5                         |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |

## 24. Table: GuardianManager\_event\_GuardianAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-24 08:09:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8411818                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3ded038a35a8308c6e983c950857cd2891c2595d93f791f822b993bd6d7360b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x13f7657fc48082668efa2ab345e4c0b22253c9bd                         |                                                              |
| guardian          | VARCHAR   | 0x2693563ee94ba6dd0f208219a92e89ef410e2dc6                         |                                                              |

## 25. Table: GuardianManager\_event\_GuardianAdditionCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-09 14:47:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10232123                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x01e129e6215234a00cd1609bb4f6a780a8d27b08377975f48fc5a3e46a31bde8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x777832056011ccc802c40857447b102204ac2678                         |                                                              |
| guardian          | VARCHAR   | 0x8652df7d1d90c9b729b7b960909eb38404ab8dc8                         |                                                              |

## 26. Table: GuardianManager\_event\_GuardianAdditionRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-24 21:13:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8415239                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6f53574e69b1f87b0cec23af64dedb15d5c3de4a3e9055a7ff751b7993c2304 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x0449378942c77e14dfab5668b65008f45406a2c8                         |                                                              |
| guardian          | VARCHAR   | 0x45cb7b221a4d1fed8bf4b0a3c80509a3d1ffdbfc                         |                                                              |
| executeAfter      | VARCHAR   | 1566767594                                                         |                                                              |

## 27. Table: GuardianManager\_event\_GuardianRevokationCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-28 01:52:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10351404                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6afa3e396b72bdf858fc8b898e068866c740a33fd430ac2a588e517cb14cc7a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x030c6c95835c5a28c6b90cd16889702619641a72                         |                                                              |
| guardian          | VARCHAR   | 0x311f3e3ac0c921a3fd0e6b5f3f6a272af937f792                         |                                                              |

## 28. Table: GuardianManager\_event\_GuardianRevokationRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-02 12:36:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8470813                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x180018617b887975adc95ab20fae6d764841e09e588297c4028ddaade1106432 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x90b411d1a9fe6a3004a61a6acbcfb7c2c21e41f3                         |                                                              |
| guardian          | VARCHAR   | 0x83d5940c532006deedc887238321598d694e4184                         |                                                              |
| executeAfter      | VARCHAR   | 1567514210                                                         |                                                              |

## 29. Table: GuardianManager\_event\_GuardianRevoked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 01:43:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10687632                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3020d55936f771c2031ef42f89c4a5490e5813d52cda840e1fe8f7084cede39a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x20677a9d7da0b06b59cf773041e64b17ce1c64c9                         |                                                              |
| guardian          | VARCHAR   | 0x62728c1b284fe06af77c273eb99accdce1678159                         |                                                              |

## 30. Table: GuardianManager\_event\_ModuleCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-04 14:03:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7173660                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x700e5e83396470bec3353414cd5a195303becedd1635dc52a83d53446434d148 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| name              | VARCHAR   | 0x477561726469616e4d616e616765720000000000000000000000000000000000 |                                                              |

## 31. Table: GuardianManager\_event\_ModuleInitialised\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-12 01:04:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10247781                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2220659b7ad14e12f4b75806b70bf913810a1c8cc97954915ec14acd83b7d0d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x5a620f3352aa5660432b6b4bb671a431afb3374a                         |                                                              |

## 32. Table: GuardianManager\_event\_TransactionExecuted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-29 10:48:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7462964                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9700f7f7263cb501710d263f23258d4cadec5bbe11ac50b529288e11360d4af0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff5a7299ff6f0fbaad9b38906b77d08c0fbdc9a7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x5893b5200cfcadf962226cebce7859fb3ba4849a                         |                                                              |
| success           | VARCHAR   | true                                                               |                                                              |
| signedHash        | VARCHAR   | 0xb9811623c192c8cb1e136605c2ca3bfc51923db3b72cb011b61680faf2eea371 |                                                              |

## 33. Table: TransferManager\_event\_AddedToWhitelist\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-16 02:27:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10074432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x10f17bc8523de85314c9fd0ffacd0d962bea7a36d234fdec5e4aa8cf84f3ef36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x4e96bf06c55f746a83b43ee160874b8c9562b751                         |                                                              |
| target            | VARCHAR   | 0x0cf30cbeaac431c83b6971dec4c59e7903dbd412                         |                                                              |
| whitelistAfter    | VARCHAR   | 1589682445                                                         |                                                              |

## 34. Table: TransferManager\_event\_Approved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-09 00:50:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10028931                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c5f7730d3defc388de4d30b89254b7dde4078a19bc8202e0b6815416cc7f4a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xa11075f24f2962aa5f423953b30305ac7663bb72                         |                                                              |
| token             | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| amount            | VARCHAR   | 100000000                                                          |                                                              |
| spender           | VARCHAR   | 0x818e6fecd516ecc3849daf6845e3ec868087b755                         |                                                              |

## 35. Table: TransferManager\_event\_CalledContract\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-03 23:51:29+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9046389                                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf24ad0d57b80f8678b1108f95211ca438a4d6e5c85b0aaf4ab3e1d186d7ed662                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                                                           | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x107c869a42a737fd3dbcdb8aae094eabf120af8d                                                           |                                                              |
| to                | VARCHAR   | 0x241e82c79452f51fbfc89fac6d912e021db1a3b7                                                           |                                                              |
| amount            | VARCHAR   | 100000000000000000                                                                                   |                                                              |
| data              | VARCHAR   | 0x8059cf3b000000000000000000000000000000000000000000000000000000000000002000000000000000000000000000 |                                                              |

## 36. Table: TransferManager\_event\_LimitChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-21 19:13:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9716806                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0033046298ea029db0763b63a972393cc76524fe4269cc7a948a2c095bceeb44 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x2004ca7bac74423e77684e59f3c12b46c5fe77ce                         |                                                              |
| newLimit          | VARCHAR   | 5000000000000000000                                                |                                                              |
| startAfter        | VARCHAR   | 1584904419                                                         |                                                              |

## 37. Table: TransferManager\_event\_ModuleCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-28 14:01:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9015852                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e64a50ee56d7571177ff519386daf714163396aa01be72daf3d88903040a62d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| name              | VARCHAR   | 0x5472616e736665724d616e616765720000000000000000000000000000000000 |                                                              |

## 38. Table: TransferManager\_event\_PendingTransferCanceled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-03 20:56:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9411902                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x485cd026434d08b1f0c0ee61191ed3eefc99820f6d918f0bf632b75d504e8f8e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xe022bdf73d5c61b9d9392ad51a41cac0c666beb1                         |                                                              |
| id                | VARCHAR   | 0xc3d20e20ed20b7fd8c107554293bb105bdbd7012717acdc7c7b06090ce4568a4 |                                                              |

## 39. Table: TransferManager\_event\_PendingTransferCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-02 11:52:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9792431                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2c081ec6142d529cb26fd35590de942672c514f03d35ef9a3aebc28e693ecb88 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x30d96d6ea5f5d8cbb46a20cc788deba29e8677b0                         |                                                              |
| id                | VARCHAR   | 0x7c5a9429bfb7da77c9b4fb4d93dc6250a8ec136aae15cfd1e1bf063dc18847a7 |                                                              |
| executeAfter      | VARCHAR   | 1585914762                                                         |                                                              |
| token             | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| to                | VARCHAR   | 0x3450c8909e7655db27bc6ec7172ee43e922c04d7                         |                                                              |
| amount            | VARCHAR   | 311998008372606812103                                              |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |

## 40. Table: TransferManager\_event\_PendingTransferExecuted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-11 21:59:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9652804                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x176bc1fee052fbb91ccc433566ab1ef3af3fa43cf5e8beb778b33d0e638eec86 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xb30cc0e7fc1f65bb3dd7ebd647a0f1aa78326f20                         |                                                              |
| id                | VARCHAR   | 0xd485b04f10f8f2af3b7acb2fda79664647bdfbe3d742d004c9abf6b9bd4d2061 |                                                              |

## 41. Table: TransferManager\_event\_RemovedFromWhitelist\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-07 23:28:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9068755                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e29eb236d85e76a9de680405a1fe4ef3169aebb5dddcc01cca4ec7c481b91a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x107c869a42a737fd3dbcdb8aae094eabf120af8d                         |                                                              |
| target            | VARCHAR   | 0x11111254369792b2ca5d084ab5eea397ca8fa48b                         |                                                              |

## 42. Table: TransferManager\_event\_TransactionExecuted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 16:56:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16112776                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x625b30332e38de7bec17561b3b9cc984f61f7ad6b1be2479579d76e70fdfbc54 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 468                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xc536c39d7fc2d1f1935104a1867e97a7d869c870                         |                                                              |
| success           | VARCHAR   | true                                                               |                                                              |
| signedHash        | VARCHAR   | 0xc1280d6769dc155ed4900accfc7100aa625340751c99891238dc8ef0230498a2 |                                                              |

## 43. Table: TransferManager\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-02 16:13:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9987785                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae5a7152dc18bb229584039a8a6146dce6409af78288519d5459284c39e2a434 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b6d87f12b106e1d3fa7137494751566329d1045                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xf2ff255b7d64b8decdc12fd33f73bf526152365d                         |                                                              |
| token             | VARCHAR   | 0x0ba45a8b5d5575935b8158a88c631e9f9c95a2e5                         |                                                              |
| amount            | VARCHAR   | 1316224830000000000                                                |                                                              |
| to                | VARCHAR   | 0xe5a181cd0c5f911b6a1940ab43ba4325dfb0fc31                         |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |

## 44. Table: WalletFactory\_2\_event\_ManagerAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-23 11:40:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12296242                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6f56e3e6be40f00f51da190f48a2a0d2344036834fc244429290eb649d93b19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x536384fcd25b576265b6775f383d5ac408ff9db7                         | Address of the contract that produced the log                |
| \_manager         | VARCHAR   | 0x7be5474bf4e30b5a5f65ba8f8383f6bcb708d6c5                         |                                                              |

## 45. Table: WalletFactory\_2\_event\_ManagerRevoked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_manager         | VARCHAR   |                                                              |             |

## 46. Table: WalletFactory\_2\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-23 11:45:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12296264                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1c058559819bbb67538aff9d5ff575656981efee44e549d6ecb6ed769c15ec4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x536384fcd25b576265b6775f383d5ac408ff9db7                         | Address of the contract that produced the log                |
| \_newOwner        | VARCHAR   | 0xa5c603e1c27a96171487aea0649b01c56248d2e8                         |                                                              |

## 47. Table: WalletFactory\_2\_event\_RefundAddressChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| addr              | VARCHAR   |                                                              |             |

## 48. Table: WalletFactory\_2\_event\_WalletCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-14 13:51:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15746762                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c7519da7aa0bec6720049ff367d3119ff51421824b275a8df3fc39d9539c470 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x536384fcd25b576265b6775f383d5ac408ff9db7                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x5aff1ebc5cc92a30e93e93218aa11547b05cb5b0                         |                                                              |
| owner             | VARCHAR   | 0x5d9729e30e2a5d320f7a550b344a085a2b37f8e5                         |                                                              |
| guardian          | VARCHAR   | 0xbe43737b7fa5d0f8c481d9410c3f3ec016b93dd6                         |                                                              |
| refundToken       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| refundAmount      | VARCHAR   | 5400000000000000                                                   |                                                              |

## 49. Table: WalletFactory\_3\_event\_WalletCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-13 12:54:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12626253                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f97f6fd8ccf86d53418d8a5a9b817c49b6fa5a09ae546481b303ef71822f53c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 341                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1d09a6d1c45d1a9eb8cb8a8354bcd78e225f06d3                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0xe095559459cd0b1848e2793f0da2cdb21bcf098f                         |                                                              |
| owner             | VARCHAR   | 0x1f41a0b1be6a1b7b2d320a9ee9aa31e5bcbc6cf9                         |                                                              |
| guardian          | VARCHAR   | 0x333d77476c8e85d2b417f63955ea73e692098280                         |                                                              |
| refundToken       | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| refundAmount      | VARCHAR   | 30000000                                                           |                                                              |

## 50. Table: WalletFactory\_4\_event\_WalletCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-13 08:50:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10450208                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02f6f18e6672e3bd0134d4c169668af59e31cfa3d013582283f61eafa6c95dbb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 287                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x40c84310ef15b0c0e5c69d25138e0e16e8000fe9                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x05f2421485b7e9d6b5cba2efea5623dbc27f2ba5                         |                                                              |
| owner             | VARCHAR   | 0x45005eb714635ee94f00ac768184341ef878d224                         |                                                              |
| guardian          | VARCHAR   | 0xf43b6488e59357ef3a6746dbb5ad1f8f82ac1c8b                         |                                                              |

## 51. Table: WalletFactory\_5\_event\_WalletCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-09 16:57:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11621761                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0f18f2cfdf7410da26f2b169108a9fded2dfd3ac6d64923b9dd005e622ba9f14 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ae0acdb750bfcf694675f46b580847fc49a48bf                         | Address of the contract that produced the log                |
| wallet            | VARCHAR   | 0x596472c3bd5673997893d260ceb927a0ed988a30                         |                                                              |
| owner             | VARCHAR   | 0x844ff707ceec8147941eb7540c6ec6cc01ec060d                         |                                                              |
| guardian          | VARCHAR   | 0x30e2ebd71ba4d32886360b207b0fb6c4d68fb225                         |                                                              |

## 52. Table: WalletFactory\_event\_ManagerAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-04 13:39:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7173593                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83deb975d662ae6289e5e4db2a2f67b37d3bcf3eb52015d523e32fa27c63acd6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x851cc731ce1613ae4fd8ec7f61f4b350f9ce1020                         | Address of the contract that produced the log                |
| \_manager         | VARCHAR   | 0xa1a1224e9071470ab12a8df7626d4fe7789a039d                         |                                                              |

## 53. Table: WalletFactory\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-04 13:50:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7173630                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45cfcf713276317fbacede99364eb889aca0267adc608d05968a9853fd2667cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x851cc731ce1613ae4fd8ec7f61f4b350f9ce1020                         | Address of the contract that produced the log                |
| \_newOwner        | VARCHAR   | 0xa5c603e1c27a96171487aea0649b01c56248d2e8                         |                                                              |

## 54. Table: WalletFactory\_event\_WalletCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-10 08:08:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9453896                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb257c086303e3574d0a2e80e35b148f0fe0a056e029013e5aeed2959f84892ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x851cc731ce1613ae4fd8ec7f61f4b350f9ce1020                         | Address of the contract that produced the log                |
| \_wallet          | VARCHAR   | 0xd542804c4f88dd951dd153ffdf4947098a66ea97                         |                                                              |
| \_owner           | VARCHAR   | 0xf30d861301d73acf702c8aa5ef1d66e4fbd1c6f8                         |                                                              |
