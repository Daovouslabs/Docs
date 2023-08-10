# venus

## 1. Table: Comptroller\_event\_ActionPaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vToken            | VARCHAR   |                                                              |             |
| action            | VARCHAR   |                                                              |             |
| pauseState        | VARCHAR   |                                                              |             |

## 2. Table: Comptroller\_event\_ActionProtocolPaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| state             | VARCHAR   |                                                              |             |

## 3. Table: Comptroller\_event\_DistributedBorrowerVenus\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vToken            | VARCHAR   |                                                              |             |
| borrower          | VARCHAR   |                                                              |             |
| venusDelta        | VARCHAR   |                                                              |             |
| venusBorrowIndex  | VARCHAR   |                                                              |             |

## 4. Table: Comptroller\_event\_DistributedSupplierVenus\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vToken            | VARCHAR   |                                                              |             |
| supplier          | VARCHAR   |                                                              |             |
| venusDelta        | VARCHAR   |                                                              |             |
| venusSupplyIndex  | VARCHAR   |                                                              |             |

## 5. Table: Comptroller\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-03 10:19:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21863612                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83f27548a06d5700755e262b8d62714375d849205c0ff669470dff5f6723302f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf6c14d4dfe45c132822ce28c646753c54994e59c                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 14                                                                 |                                                              |
| info              | VARCHAR   | 3                                                                  |                                                              |
| detail            | VARCHAR   | 9                                                                  |                                                              |

## 6. Table: Comptroller\_event\_MarketEntered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vToken            | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |

## 7. Table: Comptroller\_event\_MarketExited\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vToken            | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |

## 8. Table: Comptroller\_event\_MarketListed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vToken            | VARCHAR   |                                                              |             |

## 9. Table: Comptroller\_event\_MarketVenus\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vToken            | VARCHAR   |                                                              |             |
| isVenus           | VARCHAR   |                                                              |             |

## 10. Table: Comptroller\_event\_NewCloseFactor\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| oldCloseFactorMantissa | VARCHAR   |                                                              |             |
| newCloseFactorMantissa | VARCHAR   |                                                              |             |

## 11. Table: Comptroller\_event\_NewCollateralFactor\_history

| Column                      | Type      | Example                                                      | Description |
| --------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp            | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number               | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash           | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                  | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address           | VARCHAR   | Address of the contract that produced the log                |             |
| vToken                      | VARCHAR   |                                                              |             |
| oldCollateralFactorMantissa | VARCHAR   |                                                              |             |
| newCollateralFactorMantissa | VARCHAR   |                                                              |             |

## 12. Table: Comptroller\_event\_NewLiquidationIncentive\_history

| Column                          | Type      | Example                                                      | Description |
| ------------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number                   | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash               | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                      | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address               | VARCHAR   | Address of the contract that produced the log                |             |
| oldLiquidationIncentiveMantissa | VARCHAR   |                                                              |             |
| newLiquidationIncentiveMantissa | VARCHAR   |                                                              |             |

## 13. Table: Comptroller\_event\_NewMaxAssets\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldMaxAssets      | VARCHAR   |                                                              |             |
| newMaxAssets      | VARCHAR   |                                                              |             |

## 14. Table: Comptroller\_event\_NewPauseGuardian\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPauseGuardian  | VARCHAR   |                                                              |             |
| newPauseGuardian  | VARCHAR   |                                                              |             |

## 15. Table: Comptroller\_event\_NewPriceOracle\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPriceOracle    | VARCHAR   |                                                              |             |
| newPriceOracle    | VARCHAR   |                                                              |             |

## 16. Table: Comptroller\_event\_NewVAIController\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldVAIController  | VARCHAR   |                                                              |             |
| newVAIController  | VARCHAR   |                                                              |             |

## 17. Table: Comptroller\_event\_NewVAIMintRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldVAIMintRate    | VARCHAR   |                                                              |             |
| newVAIMintRate    | VARCHAR   |                                                              |             |

## 18. Table: Comptroller\_event\_NewVenusRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldVenusRate      | VARCHAR   |                                                              |             |
| newVenusRate      | VARCHAR   |                                                              |             |

## 19. Table: Comptroller\_event\_VenusSpeedUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| vToken            | VARCHAR   |                                                              |             |
| newSpeed          | VARCHAR   |                                                              |             |

## 20. Table: VToken\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-11-15 01:39:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 12656974                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x63fb9dd7c7842762d0709d1792bbcecf8974339b58d0cf977e1eebb1fc40a410 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 1323                                                               | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x08ceb3f4a7ed3500ca0982bcd0fc7816688084c3                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 2920365936349463305619042                                          |                                                              |
| interestAccumulated | VARCHAR   | 167061838504353062334                                              |                                                              |
| borrowIndex         | VARCHAR   | 1012375696097521879                                                |                                                              |
| totalBorrows        | VARCHAR   | 18778322463446049014416222                                         |                                                              |

## 21. Table: VToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 09:23:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29865709                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3d1a4e291b84ebee6d0b8690cc8ca1cc0edd825857f0efa2a7e1c621cab4ecc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 284                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfd5840cd36d94d7229439859c0112a4185bc0255                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x4947f35715d97e480508c5d58a4ef44512a56c2b                         |                                                              |
| spender           | VARCHAR   | 0xfd5840cd36d94d7229439859c0112a4185bc0255                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 22. Table: VToken\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-21 10:15:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5871878                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d7d5d24023b9c22173c52abf6bd9e930417cbc20e773102f813ed42348ecdd9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa07c5b74c9b40447a954e1466938b865b6bbea36                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x007e4e679e14f17d62607418f546e2d97d9e5a61                         |                                                              |
| borrowAmount      | VARCHAR   | 1000000000000000000                                                |                                                              |
| accountBorrows    | VARCHAR   | 2000805754434371107                                                |                                                              |
| totalBorrows      | VARCHAR   | 970418459090696221587234                                           |                                                              |

## 23. Table: VToken\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 00:59:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23827456                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6339f0a97565d1717ac28fcf97ba8a61e6d06bdd2c47b00a797f9646bfffe5f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x151b1e2635a717bcdc836ecd6fbb62b674fe3e1d                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 40                                                                 |                                                              |
| detail            | VARCHAR   | 4                                                                  |                                                              |

## 24. Table: VToken\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-13 20:23:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21306131                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdec5fd99522401c37396cdcc75b58230863f9f3d8abde6439ce13c834b4f98f0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x882c173bc7ff3b7786ca16dfed3dfffb9ee7847b                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x9d3a168cf3a54bae225471fc061a77e49c741751                         |                                                              |
| borrower          | VARCHAR   | 0xef044206db68e40520bfa82d45419d498b4bc7bf                         |                                                              |
| repayAmount       | VARCHAR   | 6656229742448348                                                   |                                                              |
| vTokenCollateral  | VARCHAR   | 0x151b1e2635a717bcdc836ecd6fbb62b674fe3e1d                         |                                                              |
| seizeTokens       | VARCHAR   | 157236997225                                                       |                                                              |

## 25. Table: VToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-22 12:42:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16280633                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x572d67c11adc141d2b1dcf23ebb9bac214540dc568f6dc2aacaec42f34bee3ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08ceb3f4a7ed3500ca0982bcd0fc7816688084c3                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0xbbf560b6ed08690c0126f0b7b6e2791e6e552835                         |                                                              |
| mintAmount        | VARCHAR   | 1227824147700051502                                                |                                                              |
| mintTokens        | VARCHAR   | 6029691781                                                         |                                                              |

## 26. Table: VToken\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-25 17:42:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25979347                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x237c5f48ecf7efeab00fe653f53c29561231c3cd6f7c6cff6c843b030fe89d70 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5d3466aa484b040ee977073fcf337f2c00071c1                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0x55a9f5374af30e3045fb491f1da3c2e8a74d168d                         |                                                              |
| newAdmin          | VARCHAR   | 0x939bd8d64c0a9583a7dcea9933f7b21697ab6396                         |                                                              |

## 27. Table: VToken\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-22 01:16:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6773712                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x59f7876d6f4ec5edf4766c96042f39ed4cf0ac7b711ecdd0abe425abdbbd297e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 355                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec3422ef92b2fb59e84c8b02ba73f1fe84ed8d71                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0xfd36e2c2a6789db23113685031d7f16329158384                         |                                                              |

## 28. Table: VToken\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 14:46:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29269151                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdd425298d87e1f8c86ed8b21d06a4341039f29eeecda0fefb489193cdd01378f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 655                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08ceb3f4a7ed3500ca0982bcd0fc7816688084c3                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0xf766fc1f685a396ed6b99550a803ef39ec5b4135                         |                                                              |
| newImplementation | VARCHAR   | 0x13f816511384d3534783241ddb5751c4b7a7e148                         |                                                              |

## 29. Table: VToken\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-03-13 15:55:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 26433498                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xd564a17c2fe65c6f90765969e54a7f85fb0a94b8795af149890f3d521cebbd35 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xa07c5b74c9b40447a954e1466938b865b6bbea36                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x1ba3cc62dee8556433efb23f946ab7d6482bbb57                         |                                                              |
| newInterestRateModel | VARCHAR   | 0x1b047f9717154ea5ec59674273d50a137212cbb4                         |                                                              |

## 30. Table: VToken\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 22:00:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17862955                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8539ee6d605dfd9f88c4dc7df515d3064d23b98cdf72ec05687f03fb0ac4b05e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 417                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x78366446547d062f45b4c0f320cdaa6d710d87bb                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x1c2cac6ec528c20800b2fe734820d87b581eaa6b                         |                                                              |

## 31. Table: VToken\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2022-05-23 15:00:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 18054932                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x2bc931b1126e67f8a61b6cdd656dce5edd5419b3d4ef39df701b5c9a8e146d2b | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 319                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x78366446547d062f45b4c0f320cdaa6d710d87bb                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 200000000000000000                                                 |                                                              |
| newReserveFactorMantissa | VARCHAR   | 750000000000000000                                                 |                                                              |

## 32. Table: VToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-15 00:36:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16066325                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf1d73c51f2b2a706df0d4332e59ab7bb1f046bf63c7ffc78a2c0a398dbe784cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 313                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x151b1e2635a717bcdc836ecd6fbb62b674fe3e1d                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x13582664841cf3c206cb65183b115d4991b00223                         |                                                              |
| redeemAmount      | VARCHAR   | 1100365222343007115                                                |                                                              |
| redeemTokens      | VARCHAR   | 5471515714                                                         |                                                              |

## 33. Table: VToken\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-19 13:10:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9294045                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4be8eea31d7be178dfd5c4a695a4b4b152306ecc1a89d06ef86d5999d6d5c89 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 308                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x151b1e2635a717bcdc836ecd6fbb62b674fe3e1d                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x0848db7cb495e7b9ada1d4dc972b9a526d014d84                         |                                                              |
| borrower          | VARCHAR   | 0x0848db7cb495e7b9ada1d4dc972b9a526d014d84                         |                                                              |
| repayAmount       | VARCHAR   | 15260622960100808316204                                            |                                                              |
| accountBorrows    | VARCHAR   | 415578654507270580268574                                           |                                                              |
| totalBorrows      | VARCHAR   | 1768210434442357356876839                                          |                                                              |

## 34. Table: VToken\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-22 01:41:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23262481                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea6af3afd94f0c4b64b9e32d6a84dc249d2aeb3d5e795f578e3e31fccde5c44c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95c78222b3d6e262426483d42cfa53685a67ab9d                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0xfcb97be518c46f7e6432e926db7e2e5ab3b0fbe6                         |                                                              |
| addAmount         | VARCHAR   | 1                                                                  |                                                              |
| newTotalReserves  | VARCHAR   | 68290205209863934395211                                            |                                                              |

## 35. Table: VToken\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-14 04:06:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3080469                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe1e55a6d115743611fb135641a54ca5ce48c60b8786099c17a904b1e18a27f5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeca88125a5adbe82614ffc12d0db554e2e2867c8                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x1ca3ac3686071be692be7f1fbecd668641476d7e                         |                                                              |
| reduceAmount      | VARCHAR   | 10000000000000000000                                               |                                                              |
| newTotalReserves  | VARCHAR   | 4263124067931858787443                                             |                                                              |

## 36. Table: VToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-08 08:35:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21993488                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2989c9500a470a7c342bf9a966655f3d5fd99c94d816960cc59d88b25dd2e24 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08ceb3f4a7ed3500ca0982bcd0fc7816688084c3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x10b30298cb9b393061a8b53f157054d64b8e0fd2                         |                                                              |
| to                | VARCHAR   | 0x08ceb3f4a7ed3500ca0982bcd0fc7816688084c3                         |                                                              |
| amount            | VARCHAR   | 40648284229                                                        |                                                              |
