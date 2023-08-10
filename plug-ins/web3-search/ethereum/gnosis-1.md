# gnosis

## 1. Table: MultiSigWalletWithDailyLimitFactory\_event\_ContractInstantiation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-03 15:12:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7297282                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x49b3b86cc48f71302faaf048c8ccf1d142fd381b757d216bcd67ab5b958e19bf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6e95c8e8557abc08b46f3c347ba06f8dc012763f                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xbdbf26b5ad95ad6ebf79a870e3f7f9f9bfc0091f                         |                                                              |
| instantiation     | VARCHAR   | 0xe98604413c217ea6f0f338506d9903815cd231ad                         |                                                              |

## 2. Table: MultiSigWalletWithDailyLimit\_event\_Confirmation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-08 14:12:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7031667                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9cf3c8c19e66797c018e0aecc20632f4eaf6289caefaa4438c381735360be76 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 277                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x10208fb4ef202bdc49803995b0a8ca185383bba4                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x5cff40372b96e133967d980f72812653163121fa                         |                                                              |
| transactionId     | VARCHAR   | 45                                                                 |                                                              |

## 3. Table: MultiSigWalletWithDailyLimit\_event\_DailyLimitChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-01 01:31:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9783029                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xffe96598019f9dd2e24ffb80640c968523813ad05e330fea65d1f68d3d85a89f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c53b88411eb2bb8f2741b47f3725f6b36407ec7                         | Address of the contract that produced the log                |
| dailyLimit        | VARCHAR   | 2000000000000000000                                                |                                                              |

## 4. Table: MultiSigWalletWithDailyLimit\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-25 20:03:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9943678                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfdbe036220541f4d4c4a43acea32a42fb78dae2a7babbffdc450d8486c4f421a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcb102cbfad94d71596d7d9172072da8b86e60fbd                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x055cc48f7968fd8640ef140610dd4038e1b03926                         |                                                              |
| value             | VARCHAR   | 2000000000000000                                                   |                                                              |

## 5. Table: MultiSigWalletWithDailyLimit\_event\_ExecutionFailure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-30 05:47:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7667018                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88ec6d7ba81fa0900a10cb6a798e7e8975c4bb3c8e873067b37b8400c91822c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x492eea2038aadc701259f3535841ab985c2f9a80                         | Address of the contract that produced the log                |
| transactionId     | VARCHAR   | 1469                                                               |                                                              |

## 6. Table: MultiSigWalletWithDailyLimit\_event\_Execution\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 15:25:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14353371                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x135a960209347cab7774b980342e9a05d9493a8ce47d687cda972b25d40cc872 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 251                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x332d87209f7c8296389c307eae170c2440830a47                         | Address of the contract that produced the log                |
| transactionId     | VARCHAR   | 105                                                                |                                                              |

## 7. Table: MultiSigWalletWithDailyLimit\_event\_OwnerAddition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-11 14:58:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9650884                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x07e3412253d09d068a481f7e6174aa6e2d9243bf0a81d9481d098e361ac5fd2b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e8cd851dea1740ab897168856a94475c752186b                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xcacc64639ddb226398272c73bc04cc8e1f56675d                         |                                                              |

## 8. Table: MultiSigWalletWithDailyLimit\_event\_OwnerRemoval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-30 14:25:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6800864                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0605d4c6f37ad80dde1ee8d4e919cec7c36d79e6299f6262d89a3f7de5c5caba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5afc06c035619654927614fac6bc1c0413715e59                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x6fd8b8ee94299ea46dfc5bfedb81f348a0eabab6                         |                                                              |

## 9. Table: MultiSigWalletWithDailyLimit\_event\_RequirementChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-12-10 17:43:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6862157                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65ffd2fa393eb179b8e6bedcf0981dfe8b4be5fd92ef59768ad3d854a867945a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9b93445a8354d3b4c6cb6be61c9858abdf4a1665                         | Address of the contract that produced the log                |
| required          | VARCHAR   | 2                                                                  |                                                              |

## 10. Table: MultiSigWalletWithDailyLimit\_event\_Revocation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-30 06:23:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9381888                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed81765679ef8a8bd5d41ab775f2004b3871aff3fde1f5b533a7495f8b48c995 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa847dc227d3f3e86fa01406279c1e88cb6950c3a                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xfe2321d7dfa492dfc39330e8b85e7c49161e7f98                         |                                                              |
| transactionId     | VARCHAR   | 24                                                                 |                                                              |

## 11. Table: MultiSigWalletWithDailyLimit\_event\_Submission\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 05:47:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14137694                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa963f40d66127ff69e9dd505061aacee5ead5d564d3379308942acee8e426e08 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0258d8437e4ac3f276a10c947724099190ec0b8f                         | Address of the contract that produced the log                |
| transactionId     | VARCHAR   | 19                                                                 |                                                              |
