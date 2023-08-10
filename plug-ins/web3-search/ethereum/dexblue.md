# dexblue

## 1. Table: dexBlue\_event\_LogBlockedForSingleSigWithdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-01 04:09:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10371345                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8df706e845066a38e88a6a004d1565d44a41595bd8e6b5efdf2e813160cc1743 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000000000000541e251335090ac5b47176af4f7e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x8e9a785039ed7069e59f8a6ee02f8b9ffd8bbe18                         |                                                              |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: dexBlue\_event\_LogDelegateStatus\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-11 13:31:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8720671                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb243eae6f52291ab8bb0d7d6484e648e060d5c383abf169fcf6d5c365b893088 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000000000000541e251335090ac5b47176af4f7e                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0x75359ca9e21376565d4a7fa02dbbf206fbe35895                         |                                                              |
| delegate          | VARCHAR   | 0xdc10c72151c2da5af0856e6a40a2a677018034d7                         |                                                              |
| status            | VARCHAR   | true                                                               |                                                              |

## 3. Table: dexBlue\_event\_LogDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-04 09:33:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10198490                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94b09442544fc2a3f1394bb1a7667c3f2d0479c8125d95654756bc58fac9081d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000000000000541e251335090ac5b47176af4f7e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x716b6b6baab9068841e9d7b05e3e43608cd669ab                         |                                                              |
| token             | VARCHAR   | 0x514910771af9ca656af840dff83e8264ecf986ca                         |                                                              |
| amount            | VARCHAR   | 55282000000000000000                                               |                                                              |

## 4. Table: dexBlue\_event\_LogDirectWithdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-04 23:25:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9051855                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa3d2b520c93957fb8a3b8775a8c930f3d8fb7f73551bb1fd2dd0540c3c05aa79 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000000000000541e251335090ac5b47176af4f7e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x1a3913e00ac3919bb867b37f64e237132885fa9d                         |                                                              |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount            | VARCHAR   | 374729399280000000                                                 |                                                              |

## 5. Table: dexBlue\_event\_LogOrderCanceled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| hash              | VARCHAR   |                                                              |             |

## 6. Table: dexBlue\_event\_LogSingleSigWithdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-28 14:15:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13114373                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x79cddd59db589b5b21fd76886650b1e9e0b034f59b6de5589c5826037c5c8bb1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 597                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000000000000541e251335090ac5b47176af4f7e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x1d55cdbb71827e89c98841f8a52ac84d025558a1                         |                                                              |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount            | VARCHAR   | 10000000000000                                                     |                                                              |

## 7. Table: dexBlue\_event\_LogSwap\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| soldAsset         | VARCHAR   |                                                              |             |
| soldAmount        | VARCHAR   |                                                              |             |
| boughtAsset       | VARCHAR   |                                                              |             |
| boughtAmount      | VARCHAR   |                                                              |             |

## 8. Table: dexBlue\_event\_LogTradeFailed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-05 16:54:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10206908                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ece410517639ee05e6427ce64ff65a0ef5ebadbb7c56d28b0b22af4b7f18aac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000000000000541e251335090ac5b47176af4f7e                         | Address of the contract that produced the log                |

## 9. Table: dexBlue\_event\_LogTrade\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-29 10:28:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10553941                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98707bf010d9940e5fa4f0b7c85a96173fbdc89593abf879a009906f40d9f0cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000000000000541e251335090ac5b47176af4f7e                         | Address of the contract that produced the log                |
| makerAsset        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| makerAmount       | VARCHAR   | 1339554028000000000                                                |                                                              |
| takerAsset        | VARCHAR   | 0x0ba45a8b5d5575935b8158a88c631e9f9c95a2e5                         |                                                              |
| takerAmount       | VARCHAR   | 38062000000000000000                                               |                                                              |

## 10. Table: dexBlue\_event\_LogWithdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-01 10:59:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9785626                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60bbda2ee924df2928c9b1a9679190e426708d7e60949c82f990f36245b527c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000000000000541e251335090ac5b47176af4f7e                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x0d7effefdb084dfeb1621348c8c70cc4e871eba4                         |                                                              |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount            | VARCHAR   | 49731433500000000000                                               |                                                              |
