# perennial

## 1. Table: Collateral\_event\_AccountSettle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 15:17:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16556256                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb97fe69922966bee86ffb40b766cc059da14271a9440330b09af37fd1c0998a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 498                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d264ebdb6632a06a1726193d4d37fef1e5dbdcd                         | Address of the contract that produced the log                |
| product           | VARCHAR   | 0x60b24e58a46896724f8e2b18f18c801976d2b569                         |                                                              |
| account           | VARCHAR   | 0x737a2059e67d660371f80e98bb505fb33435d40b                         |                                                              |
| amount            | VARCHAR   | -138080743344689896                                                |                                                              |
| newShortfall      | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: Collateral\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-18 10:41:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16854113                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe94eef26fd4a3cab8c79ef268e58e5eaa4e276435ec7fc6762ec1a19fac494c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 244                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d264ebdb6632a06a1726193d4d37fef1e5dbdcd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xc7b42f99c63126b22858f4eed636f805cfe82c91                         |                                                              |
| product           | VARCHAR   | 0xdb60626ff6cdc9db07d3625a93d21ddf0f8a688c                         |                                                              |
| amount            | VARCHAR   | 2000000000000000000000                                             |                                                              |

## 3. Table: Collateral\_event\_FeeClaim\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 4. Table: Collateral\_event\_Initialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-21 00:06:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792786                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe612e5fbab008e000d75bc207a52a273df027e189763c87bea4cedac338f6dfa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d264ebdb6632a06a1726193d4d37fef1e5dbdcd                         | Address of the contract that produced the log                |
| version           | VARCHAR   | 1                                                                  |                                                              |

## 5. Table: Collateral\_event\_Liquidation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-18 16:15:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16434821                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c8f85f8009628d2e785e601ad83a93d43bfa0b9f2625b917cd8e004ae40aee7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d264ebdb6632a06a1726193d4d37fef1e5dbdcd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xddf0cebc3b259420280371337b11f6fabdddf2f0                         |                                                              |
| product           | VARCHAR   | 0xdb60626ff6cdc9db07d3625a93d21ddf0f8a688c                         |                                                              |
| liquidator        | VARCHAR   | 0x423d55649769f745015f9de8601773e86793b7ec                         |                                                              |
| fee               | VARCHAR   | 11721388259890429122                                               |                                                              |

## 6. Table: Collateral\_event\_ProductSettle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 07:17:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17668835                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x444d7637fe40f8322648bd0c6386dc01bfc0e0b9c7d081f3ace5305037faa58b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d264ebdb6632a06a1726193d4d37fef1e5dbdcd                         | Address of the contract that produced the log                |
| product           | VARCHAR   | 0x60b24e58a46896724f8e2b18f18c801976d2b569                         |                                                              |
| protocolFee       | VARCHAR   | 0                                                                  |                                                              |
| productFee        | VARCHAR   | 0                                                                  |                                                              |

## 7. Table: Collateral\_event\_ShortfallResolution\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| product           | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 8. Table: Collateral\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 12:58:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16555566                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c36539ce04e079f8da0c16a1ccee622ec6a4a31f8d20b4518f7c6377dd1cc48 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d264ebdb6632a06a1726193d4d37fef1e5dbdcd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x89780b0fd48dc3a62d20020e40635b49a76f1995                         |                                                              |
| product           | VARCHAR   | 0xdb60626ff6cdc9db07d3625a93d21ddf0f8a688c                         |                                                              |
| amount            | VARCHAR   | 1451976932284689328                                                |                                                              |

## 9. Table: Controller\_event\_CollateralUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-21 00:07:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792790                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1dcb0fcc49c11aaf5003185c8054a28af0417acb985555feca05399dffe18ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 356                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| newCollateral     | VARCHAR   | 0x2d264ebdb6632a06a1726193d4d37fef1e5dbdcd                         |                                                              |

## 10. Table: Controller\_event\_CoordinatorCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-26 16:32:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15833463                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe160a4170cee1e675edb79e60b478dac5802380df6f01ea11f0969a139defbab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 417                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| coordinatorId     | VARCHAR   | 1                                                                  |                                                              |
| owner             | VARCHAR   | 0xa20ea565cd799e01a86548af5a2929eb7c767fc9                         |                                                              |

## 11. Table: Controller\_event\_CoordinatorOwnerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 00:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16115143                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02b1b96a04cc78f5fd18d13e0e7fcb877197fcd838a799d1ee6bbe10ff14858f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| coordinatorId     | VARCHAR   | 1                                                                  |                                                              |
| newOwner          | VARCHAR   | 0xe3010e0a0f1a8e8ac58bf2cd83b7facaee4821af                         |                                                              |

## 12. Table: Controller\_event\_CoordinatorPendingOwnerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-21 00:07:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792794                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc755613d069f39ec173906b2f002bc906cda511e9e8120422fbcd1fb810b9f1b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| coordinatorId     | VARCHAR   | 0                                                                  |                                                              |
| newPendingOwner   | VARCHAR   | 0x13b7a79e050ef2c3fdc858efd5c066c3655be841                         |                                                              |

## 13. Table: Controller\_event\_CoordinatorTreasuryUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| coordinatorId     | VARCHAR   |                                                              |             |
| newTreasury       | VARCHAR   |                                                              |             |

## 14. Table: Controller\_event\_IncentivizationFeeUpdated\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| newIncentivizationFee | VARCHAR   |                                                              |             |

## 15. Table: Controller\_event\_IncentivizerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-21 00:07:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792790                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1dcb0fcc49c11aaf5003185c8054a28af0417acb985555feca05399dffe18ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 357                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| newIncentivizer   | VARCHAR   | 0x69a682f90d58c8d1abea18ae1bc98c9a1be4f2eb                         |                                                              |

## 16. Table: Controller\_event\_Initialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-21 00:07:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792790                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1dcb0fcc49c11aaf5003185c8054a28af0417acb985555feca05399dffe18ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 359                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| version           | VARCHAR   | 1                                                                  |                                                              |

## 17. Table: Controller\_event\_LiquidationFeeUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 00:34:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16115055                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xff73f4e823d8d16b084d872accad24bd80c90524454c6b6663767a3f56620086 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| newLiquidationFee | VARCHAR   | 100000000000000000                                                 |                                                              |

## 18. Table: Controller\_event\_MinCollateralUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 00:18:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16114975                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8818895226e5c0f7e48c97512898f4926293eb45806746d65e89ef7c44fba8dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 366                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| newMinCollateral  | VARCHAR   | 100000000000000000000                                              |                                                              |

## 19. Table: Controller\_event\_MinFundingFeeUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newMinFundingFee  | VARCHAR   |                                                              |             |

## 20. Table: Controller\_event\_MultiInvokerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 01:53:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16108291                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa2f517e7cee7aa7cebc4d368db528c1c7ee98e74cc9f8e3515140a88a49997d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 254                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| newMultiInvoker   | VARCHAR   | 0xe77076d3eee12da1d7402ff4e6ca12a8d99fce8b                         |                                                              |

## 21. Table: Controller\_event\_PausedUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newPaused         | VARCHAR   |                                                              |             |

## 22. Table: Controller\_event\_PauserUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 00:31:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16115037                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb00136377e1d16f002f8df6bb0afacde3f62f44514a83b9708991ba404da7cfc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| newPauser         | VARCHAR   | 0xe3010e0a0f1a8e8ac58bf2cd83b7facaee4821af                         |                                                              |

## 23. Table: Controller\_event\_ProductBeaconUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-21 00:07:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792790                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1dcb0fcc49c11aaf5003185c8054a28af0417acb985555feca05399dffe18ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 358                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9df509186b6d3b7d033359f94c8b1bb5544d51b3                         | Address of the contract that produced the log                |
| newProductBeacon  | VARCHAR   | 0x841d7c994ac0bb17ccd65a021e686e3cfafe2118                         |                                                              |

## 24. Table: Controller\_event\_ProductCreated\_history

| Column                                         | Type                                                                                                                                                                                                                                                                                                                                                        | Example                                                      | Description |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                               | TIMESTAMP                                                                                                                                                                                                                                                                                                                                                   | Timestamp of the block where this event was emitted          |             |
| block\_number                                  | INTEGER                                                                                                                                                                                                                                                                                                                                                     | The block number where this event was emitted                |             |
| transaction\_hash                              | VARCHAR                                                                                                                                                                                                                                                                                                                                                     | Hash of the transactions in which this event was emitted     |             |
| log\_index                                     | INTEGER                                                                                                                                                                                                                                                                                                                                                     | Integer of the log index position in the block of this event |             |
| contract\_address                              | VARCHAR                                                                                                                                                                                                                                                                                                                                                     | Address of the contract that produced the log                |             |
| product                                        | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo                                    | STRUCT\<name STRING, symbol STRING, payoffDefinition STRUCT\<payoffType STRING, payoffDirection STRING, data STRING>, oracle STRING, maintenance STRING, fundingFee STRING, makerFee STRING, takerFee STRING, positionFee STRING, makerLimit STRING, utilizationCurve STRUCT\<minRate STRING, maxRate STRING, targetRate STRING, targetUtilization STRING>> |                                                              |             |
| productInfo.name                               | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.symbol                             | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.payoffDefinition                   | STRUCT\<payoffType STRING, payoffDirection STRING, data STRING>                                                                                                                                                                                                                                                                                             |                                                              |             |
| productInfo.payoffDefinition.payoffType        | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.payoffDefinition.payoffDirection   | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.payoffDefinition.data              | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.oracle                             | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.maintenance                        | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.fundingFee                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.makerFee                           | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.takerFee                           | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.positionFee                        | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.makerLimit                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.utilizationCurve                   | STRUCT\<minRate STRING, maxRate STRING, targetRate STRING, targetUtilization STRING>                                                                                                                                                                                                                                                                        |                                                              |             |
| productInfo.utilizationCurve.minRate           | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.utilizationCurve.maxRate           | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.utilizationCurve.targetRate        | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |
| productInfo.utilizationCurve.targetUtilization | VARCHAR                                                                                                                                                                                                                                                                                                                                                     |                                                              |             |

## 25. Table: Controller\_event\_ProgramsPerProductUpdated\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| newProgramsPerProduct | VARCHAR   |                                                              |             |

## 26. Table: Controller\_event\_ProtocolFeeUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newProtocolFee    | VARCHAR   |                                                              |             |

## 27. Table: Incentivizer\_event\_Claim\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| product           | VARCHAR   |                                                              |             |
| account           | VARCHAR   |                                                              |             |
| programId         | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 28. Table: Incentivizer\_event\_FeeClaim\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 29. Table: Incentivizer\_event\_Initialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-21 00:06:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792788                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e3cf64378044ae4ac8a46f5d0c8fe9145f086edac9cd007e385ae5dfd50c1b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x69a682f90d58c8d1abea18ae1bc98c9a1be4f2eb                         | Address of the contract that produced the log                |
| version           | VARCHAR   | 1                                                                  |                                                              |

## 30. Table: Incentivizer\_event\_ProgramComplete\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| product           | VARCHAR   |                                                              |             |
| programId         | VARCHAR   |                                                              |             |
| version           | VARCHAR   |                                                              |             |

## 31. Table: Incentivizer\_event\_ProgramCreated\_history

| Column                    | Type                                                                                                                   | Example                                                      | Description |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp          | TIMESTAMP                                                                                                              | Timestamp of the block where this event was emitted          |             |
| block\_number             | INTEGER                                                                                                                | The block number where this event was emitted                |             |
| transaction\_hash         | VARCHAR                                                                                                                | Hash of the transactions in which this event was emitted     |             |
| log\_index                | INTEGER                                                                                                                | Integer of the log index position in the block of this event |             |
| contract\_address         | VARCHAR                                                                                                                | Address of the contract that produced the log                |             |
| product                   | VARCHAR                                                                                                                |                                                              |             |
| programId                 | VARCHAR                                                                                                                |                                                              |             |
| programInfo               | STRUCT\<coordinatorId STRING, amount STRUCT\<maker STRING, taker STRING>, start STRING, duration STRING, token STRING> |                                                              |             |
| programInfo.coordinatorId | VARCHAR                                                                                                                |                                                              |             |
| programInfo.amount        | STRUCT\<maker STRING, taker STRING>                                                                                    |                                                              |             |
| programInfo.amount.maker  | VARCHAR                                                                                                                |                                                              |             |
| programInfo.amount.taker  | VARCHAR                                                                                                                |                                                              |             |
| programInfo.start         | VARCHAR                                                                                                                |                                                              |             |
| programInfo.duration      | VARCHAR                                                                                                                |                                                              |             |
| programInfo.token         | VARCHAR                                                                                                                |                                                              |             |
| programFeeAmount          | VARCHAR                                                                                                                |                                                              |             |

## 32. Table: Incentivizer\_event\_ProgramStarted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| product           | VARCHAR   |                                                              |             |
| programId         | VARCHAR   |                                                              |             |
| version           | VARCHAR   |                                                              |             |

## 33. Table: ProductBeacon\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-03 21:01:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16106836                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x245a21588070cdc1150d986e14c0f5c4b7973fcbffff0cad09f51f201c7afb45 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x841d7c994ac0bb17ccd65a021e686e3cfafe2118                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x66a7fdb96c583c59597de16d8b2b989231415339                         |                                                              |
| newOwner          | VARCHAR   | 0xa20ea565cd799e01a86548af5a2929eb7c767fc9                         |                                                              |

## 34. Table: ProductBeacon\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-23 00:18:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16465873                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdfe8251a34ce0432752c8f9694462beb3b326ebb673e81d08bf31d64601342d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 202                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x841d7c994ac0bb17ccd65a021e686e3cfafe2118                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0x17abb7df4cdcdda78039d51abacfd2b75f82434f                         |                                                              |

## 35. Table: Product\_event\_AccountSettle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-08 02:24:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16581056                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc4dda2781b8bc8ccc45ad5f5ddf86a4f24282755724e610a846a889423e64420 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 283                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60b24e58a46896724f8e2b18f18c801976d2b569                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x11d67fa925877813b744abc0917900c2b1d6eb81                         |                                                              |
| preVersion        | VARCHAR   | 33351                                                              |                                                              |
| toVersion         | VARCHAR   | 33486                                                              |                                                              |

## 36. Table: Product\_event\_ClosedUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newClosed         | VARCHAR   |                                                              |             |
| version           | VARCHAR   |                                                              |             |

## 37. Table: Product\_event\_FundingFeeUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newFundingFee     | VARCHAR   |                                                              |             |
| version           | VARCHAR   |                                                              |             |

## 38. Table: Product\_event\_Initialized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-26 16:32:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15833463                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe160a4170cee1e675edb79e60b478dac5802380df6f01ea11f0969a139defbab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 434                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfed3e166330341e0305594b8c6e6598f9f4cbe9b                         | Address of the contract that produced the log                |
| version           | VARCHAR   | 1                                                                  |                                                              |

## 39. Table: Product\_event\_JumpRateUtilizationCurveUpdated\_history

| Column                    | Type                                                                                 | Example                                                                                              | Description                                                  |
| ------------------------- | ------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP                                                                            | 2022-12-05 01:26:23+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER                                                                              | 16115311                                                                                             | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR                                                                              | 0x444729c8e4bec10d20c7cc44f7c6072a94b571f8a239b5770c5d878b89829d73                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER                                                                              | 107                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR                                                                              | 0x60b24e58a46896724f8e2b18f18c801976d2b569                                                           | Address of the contract that produced the log                |
| updates                   | STRUCT\<minRate STRING, maxRate STRING, targetRate STRING, targetUtilization STRING> | {'minRate': '550000000000000000', 'maxRate': '14000000000000000000', 'targetRate': '9500000000000000 |                                                              |
| updates.minRate           | VARCHAR                                                                              | 550000000000000000                                                                                   |                                                              |
| updates.maxRate           | VARCHAR                                                                              | 14000000000000000000                                                                                 |                                                              |
| updates.targetRate        | VARCHAR                                                                              | 950000000000000000                                                                                   |                                                              |
| updates.targetUtilization | VARCHAR                                                                              | 800000000000000000                                                                                   |                                                              |
| version                   | VARCHAR                                                                              | 30990                                                                                                |                                                              |

## 40. Table: Product\_event\_MaintenanceUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-15 19:11:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16192099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6aa863d11f582c8d35fd15cfbce228cc138a8d91dc7c6ae5773f365cbfba8fe6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60b24e58a46896724f8e2b18f18c801976d2b569                         | Address of the contract that produced the log                |
| newMaintenance    | VARCHAR   | 200000000000000000                                                 |                                                              |
| version           | VARCHAR   | 31367                                                              |                                                              |

## 41. Table: Product\_event\_MakeClosed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-01 22:33:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17168969                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcd626662860f21d61b557f19201cb2d6b99f6f0eba13eeb42784e813495bea94 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60b24e58a46896724f8e2b18f18c801976d2b569                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xb47eb88c256a3ea7b12aaf187ebdc93e126329cb                         |                                                              |
| version           | VARCHAR   | 37125                                                              |                                                              |
| amount            | VARCHAR   | 565000000000000000                                                 |                                                              |

## 42. Table: Product\_event\_MakeOpened\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-02 07:14:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17171543                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4f9aee9d5ddb5bf09651bf4ea7382d93697eaeebbdc87c9bfe6f867e26b9be9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 314                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb60626ff6cdc9db07d3625a93d21ddf0f8a688c                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xb00b1e53909f8253783d8e54aee462f99bacb435                         |                                                              |
| version           | VARCHAR   | 37135                                                              |                                                              |
| amount            | VARCHAR   | 54672294268156668                                                  |                                                              |

## 43. Table: Product\_event\_MakerFeeUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newMakerFee       | VARCHAR   |                                                              |             |
| version           | VARCHAR   |                                                              |             |

## 44. Table: Product\_event\_MakerLimitUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 01:03:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16115196                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x647fd774814cd73fbc400507377d7c66635fe879b4eb8a84714c6264554c4419 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfed3e166330341e0305594b8c6e6598f9f4cbe9b                         | Address of the contract that produced the log                |
| newMakerLimit     | VARCHAR   | 2000000000000000000000                                             |                                                              |
| version           | VARCHAR   | 30990                                                              |                                                              |

## 45. Table: Product\_event\_OracleUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-24 19:37:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16478804                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9f51c340cd5fc46c6165b42d11bd1e2ec6d40afed8aea34fc8dafa74adf985d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 373                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60b24e58a46896724f8e2b18f18c801976d2b569                         | Address of the contract that produced the log                |
| newOracle         | VARCHAR   | 0x2c19eac953048801ffe1358d109a1ac2af7930fd                         |                                                              |
| oracleVersion     | VARCHAR   | 32849                                                              |                                                              |

## 46. Table: Product\_event\_PendingMakerFeeUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newMakerFee       | VARCHAR   |                                                              |             |

## 47. Table: ProxyAdmin\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-21 00:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792781                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ca23ac6a6aac98eb17771f8ee905167de91866e823a4e898b297511233b9043 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 263                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd260a68a081f1d92f5eb1f0afdb29f00836dfa6b                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x66a7fdb96c583c59597de16d8b2b989231415339                         |                                                              |
