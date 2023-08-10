# damm

## 1. Table: CErc20Delegate\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-06-01 13:22:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17386226                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x4b70935428d952df0b43d06add67f999818f9061dc4079a87a74d5f781f07caf | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x07e87bf536c4b791fe9f5ffa921ad8812ae1c079                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 1555422840234348344322527                                          |                                                              |
| interestAccumulated | VARCHAR   | 0                                                                  |                                                              |
| borrowIndex         | VARCHAR   | 1000000000000000000                                                |                                                              |
| totalBorrows        | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: CErc20Delegate\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 3. Table: CErc20Delegate\_event\_Borrow\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| borrower          | VARCHAR   |                                                              |             |
| borrowAmount      | VARCHAR   |                                                              |             |
| accountBorrows    | VARCHAR   |                                                              |             |
| totalBorrows      | VARCHAR   |                                                              |             |

## 4. Table: CErc20Delegate\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| liquidator        | VARCHAR   |                                                              |             |
| borrower          | VARCHAR   |                                                              |             |
| repayAmount       | VARCHAR   |                                                              |             |
| cTokenCollateral  | VARCHAR   |                                                              |             |
| seizeTokens       | VARCHAR   |                                                              |             |

## 5. Table: CErc20Delegate\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-20 06:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16009483                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf24766df3528aa241825f3ab756cfeeadd539a84803a7e4de6c265fe77a42b5b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07e87bf536c4b791fe9f5ffa921ad8812ae1c079                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x8a475e09de4bec7ebe8bbd411633d08f27acb23b                         |                                                              |
| mintAmount        | VARCHAR   | 870000000000000000                                                 |                                                              |
| mintTokens        | VARCHAR   | 86999999                                                           |                                                              |

## 6. Table: CErc20Delegate\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 7. Table: CErc20Delegate\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-11 01:57:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15943641                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c3d092c1a41aca34b945309b1ecd0091fedfb6f914f14f3e96cfb954fc2a336 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 308                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07e87bf536c4b791fe9f5ffa921ad8812ae1c079                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0xf6dfbbf912799e2426bae13a918cb17f0e965c3c                         |                                                              |

## 8. Table: CErc20Delegate\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-11-11 01:57:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 15943641                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x4c3d092c1a41aca34b945309b1ecd0091fedfb6f914f14f3e96cfb954fc2a336 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 309                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x07e87bf536c4b791fe9f5ffa921ad8812ae1c079                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0x99094979cf6971e687b779dae012bb870349acf4                         |                                                              |

## 9. Table: CErc20Delegate\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 10. Table: CErc20Delegate\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                      | Description |
| ------------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp         | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number            | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash        | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index               | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address        | VARCHAR   | Address of the contract that produced the log                |             |
| oldReserveFactorMantissa | VARCHAR   |                                                              |             |
| newReserveFactorMantissa | VARCHAR   |                                                              |             |

## 11. Table: CErc20Delegate\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-23 08:44:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16889137                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3857722ff8e3ed8024eb0ee0c246cb5f18cbd2c544f9b46f6100fcbf7e391349 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07e87bf536c4b791fe9f5ffa921ad8812ae1c079                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x7dff6ddc5f307ec1421ffb086bb7a0a91154754c                         |                                                              |
| redeemAmount      | VARCHAR   | 12178230000007098090749                                            |                                                              |
| redeemTokens      | VARCHAR   | 1217822999998                                                      |                                                              |

## 12. Table: CErc20Delegate\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| payer             | VARCHAR   |                                                              |             |
| borrower          | VARCHAR   |                                                              |             |
| repayAmount       | VARCHAR   |                                                              |             |
| accountBorrows    | VARCHAR   |                                                              |             |
| totalBorrows      | VARCHAR   |                                                              |             |

## 13. Table: CErc20Delegate\_event\_ReservesAdded\_history

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

## 14. Table: CErc20Delegate\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| admin             | VARCHAR   |                                                              |             |
| reduceAmount      | VARCHAR   |                                                              |             |
| newTotalReserves  | VARCHAR   |                                                              |             |

## 15. Table: CErc20Delegate\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-29 20:29:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16078037                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a8667ee8eaaadaeeb349d82264d1cf1d70d4c7678d2b3464291bd7ef675ed7a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07e87bf536c4b791fe9f5ffa921ad8812ae1c079                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x07e87bf536c4b791fe9f5ffa921ad8812ae1c079                         |                                                              |
| to                | VARCHAR   | 0x79a68d37b2767c6d936d91003dee68da129372a9                         |                                                              |
| amount            | VARCHAR   | 16496118542                                                        |                                                              |

## 16. Table: CErc20Delegator\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-11 01:57:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15943641                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c3d092c1a41aca34b945309b1ecd0091fedfb6f914f14f3e96cfb954fc2a336 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07e87bf536c4b791fe9f5ffa921ad8812ae1c079                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newImplementation | VARCHAR   | 0x8c22cd2b93f06a37f81384afec62193957bb50e0                         |                                                              |

## 17. Table: ComptrollerG7\_event\_ActionPaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-04 09:15:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15673816                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf932e4b3db79c9a12c8c4b51cffb2c40d95f29dea1c700d9e7b3ea330dd8f135 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 535                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f96ab61520a6636331a48a11eafba8fb51f74e4                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0xa9045052affceff7cab7e06f9afa200c4497c2bf                         |                                                              |
| action            | VARCHAR   | Mint                                                               |                                                              |
| pauseState        | VARCHAR   | true                                                               |                                                              |

## 18. Table: ComptrollerG7\_event\_BorrowerLimitChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-03 21:19:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15892130                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20a30163cf5d56b1f5311960f0497accc3802baecf18c318e37f41eef9a44d88 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 332                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f96ab61520a6636331a48a11eafba8fb51f74e4                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x1c1446310ce96bba0e961ef48a0ec881898b5687                         |                                                              |
| borrowLimit       | VARCHAR   | 800000000000000000000000                                           |                                                              |

## 19. Table: ComptrollerG7\_event\_BorrowerWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-23 21:38:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16472245                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x283616a4fa4ddab94273a0422a93e953540e651f12fe4fdc316d72f022335d64 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 353                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f96ab61520a6636331a48a11eafba8fb51f74e4                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xaff9d9be9b9526c67e537844818e761d40166af8                         |                                                              |

## 20. Table: ComptrollerG7\_event\_CompGranted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| recipient         | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 21. Table: ComptrollerG7\_event\_CompSpeedUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-11 23:13:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15728077                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3abcadc0ffde9c6e00df705c48aa8b3781fe96ca03628d1cf8b5c25eb1e8476e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f96ab61520a6636331a48a11eafba8fb51f74e4                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0x2878a6982a3cdb9d57e821ecc7ba1cfb335144ff                         |                                                              |
| newSpeed          | VARCHAR   | 0                                                                  |                                                              |

## 22. Table: ComptrollerG7\_event\_ContributorCompSpeedUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| contributor       | VARCHAR   |                                                              |             |
| newSpeed          | VARCHAR   |                                                              |             |

## 23. Table: ComptrollerG7\_event\_DistributedBorrowerComp\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-31 13:43:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15868417                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc518d0068a6ab11ff62419ef1fcaa87e3857cb85c45cdd6b6f79ced9a36322e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f96ab61520a6636331a48a11eafba8fb51f74e4                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0xa3006250a22e1ca3c3f19fd1fb080c5dc65992c5                         |                                                              |
| borrower          | VARCHAR   | 0x343dff3a1692a674f5dd6a5515d2d2184d20efae                         |                                                              |
| compDelta         | VARCHAR   | 0                                                                  |                                                              |
| compBorrowIndex   | VARCHAR   | 337073131148197360645437154181393257124844038188                   |                                                              |

## 24. Table: ComptrollerG7\_event\_DistributedSupplierComp\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 21:27:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16658183                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9deb7c443bca391151982e29b66368103c3012b1677d3bd1a52fce72d9048b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f96ab61520a6636331a48a11eafba8fb51f74e4                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0xa3006250a22e1ca3c3f19fd1fb080c5dc65992c5                         |                                                              |
| supplier          | VARCHAR   | 0x4dd74e17cd0ce65d1fa6aa27c20fe678221ba01a                         |                                                              |
| compDelta         | VARCHAR   | 1101663290525254044184                                             |                                                              |
| compSupplyIndex   | VARCHAR   | 662956664711893522426799904492003794354129280                      |                                                              |

## 25. Table: ComptrollerG7\_event\_Failure\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| error             | VARCHAR   |                                                              |             |
| info              | VARCHAR   |                                                              |             |
| detail            | VARCHAR   |                                                              |             |

## 26. Table: ComptrollerG7\_event\_MarketEntered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 20:22:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15492369                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ac855de5c820ff9ee7026550a4d2cb4eda8fe9c3cf6ceabef73343c0c9a12cf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 477                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f96ab61520a6636331a48a11eafba8fb51f74e4                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0xa3006250a22e1ca3c3f19fd1fb080c5dc65992c5                         |                                                              |
| account           | VARCHAR   | 0x11eff12a14afc54247ee84a7f832e70331fe7919                         |                                                              |

## 27. Table: ComptrollerG7\_event\_MarketExited\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cToken            | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |

## 28. Table: ComptrollerG7\_event\_MarketListed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-04 02:47:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15671896                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b6ae6eaee16593a143cf6103085dd6214f93f3c89f549b16a0fbf027842cf5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 299                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f96ab61520a6636331a48a11eafba8fb51f74e4                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0xd2715f392871a4117a6ffaaf6cf43df33f154eef                         |                                                              |

## 29. Table: ComptrollerG7\_event\_NewBorrowCapGuardian\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| oldBorrowCapGuardian | VARCHAR   |                                                              |             |
| newBorrowCapGuardian | VARCHAR   |                                                              |             |

## 30. Table: ComptrollerG7\_event\_NewBorrowCap\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cToken            | VARCHAR   |                                                              |             |
| newBorrowCap      | VARCHAR   |                                                              |             |

## 31. Table: ComptrollerG7\_event\_NewCloseFactor\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| oldCloseFactorMantissa | VARCHAR   |                                                              |             |
| newCloseFactorMantissa | VARCHAR   |                                                              |             |

## 32. Table: ComptrollerG7\_event\_NewCollateralFactor\_history

| Column                      | Type      | Example                                                      | Description |
| --------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp            | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number               | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash           | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                  | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address           | VARCHAR   | Address of the contract that produced the log                |             |
| cToken                      | VARCHAR   |                                                              |             |
| oldCollateralFactorMantissa | VARCHAR   |                                                              |             |
| newCollateralFactorMantissa | VARCHAR   |                                                              |             |

## 33. Table: ComptrollerG7\_event\_NewLiquidationIncentive\_history

| Column                          | Type      | Example                                                      | Description |
| ------------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number                   | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash               | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                      | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address               | VARCHAR   | Address of the contract that produced the log                |             |
| oldLiquidationIncentiveMantissa | VARCHAR   |                                                              |             |
| newLiquidationIncentiveMantissa | VARCHAR   |                                                              |             |

## 34. Table: ComptrollerG7\_event\_NewPauseGuardian\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPauseGuardian  | VARCHAR   |                                                              |             |
| newPauseGuardian  | VARCHAR   |                                                              |             |
