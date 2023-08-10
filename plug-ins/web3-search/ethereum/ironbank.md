# ironbank

## 1. Table: Unitroller\_event\_MarketListed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-11 11:45:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12412970                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x584ca6798d6da299ccaa52685ae85840be2a9a80cb20befdde16ce921b54fa0b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xab1c342c7bf5ec5f02adea1c2270670bca144cbb                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0x226f3738238932ba0db2319a8117d9555446102f                         |                                                              |

## 2. Table: cToken\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-12-04 13:23:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13740034                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x3195691b144e9b922aa7f9f9eaf216cfcd50fb5b84caf960f59a6cc83d93b194 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 607                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xa8caea564811af0e92b1e044f3edd18fa9a73e4f                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 18286236                                                           |                                                              |
| interestAccumulated | VARCHAR   | 5994                                                               |                                                              |
| borrowIndex         | VARCHAR   | 1025346026534307821                                                |                                                              |
| totalBorrows        | VARCHAR   | 6985423                                                            |                                                              |

## 3. Table: cToken\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 14:01:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932986                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a3bdec498e5e3705c8f823fa8c2f742b9f4db73ac2070b0762b4e1e87fd0fae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 413                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3c9f5385c288ce438ed55620938a4b967c080101                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x38abab9766e0b27d2912718a884292b8e7eb2803                         |                                                              |
| borrowAmount      | VARCHAR   | 100000000000000000000000000                                        |                                                              |
| accountBorrows    | VARCHAR   | 200001545543220476709411980                                        |                                                              |
| totalBorrows      | VARCHAR   | 6127878060154148122102591514                                       |                                                              |

## 4. Table: cToken\_event\_Flashloan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-12 17:12:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13404932                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5f3df6ec9b51e8e88d0d9078b04373742294530b6bcb9be045525fcab71b915 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41c84c0e2ee0b740cf0d31f63f3b6f627dc6b393                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0x949ed86c385d191e96af136e2024d96e467d7651                         |                                                              |
| amount            | VARCHAR   | 808251122417436911                                                 |                                                              |
| totalFee          | VARCHAR   | 242475336725231                                                    |                                                              |
| reservesFee       | VARCHAR   | 36371300508784                                                     |                                                              |

## 5. Table: cToken\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-23 00:26:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14826473                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f8a5a144aeedb138cf30f1cb65250b26d889deb6ed7919611d0cd687f548608 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e595470ed749b85c6f7669de83eae304c2ec68f                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x6ee33c4a192118ea664612aec6f7b6e4aef78b87                         |                                                              |
| borrower          | VARCHAR   | 0x2951b1f7058bd2c05f01954002c450bac0873847                         |                                                              |
| repayAmount       | VARCHAR   | 813838195496945001138                                              |                                                              |
| cTokenCollateral  | VARCHAR   | 0x8e595470ed749b85c6f7669de83eae304c2ec68f                         |                                                              |
| seizeTokens       | VARCHAR   | 8361500211439                                                      |                                                              |

## 6. Table: cToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 22:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16114289                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3fefc0d43b37226f87d293007c3fc0de37b84e0553087eca7f07a9d741ae997 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41c84c0e2ee0b740cf0d31f63f3b6f627dc6b393                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x5a4fe7459620692b4b2f67e6eb8828006a5d2de6                         |                                                              |
| mintAmount        | VARCHAR   | 14000000000000000000                                               |                                                              |
| mintTokens        | VARCHAR   | 130311167827                                                       |                                                              |

## 7. Table: cToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-08 07:44:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15701956                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6687d6a939892f33f12fb374a4b963b505fd8c904821272273288f20141ed428 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x48759f220ed983db51fa7a8c0d2aab8f3ce4166a                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x6853eeef8cabe3e7f4a478b39f1f3fd7e99759b5                         |                                                              |
| redeemAmount      | VARCHAR   | 8184361695                                                         |                                                              |
| redeemTokens      | VARCHAR   | 76716068394475                                                     |                                                              |

## 8. Table: cToken\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-02 16:22:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16542277                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xff25c2c4727f6c0639ebbac3f27bbb808835eddcc6c24206b5f8729327c629df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x226f3738238932ba0db2319a8117d9555446102f                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xc029784f0b3cced83c9f98fdb857989b4fb9d1e7                         |                                                              |
| borrower          | VARCHAR   | 0x4583dffaa7a5e0302232313681561402910cf2f8                         |                                                              |
| repayAmount       | VARCHAR   | 2526452192219087438239                                             |                                                              |
| accountBorrows    | VARCHAR   | 2526452192219087438240                                             |                                                              |
| totalBorrows      | VARCHAR   | 6811124034448587469353                                             |                                                              |

## 9. Table: cToken\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| benefactor        | VARCHAR   |                                                              |             |
| addAmount         | VARCHAR   |                                                              |             |
| newTotalReserves  | VARCHAR   |                                                              |             |

## 10. Table: cToken\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-06 07:37:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17633367                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x361116476e88be9664bc50156914a5eb2ae486d13e4f5416605afe3cd0be8bcf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41c84c0e2ee0b740cf0d31f63f3b6f627dc6b393                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x1145ed8549fc5a49ace3f01354a05d03058fef24                         |                                                              |
| reduceAmount      | VARCHAR   | 1120690377644915126                                                |                                                              |
| newTotalReserves  | VARCHAR   | 16843732642368674926                                               |                                                              |

## 11. Table: cToken\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
