# stakehound

## 1. Table: StakedTokenV2\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-08 09:58:46+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12392969                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78e08ec35af77ec8a1779040e970ca66ecc2a112fcd573d62873f5944db5f8a6             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe66b14d37c77f4e9b180ceb433d1b164f0281d                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x73eb7a4756ef34b903d8f0d320138fa4f2e4ec5b                                     |                                                              |
| spender           | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: StakedTokenV2\_event\_Blacklisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-03 11:42:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12561358                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x52cb9ac1813a7aee5d0c553a9f58480e0ab7766d5bb4158f2f2c4007284a1bd4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe66b14d37c77f4e9b180ceb433d1b164f0281d                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xc510f9f7ff9b8469986c955d3ccb0a805817e84e                         |                                                              |
| isBlacklisted     | VARCHAR   | true                                                               |                                                              |

## 3. Table: StakedTokenV2\_event\_LogSupplyControllerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-20 17:55:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11296444                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe27316c7db6038f70a53b137d8eb05dd403404f830dd301a3b972aee5a826b5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 207                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe66b14d37c77f4e9b180ceb433d1b164f0281d                         | Address of the contract that produced the log                |
| supplyController  | VARCHAR   | 0x314f8e805b347af013cd952e0929cb573abbf4d1                         |                                                              |

## 4. Table: StakedTokenV2\_event\_LogTokenDistribution\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-02 21:24:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12357175                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x01f2fed19569e445319617498f872023a4f3dd4cf9bc10280abc2256d6af1e26 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe66b14d37c77f4e9b180ceb433d1b164f0281d                         | Address of the contract that produced the log                |
| oldTotalSupply    | VARCHAR   | 64054347667934379884378                                            |                                                              |
| supplyChange      | VARCHAR   | 12119777100710631113                                               |                                                              |
| positive          | VARCHAR   | true                                                               |                                                              |
| newTotalSupply    | VARCHAR   | 64066467445035090515491                                            |                                                              |

## 5. Table: StakedTokenV2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-20 17:26:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11296329                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4d95a267593582d19a119bf640c559ed07a01aed420c9e65daacec923a7f131d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe66b14d37c77f4e9b180ceb433d1b164f0281d                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x0b0b977facc378365e9aedbe0bc28ee6cd7f09ed                         |                                                              |

## 6. Table: StakedTokenV2\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-10 21:00:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12408971                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a520a61804848221893e63e41b67261929debac213a8043277900ec167fab5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 347                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe66b14d37c77f4e9b180ceb433d1b164f0281d                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe14ce18903b0d3678a098f3bdeda0aac3790ac3b                         |                                                              |

## 7. Table: StakedTokenV2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 16:46:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14755975                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd8b80f98a9467bdfcc4415696a7fbf13162d69bef6e3ac67155193371271801c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 669                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe66b14d37c77f4e9b180ceb433d1b164f0281d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xdb31651967684a40a05c4ab8ec56fc32f060998d                         |                                                              |
| to                | VARCHAR   | 0xef22c14f46858d5ac61326497b056974167f2ee1                         |                                                              |
| value             | VARCHAR   | 10231274715236232856804                                            |                                                              |

## 8. Table: StakedTokenV2\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-22 13:40:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12684347                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6ded0a76aa450a5189ef3793725dbdecf633584b516a0040d12f0f44699f9d62 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 275                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdfe66b14d37c77f4e9b180ceb433d1b164f0281d                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe14ce18903b0d3678a098f3bdeda0aac3790ac3b                         |                                                              |

## 9. Table: StakedTokenV2\_event\_WarningMaxExpectedSupplyExceeded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| totalSupply       | VARCHAR   |                                                              |             |
| totalShares       | VARCHAR   |                                                              |             |
