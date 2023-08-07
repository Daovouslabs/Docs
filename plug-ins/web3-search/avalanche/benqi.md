# benqi

## 1. Table: Comptroller\_event\_ActionPaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| qiToken           | VARCHAR   |                                                              |             |
| action            | VARCHAR   |                                                              |             |
| pauseState        | VARCHAR   |                                                              |             |

## 2. Table: Comptroller\_event\_BorrowRewardSpeedUpdated\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| rewardToken          | VARCHAR   |                                                              |             |
| qiToken              | VARCHAR   |                                                              |             |
| newBorrowRewardSpeed | VARCHAR   |                                                              |             |

## 3. Table: Comptroller\_event\_ContributorQiSpeedUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| contributor       | VARCHAR   |                                                              |             |
| newSpeed          | VARCHAR   |                                                              |             |

## 4. Table: Comptroller\_event\_DistributedBorrowerReward\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tokenType         | VARCHAR   |                                                              |             |
| qiToken           | VARCHAR   |                                                              |             |
| borrower          | VARCHAR   |                                                              |             |
| qiDelta           | VARCHAR   |                                                              |             |
| qiBorrowIndex     | VARCHAR   |                                                              |             |

## 5. Table: Comptroller\_event\_DistributedSupplierReward\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| tokenType         | VARCHAR   |                                                              |             |
| qiToken           | VARCHAR   |                                                              |             |
| borrower          | VARCHAR   |                                                              |             |
| qiDelta           | VARCHAR   |                                                              |             |
| qiBorrowIndex     | VARCHAR   |                                                              |             |

## 6. Table: Comptroller\_event\_Failure\_history

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

## 7. Table: Comptroller\_event\_MarketEntered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| qiToken           | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |

## 8. Table: Comptroller\_event\_MarketExited\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| qiToken           | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |

## 9. Table: Comptroller\_event\_MarketListed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| qiToken           | VARCHAR   |                                                              |             |

## 10. Table: Comptroller\_event\_NewBorrowCapGuardian\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| oldBorrowCapGuardian | VARCHAR   |                                                              |             |
| newBorrowCapGuardian | VARCHAR   |                                                              |             |

## 11. Table: Comptroller\_event\_NewBorrowCap\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| qiToken           | VARCHAR   |                                                              |             |
| newBorrowCap      | VARCHAR   |                                                              |             |

## 12. Table: Comptroller\_event\_NewCloseFactor\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| oldCloseFactorMantissa | VARCHAR   |                                                              |             |
| newCloseFactorMantissa | VARCHAR   |                                                              |             |

## 13. Table: Comptroller\_event\_NewCollateralFactor\_history

| Column                      | Type      | Example                                                      | Description |
| --------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp            | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number               | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash           | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                  | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address           | VARCHAR   | Address of the contract that produced the log                |             |
| qiToken                     | VARCHAR   |                                                              |             |
| oldCollateralFactorMantissa | VARCHAR   |                                                              |             |
| newCollateralFactorMantissa | VARCHAR   |                                                              |             |

## 14. Table: Comptroller\_event\_NewLiquidationIncentive\_history

| Column                          | Type      | Example                                                      | Description |
| ------------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number                   | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash               | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                      | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address               | VARCHAR   | Address of the contract that produced the log                |             |
| oldLiquidationIncentiveMantissa | VARCHAR   |                                                              |             |
| newLiquidationIncentiveMantissa | VARCHAR   |                                                              |             |

## 15. Table: Comptroller\_event\_NewPauseGuardian\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPauseGuardian  | VARCHAR   |                                                              |             |
| newPauseGuardian  | VARCHAR   |                                                              |             |

## 16. Table: Comptroller\_event\_NewPriceOracle\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPriceOracle    | VARCHAR   |                                                              |             |
| newPriceOracle    | VARCHAR   |                                                              |             |

## 17. Table: Comptroller\_event\_QiGranted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| recipient         | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 18. Table: Comptroller\_event\_SupplyRewardSpeedUpdated\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| rewardToken          | VARCHAR   |                                                              |             |
| qiToken              | VARCHAR   |                                                              |             |
| newSupplyRewardSpeed | VARCHAR   |                                                              |             |

## 19. Table: QiToken\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-06-24 05:46:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 16443164                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xbb776824a0255f4ffb4cc900cdc475ca80557f45237959f82ad17be9681f1989 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xe194c4c5ac32a3c9ffdb358d9bfd523a0b6d1568                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 157946529919                                                       |                                                              |
| interestAccumulated | VARCHAR   | 621                                                                |                                                              |
| borrowIndex         | VARCHAR   | 1040701217275885623                                                |                                                              |
| totalBorrows        | VARCHAR   | 7169032176                                                         |                                                              |

## 20. Table: QiToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 19:56:57+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33581457                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3394d9cedbeb108532283ea6f28c442afafa9567e66780c33d053d71c8a733c2             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf362fea9659cf036792c9cb02f8ff8198e21b4cb                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x5cd9316d611a73e3b5c0e96503dd9d7cde45910b                                     |                                                              |
| spender           | VARCHAR   | 0xe7a5b5783bee4c91c2bdfb00ff5a34426b6b8a02                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 21. Table: QiToken\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-29 07:47:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29364325                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x991e4f6dae4eea74a1797afbef7482343c59d5dfddd7efa79469be1c8a31d8c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x334ad834cd4481bb02d09615e7c11a00579a7909                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x37749f66f360d9de7b8b1f7928d839aa52ab2f91                         |                                                              |
| borrowAmount      | VARCHAR   | 1000000000000000000                                                |                                                              |
| accountBorrows    | VARCHAR   | 1778136926181358983                                                |                                                              |
| totalBorrows      | VARCHAR   | 377637061066271125098                                              |                                                              |

## 22. Table: QiToken\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-24 19:27:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6056957                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x41f7db02d55c8d4e093e82857f7ebcbeb0a5a828276409bfe420a8997ab51289 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4e9f683a27a6bdad3fc2764003759277e93696e6                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 74                                                                 |                                                              |
| detail            | VARCHAR   | 4                                                                  |                                                              |

## 23. Table: QiToken\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-25 00:55:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10015738                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8195f36b0bf233e805ad91a3d72adb8ae5b6b9fbc7da93a9a02d560dd233c2a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbeb5d47a3f720ec0a390d04b4d41ed7d9688bc7f                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x4eb4c8fac4854f293de11b6a6faf4647f5dab590                         |                                                              |
| borrower          | VARCHAR   | 0x7f434cd5fa5b6e145b3ef25703ae7dcf775e119c                         |                                                              |
| repayAmount       | VARCHAR   | 62422294791                                                        |                                                              |
| qiTokenCollateral | VARCHAR   | 0x4e9f683a27a6bdad3fc2764003759277e93696e6                         |                                                              |
| seizeTokens       | VARCHAR   | 22227073921393                                                     |                                                              |

## 24. Table: QiToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-15 16:47:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21103211                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x665457ab03a0f3c26f414ff4722b0e92b852ed876db9e2efd61f71e316ce135b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x334ad834cd4481bb02d09615e7c11a00579a7909                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0xdebf59042f51e73ffbcb7cd779ca30f5d24c984f                         |                                                              |
| mintAmount        | VARCHAR   | 38405265710950021                                                  |                                                              |
| mintTokens        | VARCHAR   | 190753719                                                          |                                                              |

## 25. Table: QiToken\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-03 11:39:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14217686                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfda340d05dfeabad0536036f01c1e50adf4fdba5fb0b5cf9bd08c34583c43e5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf362fea9659cf036792c9cb02f8ff8198e21b4cb                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0xf799c20563218190424c3aec6022ce9faf588eb7                         |                                                              |
| newAdmin          | VARCHAR   | 0xb952c860f1296eae87494c7d8a4c96edd43adb3d                         |                                                              |

## 26. Table: QiToken\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-30 13:25:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3620405                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x076cc468043d52f8e52980bcbc14889e4266f05c0c34e0d5c5bb34c8e5742cf0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbeb5d47a3f720ec0a390d04b4d41ed7d9688bc7f                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x486af39519b4dc9a7fccd318217352830e8ad9b4                         |                                                              |

## 27. Table: QiToken\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-10-04 12:00:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 5202368                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xad4790293f44a2a37e68230d784397f56276653b5e5502dcf1a86c6a8b313abc | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x5c0401e81bc07ca70fad469b451682c0d747ef1c                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0xf805e22c81ef330967eec52f7edb0c6b31fd5ccf                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xc436f5bc8a8bd9c9e240a2a83d44705ec87a9d55                         |                                                              |

## 28. Table: QiToken\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-03 11:39:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14217686                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfda340d05dfeabad0536036f01c1e50adf4fdba5fb0b5cf9bd08c34583c43e5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf362fea9659cf036792c9cb02f8ff8198e21b4cb                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0xb952c860f1296eae87494c7d8a4c96edd43adb3d                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 29. Table: QiToken\_event\_NewProtocolSeizeShare\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2022-06-27 08:58:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 16578383                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0x3913789fd76b5e4462b22edb93e1e3a959c20af26ea66b03aa24931ebda5c097 | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x89a415b3d20098e6a6c8f7a59001c67bd3129821                         | Address of the contract that produced the log                |
| oldProtocolSeizeShareMantissa | VARCHAR   | 0                                                                  |                                                              |
| newProtocolSeizeShareMantissa | VARCHAR   | 30000000000000000                                                  |                                                              |

## 30. Table: QiToken\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2022-04-12 11:13:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 13320121                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x2d5b121bd4fe16e54a8425d8b916ab5f9eae234fbc435027c70f235478969696 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xd8fcda6ec4bdc547c0827b8804e89acd817d56ef                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 200000000000000000                                                 |                                                              |

## 31. Table: QiToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-30 05:15:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17980522                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87cd951b2dec65a318adf42afb84592c72f4274565dab3d6dfb2c426416c24cf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x334ad834cd4481bb02d09615e7c11a00579a7909                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x33c002487b41f473af0ecc3bf04358aab56895d5                         |                                                              |
| redeemAmount      | VARCHAR   | 2300000000000000000                                                |                                                              |
| redeemTokens      | VARCHAR   | 11437160330                                                        |                                                              |

## 32. Table: QiToken\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-01 06:29:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10331753                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfebafc426d70b731991ab213201eff70e54474de75295bc673efec13a5f4600c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 30                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc9e5999b8e75c3feb117f6f73e664b9f3c8ca65c                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x01010f15548310bfa5756d32e7e8a19cc4b86ecc                         |                                                              |
| borrower          | VARCHAR   | 0x01010f15548310bfa5756d32e7e8a19cc4b86ecc                         |                                                              |
| repayAmount       | VARCHAR   | 274994020814                                                       |                                                              |
| accountBorrows    | VARCHAR   | 160638868                                                          |                                                              |
| totalBorrows      | VARCHAR   | 111419058741636                                                    |                                                              |

## 33. Table: QiToken\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 04:19:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10591306                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x48e6a80856d6344b7d3a3ebd325641c2922c0e4d1a40f3b6ed5d73d16203a938 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbeb5d47a3f720ec0a390d04b4d41ed7d9688bc7f                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0xbeb5d47a3f720ec0a390d04b4d41ed7d9688bc7f                         |                                                              |
| addAmount         | VARCHAR   | 148232400                                                          |                                                              |
| newTotalReserves  | VARCHAR   | 1359948677897                                                      |                                                              |

## 34. Table: QiToken\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-26 18:43:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3424122                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9a6d08a161a45a56c761e0eae42b841826c4466db7e160f057170edce3490ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5c0401e81bc07ca70fad469b451682c0d747ef1c                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x5423819b3b5bb38b0e9e9e59f22f9034e2d8819b                         |                                                              |
| reduceAmount      | VARCHAR   | 1000000000000000000                                                |                                                              |
| newTotalReserves  | VARCHAR   | 374885900431835029125                                              |                                                              |

## 35. Table: QiToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-03 08:52:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12934678                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaf7a871f327e94dcfaee400e9ec06d71881db1c6e8aca4a08a9da09286c4edc8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35bd6aeda81a7e5fc7a7832490e71f757b0cd9ce                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x038e63469c29e8637f5b3d4def52d31b400037ce                         |                                                              |
| to                | VARCHAR   | 0x35bd6aeda81a7e5fc7a7832490e71f757b0cd9ce                         |                                                              |
| amount            | VARCHAR   | 31428405485735                                                     |                                                              |
