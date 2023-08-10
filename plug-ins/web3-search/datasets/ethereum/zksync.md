# zksync

## 1. Table: ZKSyncEra\_event\_BlockCommit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-16 06:58:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17270650                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa43e7e4edb7e76a2e408c39da9fa61e23325c0aabec73b830e33ba230f7af1f0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32400084c286cf3e17e7b677ea9583e60a000324                         | Address of the contract that produced the log                |
| blockNumber       | VARCHAR   | 30291                                                              |                                                              |
| blockHash         | VARCHAR   | 0x930729fbe397484ceefe01ded221c105c60d80ff2b3f9cd15c6b52ce4ec6ebad |                                                              |
| commitment        | VARCHAR   | 0xbe165138a48d0f8e57de90c1d6ee67f858fc035dd9cc2565b80a906a7cc4d9c3 |                                                              |

## 2. Table: ZKSyncEra\_event\_BlockExecution\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-26 13:36:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16911940                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ec034717181f68b13b14e19997b4298102f23983475eae1b3ee49d55f0f5b20 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32400084c286cf3e17e7b677ea9583e60a000324                         | Address of the contract that produced the log                |
| blockNumber       | VARCHAR   | 1028                                                               |                                                              |
| blockHash         | VARCHAR   | 0x57a55074151d607b934a707123e461459d395983fa0f233cdda98377f86e5f83 |                                                              |
| commitment        | VARCHAR   | 0x74406cea76f582eab8446fa561a8ff2f6141591a854581a8fba49422e1bb3513 |                                                              |

## 3. Table: ZKSyncEra\_event\_BlocksVerification\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2023-04-28 04:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 17142173                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x1f0823722cffa9f41c7b68ace56433caab60872f41dce3918e4d6d55379cbae2 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x32400084c286cf3e17e7b677ea9583e60a000324                         | Address of the contract that produced the log                |
| previousLastVerifiedBlock | VARCHAR   | 21321                                                              |                                                              |
| currentLastVerifiedBlock  | VARCHAR   | 21322                                                              |                                                              |

## 4. Table: zkSyncLite\_event\_BlockCommit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 11:08:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11587625                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4613aaf46af3710500016e7bfcff4d848d55af316c89b69ddaf539cd15a5b351 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xabea9132b05a70803a4e85094fd0e1800777fbef                         | Address of the contract that produced the log                |
| blockNumber       | VARCHAR   | 7573                                                               |                                                              |

## 5. Table: zkSyncLite\_event\_BlockVerification\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-22 00:35:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11903637                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ec407860c2350814e2b1c6a7990931dc7463b0b3709572c7064d6ab2c5b0c49 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xabea9132b05a70803a4e85094fd0e1800777fbef                         | Address of the contract that produced the log                |
| blockNumber       | VARCHAR   | 11415                                                              |                                                              |
