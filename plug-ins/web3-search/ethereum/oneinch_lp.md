# oneinch\_lp

## 1. Table: MooniswapFactory\_event\_DefaultDecayPeriodVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 15:39:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12978808                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefb635151118b7163cd537c7386acfa988b1e2fb4785f89c3f7c762ddc32c33f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xb7d7ce36de85e0e080b1f94fa7cd8a47378b1b4c                         |                                                              |
| decayPeriod       | VARCHAR   | 60                                                                 |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 105577647179352166900                                              |                                                              |

## 2. Table: MooniswapFactory\_event\_DefaultFeeVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-20 05:40:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13260797                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90851a8f7370c74aa4224d094c07ee6943d065203334d890657f1b455456168e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x88b6cace7c485db4a33f4da78d10abce5820467f                         |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: MooniswapFactory\_event\_DefaultSlippageFeeVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-29 19:23:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14681069                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x75aaf4e5e61401ad2b2dea4a3d2257a35b1ecdfff7f8947a4762367fbb06fa91 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xa6585b22c2c7c92e80c33bb6620e2869bad08cf5                         |                                                              |
| slippageFee       | VARCHAR   | 1000000000000000000                                                |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 4. Table: MooniswapFactory\_event\_Deployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 22:58:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12731740                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb36fa5149c187c5f3572d2ce3e2a3a32ef079afbabdb51d0496f7b8da040d6e8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| mooniswap         | VARCHAR   | 0x84b844a3804aa3a789318e55bb622f4513564dee                         | Address of the pool                                          |
| token1            | VARCHAR   | 0x0000000000000000000000000000000000000000                         | Address of token1                                            |
| token2            | VARCHAR   | 0x93c9175e26f57d2888c7df8b470c9eea5c0b0a93                         | Address of token2                                            |

## 5. Table: MooniswapFactory\_event\_FeeCollectorUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-07 13:41:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11607875                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf9ec2ac3c4261365de2a13e04c4bcc6490be01d8e72f6fe439ebdf4e36f00c64 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| feeCollector      | VARCHAR   | 0x2eea44e40930b1984f42078e836c659a12301e40                         |                                                              |

## 6. Table: MooniswapFactory\_event\_GovernanceShareVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-19 16:31:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17728432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2bfbf51515dc75199534511beccf5f8f60cf75a8858fc18c65fe24a286b153e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 382                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x9e427a0a538fdfea06895b4c1bbf895edceb4dc0                         |                                                              |
| governanceShare   | VARCHAR   | 0                                                                  |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 7. Table: MooniswapFactory\_event\_GovernanceWalletUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-07 13:35:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11607852                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbc299bca897071abcd76790018507beb59e9a6ca8c9fb565c8c6d1078bd5bde5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| governanceWallet  | VARCHAR   | 0x7e11a8887a2c445883acc453738635bc3acdadb6                         |                                                              |

## 8. Table: MooniswapFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-07 13:33:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11607841                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7f4833214a62e810f8ee7625c876fb82c96ca3c82508f489b2bb8fbea149ccbd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x11799622f4d98a24514011e8527b969f7488ef47                         |                                                              |

## 9. Table: MooniswapFactory\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 10. Table: MooniswapFactory\_event\_ReferralShareVoteUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 22:04:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17573538                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b850e7a538a53df5cd1d3afe2c2c374983848076aa6eaf45c1d839c1113ca6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbaf9a5d4b0052359326a6cdab54babaa3a3a9643                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x7596dd0ec6a059d1fd5c003df60cb019ad8dc38e                         |                                                              |
| referralShare     | VARCHAR   | 100000000000000000                                                 |                                                              |
| isDefault         | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 11. Table: MooniswapFactory\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 12. Table: Mooniswap\_event\_Swapped\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-11-15 03:18:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 13617916                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x5640410379df99ff7323aa689dd154f420c9c37494e4b681feb5827adbdc417d | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x0ef1b8a0e726fc3948e15b23993015eb1627f210                         | Address of the contract that produced the log                |
| sender             | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| receiver           | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| srcToken           | VARCHAR   | 0x111111111117dc0aa78b770fa6a738034120c302                         |                                                              |
| dstToken           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount             | VARCHAR   | 3829699012600525681337                                             |                                                              |
| result             | VARCHAR   | 3495175284323643258                                                |                                                              |
| srcAdditionBalance | VARCHAR   | 1179124181559311723894673                                          |                                                              |
| dstRemovalBalance  | VARCHAR   | 1086309930202132084990                                             |                                                              |
| referral           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
