# paraswap

## 1. Table: AugustusSwapperOld\_v1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-30 12:57:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8650194                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbd7242b84d1d3942e005bfdec1ad326b4a464d97fa842d879f1a17725cfc1360 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b158039b9678b7452f311deb12dd08c579dad26                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x60fb0b38ff0fcb98462e70aa5da4dff047635ec3                         |                                                              |

## 2. Table: AugustusSwapperOld\_v1\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-14 12:53:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8932530                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8f7bdccc40cd59a8fb4e51b8415850607085eca83c2e7a5c602999b1950150e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b158039b9678b7452f311deb12dd08c579dad26                         | Address of the contract that produced the log                |

## 3. Table: AugustusSwapperOld\_v1\_event\_Payed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-01 08:42:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8655466                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x13c6e97289f2cb4a908dcb5e2420840f1ca8157e9dbb297434f7fdd577098f32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b158039b9678b7452f311deb12dd08c579dad26                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x60fb0b38ff0fcb98462e70aa5da4dff047635ec3                         |                                                              |
| srcToken          | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| destToken         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| srcAmount         | VARCHAR   | 60000000000000000000                                               |                                                              |
| receivedAmount    | VARCHAR   | 334176109709408654                                                 |                                                              |

## 4. Table: AugustusSwapperOld\_v1\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-09 19:52:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8709637                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x206dd6a3d7f58b00c1985803b0613ea48a5e6ee782a8eef4f82f477907f27ecc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b158039b9678b7452f311deb12dd08c579dad26                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0951ff0835302929d6c0162b3d2495a85e38ec3a                         |                                                              |
| srcToken          | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| destToken         | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| srcAmount         | VARCHAR   | 100000000000000000                                                 |                                                              |
| receivedAmount    | VARCHAR   | 18983000000000000000                                               |                                                              |

## 5. Table: AugustusSwapperOld\_v1\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 6. Table: AugustusSwapperOld\_v1\_event\_WhitelistAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-18 16:35:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8765971                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9e54b43da8767a6d821b21f8f939869f7b7bad7fb709e4da958214e7dd4c5ff7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b158039b9678b7452f311deb12dd08c579dad26                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         |                                                              |

## 7. Table: AugustusSwapperOld\_v1\_event\_WhitelistRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 8. Table: AugustusSwapperOld\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-12 11:18:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8920121                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x009e67cc6064068101864cd3b50b7e57c887acbf792ecb9623f9e69afe3ba1be | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72338b82800400f5488eca2b5a37270ba3b7a111                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x60fb0b38ff0fcb98462e70aa5da4dff047635ec3                         |                                                              |

## 9. Table: AugustusSwapperOld\_v2\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-17 18:58:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9121967                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcee378c5f982fb085a0200de97a4981a05b158b18959d127faa9c4a1d33fb59a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 141                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72338b82800400f5488eca2b5a37270ba3b7a111                         | Address of the contract that produced the log                |

## 10. Table: AugustusSwapperOld\_v2\_event\_Payed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-26 13:51:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9004520                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9057966f669b134847f5038addfc6244958cac8cf8aaf4b929025d5d193d9d8a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72338b82800400f5488eca2b5a37270ba3b7a111                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x0d54aadd7ce2dc10eb9527c6105a3c3f1b463d1b                         |                                                              |
| srcToken          | VARCHAR   | 0x57ab1ec28d129707052df4df418d58a2d46d5f51                         |                                                              |
| destToken         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| srcAmount         | VARCHAR   | 31000000000000000000                                               |                                                              |
| receivedAmount    | VARCHAR   | 204031803775541668                                                 |                                                              |

## 11. Table: AugustusSwapperOld\_v2\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-20 00:49:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8965490                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb632b1078db91cec7a4d15ba1826505cc17bb953b24798058b8d8756364464b0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72338b82800400f5488eca2b5a37270ba3b7a111                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xbf83e6e40162c655f2ded3431b7b31307275ac95                         |                                                              |
| srcToken          | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| destToken         | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| srcAmount         | VARCHAR   | 1157640952515000000000                                             |                                                              |
| receivedAmount    | VARCHAR   | 1157640952515000000000                                             |                                                              |

## 12. Table: AugustusSwapperOld\_v2\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-20 07:26:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9134559                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43d1133c6e58eb5199bb2ccdb316ee5c2f29c1aee0db0e4e9660cf8a7b57fb60 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72338b82800400f5488eca2b5a37270ba3b7a111                         | Address of the contract that produced the log                |

## 13. Table: AugustusSwapperOld\_v2\_event\_WhitelistAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-21 15:34:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8975156                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbd5699d2e36d63e2b2dda1be810bcf7caa3491f9c63962209f3e278582c058af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72338b82800400f5488eca2b5a37270ba3b7a111                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x493c57c4763932315a328269e1adad09653b9081                         |                                                              |

## 14. Table: AugustusSwapperOld\_v2\_event\_WhitelistRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-27 09:22:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9009082                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf7698ba80f0b70809ffe8067e58d6d370034fca29c635bc0ebd5901f89c526b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72338b82800400f5488eca2b5a37270ba3b7a111                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x93ed3fbe21207ec2e8f2d3c3de6e058cb73bc04d                         |                                                              |

## 15. Table: AugustusSwapperOld\_v3\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-29 10:20:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10160102                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ac38e00e3e46c9575ad8b889852ce84289a1cb029217465abe59e88fddc822e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf92c1ad75005e6436b4ee84e88cb23ed8a290988                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x60fb0b38ff0fcb98462e70aa5da4dff047635ec3                         |                                                              |
| newOwner          | VARCHAR   | 0xe6b692dcc972b9a5c3c414ac75ddc420b9edc92d                         |                                                              |

## 16. Table: AugustusSwapperOld\_v3\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 17. Table: AugustusSwapperOld\_v3\_event\_Payed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-05 11:54:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9220224                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80cb629c88eeeaa3b9c43d77af908faaf70fb75d548b307b3bc5cc790caab741 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf92c1ad75005e6436b4ee84e88cb23ed8a290988                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x0ab80a44f98fb40d95ad7cc595802f03cbab92aa                         |                                                              |
| srcToken          | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| destToken         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| srcAmount         | VARCHAR   | 4083012164199828409                                                |                                                              |
| receivedAmount    | VARCHAR   | 30020373005539009                                                  |                                                              |
| referrer          | VARCHAR   | paraswap.io                                                        |                                                              |

## 18. Table: AugustusSwapperOld\_v3\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-28 11:20:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9175547                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85682f371b5615dcf164c04d3abb613ff9ee87865787b4b0aa2e7dd7d5b4a45d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf92c1ad75005e6436b4ee84e88cb23ed8a290988                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0951ff0835302929d6c0162b3d2495a85e38ec3a                         |                                                              |
| srcToken          | VARCHAR   | 0x0f5d2fb29fb7d3cfee444a200298f468908cc942                         |                                                              |
| destToken         | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| srcAmount         | VARCHAR   | 39357259912489128578567                                            |                                                              |
| receivedAmount    | VARCHAR   | 1297046611895794441235                                             |                                                              |
| referrer          | VARCHAR   | paraswap.io                                                        |                                                              |

## 19. Table: AugustusSwapperOld\_v3\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 20. Table: AugustusSwapperOld\_v3\_event\_WhitelistAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-18 01:50:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9123364                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcd33d827b780e2bee262bacea8b102d231122d6a673e4876662ca6492e37e82f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 163                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf92c1ad75005e6436b4ee84e88cb23ed8a290988                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x3e0349f5d38414008b9bb1907ea422739be7cd4c                         |                                                              |

## 21. Table: AugustusSwapperOld\_v3\_event\_WhitelistRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 22. Table: AugustusSwapper\_v1\_event\_Donation\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| receiver           | VARCHAR   |                                                              |             |
| donationPercentage | VARCHAR   |                                                              |             |

## 23. Table: AugustusSwapper\_v1\_event\_FeeTaken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 01:53:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10922420                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x304a508e1b041a1ed1cc8265c5e634bbabc672a10d4c9ae99f4fa429c9f56218 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86969d29f5fd327e1009ba66072be22db6017cc6                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 12106328                                                           |                                                              |
| partnerShare      | VARCHAR   | 9685062                                                            |                                                              |
| paraswapShare     | VARCHAR   | 2421266                                                            |                                                              |

## 24. Table: AugustusSwapper\_v1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-29 14:20:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10161180                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6c3714265dcdd0cdeecce91ecea96ed994355a11e918b4c00d66750e993863f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86969d29f5fd327e1009ba66072be22db6017cc6                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xe6b692dcc972b9a5c3c414ac75ddc420b9edc92d                         |                                                              |

## 25. Table: AugustusSwapper\_v1\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 26. Table: AugustusSwapper\_v1\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-25 12:13:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10931749                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c91fa1b0e2775c41077b880869937ae233da317453ea8e94dc275ec8cda696d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86969d29f5fd327e1009ba66072be22db6017cc6                         | Address of the contract that produced the log                |
| initiator         | VARCHAR   | 0xbf0bc7c280af83ecb51d1333bef568656a29b752                         |                                                              |
| beneficiary       | VARCHAR   | 0xbf0bc7c280af83ecb51d1333bef568656a29b752                         |                                                              |
| srcToken          | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| destToken         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| srcAmount         | VARCHAR   | 775000000000000000000                                              |                                                              |
| receivedAmount    | VARCHAR   | 2297653576978345171                                                |                                                              |
| expectedAmount    | VARCHAR   | 2297653576978345200                                                |                                                              |
| referrer          | VARCHAR   | monolith                                                           |                                                              |

## 27. Table: AugustusSwapper\_v1\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 28. Table: AugustusSwapper\_v2\_event\_Bought\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-29 22:23:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11753455                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8985fcc1a90febc7339f3eaf649459c7c6782e72dab1532f4972a1c21f73221e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9509665d015bfe3c77aa5ad6ca20c8afa1d98989                         | Address of the contract that produced the log                |
| initiator         | VARCHAR   | 0xdac7a91516112703448b5d1fbc8b679fce838e8a                         |                                                              |
| beneficiary       | VARCHAR   | 0xdac7a91516112703448b5d1fbc8b679fce838e8a                         |                                                              |
| srcToken          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| destToken         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| srcAmount         | VARCHAR   | 27270000000000000                                                  |                                                              |
| receivedAmount    | VARCHAR   | 26930648678207736                                                  |                                                              |
| expectedAmount    | VARCHAR   | 27000000000000000                                                  |                                                              |
| referrer          | VARCHAR   | mooni                                                              |                                                              |

## 29. Table: AugustusSwapper\_v2\_event\_Donation\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| receiver            | VARCHAR   |                                                              |             |
| donationBasisPoints | VARCHAR   |                                                              |             |

## 30. Table: AugustusSwapper\_v2\_event\_FeeTaken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-10 11:43:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11424982                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x111ecfb8768436a9eb6d586fbcd301d43d4011be5985fae0f7698abbf6b50979 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9509665d015bfe3c77aa5ad6ca20c8afa1d98989                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 22211253801718988695                                               |                                                              |
| partnerShare      | VARCHAR   | 18879565731461140390                                               |                                                              |
| paraswapShare     | VARCHAR   | 3331688070257848305                                                |                                                              |

## 31. Table: AugustusSwapper\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-28 18:02:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10952443                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb68834802635974dfdd97663386f0960172c31e01384c3f0c68c5aa9676bac01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9509665d015bfe3c77aa5ad6ca20c8afa1d98989                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xe6b692dcc972b9a5c3c414ac75ddc420b9edc92d                         |                                                              |

## 32. Table: AugustusSwapper\_v2\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-30 10:43:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13326600                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x369fe2ffc7a5f203cb666d8d537955b76595e42606565a91b5a7cf97a4f72a97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9509665d015bfe3c77aa5ad6ca20c8afa1d98989                         | Address of the contract that produced the log                |

## 33. Table: AugustusSwapper\_v2\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-23 16:34:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11712917                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7df73bdccee065ca00420e1e4cfb34204f21bf8b853b0fc5cf8ea9bc029249d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9509665d015bfe3c77aa5ad6ca20c8afa1d98989                         | Address of the contract that produced the log                |
| initiator         | VARCHAR   | 0xfa7a70294cd364f4c2e3c9d9f5436715569f4d80                         |                                                              |
| beneficiary       | VARCHAR   | 0xfa7a70294cd364f4c2e3c9d9f5436715569f4d80                         |                                                              |
| srcToken          | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| destToken         | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| srcAmount         | VARCHAR   | 15300000000                                                        |                                                              |
| receivedAmount    | VARCHAR   | 15289832261546071862211                                            |                                                              |
| expectedAmount    | VARCHAR   | 15213383100238341640000                                            |                                                              |
| referrer          | VARCHAR   | argent                                                             |                                                              |

## 34. Table: AugustusSwapper\_v2\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 35. Table: AugustusSwapper\_v3\_event\_Bought\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-10 14:09:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12011240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcac880a3d98838f3bc91f350fb4956497cef9412436d873a40507d52408ed931 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf90e98f3d8dce44632e5020abf2e122e0f99dfab                         | Address of the contract that produced the log                |
| initiator         | VARCHAR   | 0xd58919830be1833052b8321021218f10d80d088d                         |                                                              |
| beneficiary       | VARCHAR   | 0xd58919830be1833052b8321021218f10d80d088d                         |                                                              |
| srcToken          | VARCHAR   | 0xb753428af26e81097e7fd17f40c88aaa3e04902c                         |                                                              |
| destToken         | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| srcAmount         | VARCHAR   | 56519674716920103                                                  |                                                              |
| receivedAmount    | VARCHAR   | 69170792482815135                                                  |                                                              |
| referrer          | VARCHAR   | mooni                                                              |                                                              |

## 36. Table: AugustusSwapper\_v3\_event\_FeeTaken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-18 02:59:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12261550                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x306a26bfc636a63a4866a674e54574dbedc26ed1910a5849527818dc5c56da48 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf90e98f3d8dce44632e5020abf2e122e0f99dfab                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 3290983994                                                         |                                                              |
| partnerShare      | VARCHAR   | 2734742388                                                         |                                                              |
| paraswapShare     | VARCHAR   | 556241606                                                          |                                                              |

## 37. Table: AugustusSwapper\_v3\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-22 21:33:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11707760                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe68312f67cf4ec749441e18c8669130c42462e518c9f7b385ab4f9a1b4d053ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf90e98f3d8dce44632e5020abf2e122e0f99dfab                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xe6b692dcc972b9a5c3c414ac75ddc420b9edc92d                         |                                                              |

## 38. Table: AugustusSwapper\_v3\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-30 10:40:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13326584                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe205f49233044ded5b401ba4e4496a0dddc6952c205609dddc02323cc8933fe7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf90e98f3d8dce44632e5020abf2e122e0f99dfab                         | Address of the contract that produced the log                |

## 39. Table: AugustusSwapper\_v3\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-06 17:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12187553                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1309314bb0163ca58c5429cf4d3fbdabd602465e1e9b1a4a766d3faa36b00f70 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 221                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf90e98f3d8dce44632e5020abf2e122e0f99dfab                         | Address of the contract that produced the log                |
| initiator         | VARCHAR   | 0xe0ded48d632cf455c2893a9891d983fffff22ce8                         |                                                              |
| beneficiary       | VARCHAR   | 0xe0ded48d632cf455c2893a9891d983fffff22ce8                         |                                                              |
| srcToken          | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| destToken         | VARCHAR   | 0x000000000000d0151e748d25b766e77efe2a6c83                         |                                                              |
| srcAmount         | VARCHAR   | 2100000000000000000                                                |                                                              |
| receivedAmount    | VARCHAR   | 5614942062046995701550                                             |                                                              |
| expectedAmount    | VARCHAR   | 5614942062046995000000                                             |                                                              |
| referrer          | VARCHAR   | paraswap.io                                                        |                                                              |

## 40. Table: AugustusSwapper\_v3\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
