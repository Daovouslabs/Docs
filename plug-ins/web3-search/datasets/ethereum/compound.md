# compound

## 1. Table: CometRewards\_v3\_event\_GovernorTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-13 05:39:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15331604                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2cc773107c8773dc78d557e4571adafa618db4052fac5c6516c3322b6ec904f4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1b0e765f6224c21223aea2af16c1c46e38885a40                         | Address of the contract that produced the log                |
| oldGovernor       | VARCHAR   | 0x343715fa797b8e9fe48b9efab4b54f01ca860e78                         |                                                              |
| newGovernor       | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |

## 2. Table: CometRewards\_v3\_event\_RewardClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 11:30:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16904191                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x30bc6ce3ed95d965f61c105f70c4c7cada0483b64d80283bd37e7171f5cecb06 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1b0e765f6224c21223aea2af16c1c46e38885a40                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xa0fad1382a14180142a7a9efbc7636c929be4381                         |                                                              |
| recipient         | VARCHAR   | 0xa0fad1382a14180142a7a9efbc7636c929be4381                         |                                                              |
| token             | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         |                                                              |
| amount            | VARCHAR   | 4831000000000000                                                   |                                                              |

## 3. Table: Comp\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-29 17:41:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15046149                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x382faff6b88a7c9715d8fd82cda97c6abf45d422eb53c93f12e2058a2bbfc79d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 371                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x929c3daf2e2be4c74a56ec01df374bc46a34c6a1                         |                                                              |
| spender           | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         |                                                              |
| amount            | VARCHAR   | 79228162514264337593543950335                                      |                                                              |

## 4. Table: Comp\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-22 13:06:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11907006                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x864de3f45b90f69ae1573a49335d1c85139dd418ece3a1649948f5a814187dfd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0x6637c3700a574887c3cdde9e56d88b5aaf47ecee                         |                                                              |
| fromDelegate      | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| toDelegate        | VARCHAR   | 0x6637c3700a574887c3cdde9e56d88b5aaf47ecee                         |                                                              |

## 5. Table: Comp\_event\_DelegateVotesChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 04:39:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16109118                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8018652c5164abeb7f0cb7c92405f671509b92b5c11d40f8e39eb4421d2036ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 290                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         | Address of the contract that produced the log                |
| delegate          | VARCHAR   | 0xf5dc303a0517bb65170e1f2313af46915582b52d                         |                                                              |
| previousBalance   | VARCHAR   | 0                                                                  |                                                              |
| newBalance        | VARCHAR   | 1003943000000000000                                                |                                                              |

## 6. Table: Comp\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 01:28:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11585024                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23b532bd1718878cf091777b88cb9d36548915a1031f6aea569a0279e8229302 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x2faf487a4414fe77e2327f0bf4ae2a264a776ad2                         |                                                              |
| to                | VARCHAR   | 0xf60228e28badeefa4650331787387b17424e7676                         |                                                              |
| amount            | VARCHAR   | 51916840310000000000                                               |                                                              |

## 7. Table: Configurator\_v3\_event\_AddAsset\_history

| Column                                | Type                                                                                                                                                                  | Example                                                      | Description |
| ------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                      | TIMESTAMP                                                                                                                                                             | Timestamp of the block where this event was emitted          |             |
| block\_number                         | INTEGER                                                                                                                                                               | The block number where this event was emitted                |             |
| transaction\_hash                     | VARCHAR                                                                                                                                                               | Hash of the transactions in which this event was emitted     |             |
| log\_index                            | INTEGER                                                                                                                                                               | Integer of the log index position in the block of this event |             |
| contract\_address                     | VARCHAR                                                                                                                                                               | Address of the contract that produced the log                |             |
| cometProxy                            | VARCHAR                                                                                                                                                               |                                                              |             |
| assetConfig                           | STRUCT\<asset STRING, priceFeed STRING, decimals STRING, borrowCollateralFactor STRING, liquidateCollateralFactor STRING, liquidationFactor STRING, supplyCap STRING> |                                                              |             |
| assetConfig.asset                     | VARCHAR                                                                                                                                                               |                                                              |             |
| assetConfig.priceFeed                 | VARCHAR                                                                                                                                                               |                                                              |             |
| assetConfig.decimals                  | VARCHAR                                                                                                                                                               |                                                              |             |
| assetConfig.borrowCollateralFactor    | VARCHAR                                                                                                                                                               |                                                              |             |
| assetConfig.liquidateCollateralFactor | VARCHAR                                                                                                                                                               |                                                              |             |
| assetConfig.liquidationFactor         | VARCHAR                                                                                                                                                               |                                                              |             |
| assetConfig.supplyCap                 | VARCHAR                                                                                                                                                               |                                                              |             |

## 8. Table: Configurator\_v3\_event\_CometDeployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-19 13:56:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16219183                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4d2fe9f4310741f2afc81a88b64ca06c91a6cabf0d030f35cac71373b6847b1b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| newComet          | VARCHAR   | 0xc82f17fe345047739ee5a77687ff8700a0ecb37d                         |                                                              |

## 9. Table: Configurator\_v3\_event\_GovernorTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-13 05:39:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15331599                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6bec0da029b2f26a6b722b09922d4ac38faa2b6c71c263de543c96fc14c3ed70 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| oldGovernor       | VARCHAR   | 0x343715fa797b8e9fe48b9efab4b54f01ca860e78                         |                                                              |
| newGovernor       | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |

## 10. Table: Configurator\_v3\_event\_SetBaseBorrowMin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldBaseBorrowMin  | VARCHAR   |                                                              |             |
| newBaseBorrowMin  | VARCHAR   |                                                              |             |

## 11. Table: Configurator\_v3\_event\_SetBaseMinForRewards\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy           | VARCHAR   |                                                              |             |
| oldBaseMinForRewards | VARCHAR   |                                                              |             |
| newBaseMinForRewards | VARCHAR   |                                                              |             |

## 12. Table: Configurator\_v3\_event\_SetBaseTokenPriceFeed\_history

| Column                | Type      | Example                                                      | Description |
| --------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp      | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number         | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash     | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index            | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address     | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy            | VARCHAR   |                                                              |             |
| oldBaseTokenPriceFeed | VARCHAR   |                                                              |             |
| newBaseTokenPriceFeed | VARCHAR   |                                                              |             |

## 13. Table: Configurator\_v3\_event\_SetBaseTrackingBorrowSpeed\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-03-06 16:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 16770545                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0xd4ebbe233d785932959b3d4582f059c0aded370419eb6af74d97b56e4c9287d5 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 145                                                                | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy                 | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldBaseTrackingBorrowSpeed | VARCHAR   | 1868287037037                                                      |                                                              |
| newBaseTrackingBorrowSpeed | VARCHAR   | 3257060185185                                                      |                                                              |

## 14. Table: Configurator\_v3\_event\_SetBaseTrackingSupplySpeed\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-07-17 17:25:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 17714451                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0xdba11bdfff0063b5629333783a02f525d2d9b79d7c1e610eba955622c061b355 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 247                                                                | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy                 | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldBaseTrackingSupplySpeed | VARCHAR   | 0                                                                  |                                                              |
| newBaseTrackingSupplySpeed | VARCHAR   | 1157407407407                                                      |                                                              |

## 15. Table: Configurator\_v3\_event\_SetBorrowKink\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-17 17:25:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17714451                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdba11bdfff0063b5629333783a02f525d2d9b79d7c1e610eba955622c061b355 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 251                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldKink           | VARCHAR   | 900000000000000000                                                 |                                                              |
| newKink           | VARCHAR   | 950000000000000000                                                 |                                                              |

## 16. Table: Configurator\_v3\_event\_SetBorrowPerYearInterestRateBase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 23:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17375147                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c027d5d6b1ca59ebd3bfbc6128a090ed4bd2ed23453b8656daf2bbe9a6d8594 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldIRBase         | VARCHAR   | 15000000000000000                                                  |                                                              |
| newIRBase         | VARCHAR   | 10000000000000000                                                  |                                                              |

## 17. Table: Configurator\_v3\_event\_SetBorrowPerYearInterestRateSlopeHigh\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-17 17:25:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17714451                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdba11bdfff0063b5629333783a02f525d2d9b79d7c1e610eba955622c061b355 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 253                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldIRSlopeHigh    | VARCHAR   | 0                                                                  |                                                              |
| newIRSlopeHigh    | VARCHAR   | 567000000000000000                                                 |                                                              |

## 18. Table: Configurator\_v3\_event\_SetBorrowPerYearInterestRateSlopeLow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 23:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17375147                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c027d5d6b1ca59ebd3bfbc6128a090ed4bd2ed23453b8656daf2bbe9a6d8594 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldIRSlopeLow     | VARCHAR   | 35000000000000004                                                  |                                                              |
| newIRSlopeLow     | VARCHAR   | 33300000000000000                                                  |                                                              |

## 19. Table: Configurator\_v3\_event\_SetConfiguration\_history

| Column                                              | Type                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Example                                                                                              | Description                                                  |
| --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                                    | TIMESTAMP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 2022-08-13 05:38:17+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number                                       | INTEGER                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 15331594                                                                                             | The block number where this event was emitted                |
| transaction\_hash                                   | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x74092c79d75e410f632a00155c23650bcecd800fad8ef1abd28448c3ade40b7b                                   | Hash of the transactions in which this event was emitted     |
| log\_index                                          | INTEGER                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 76                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address                                   | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                                                           | Address of the contract that produced the log                |
| cometProxy                                          | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xc3d688b66703497daa19211eedff47f25384cdc3                                                           |                                                              |
| oldConfiguration                                    | STRUCT\<governor STRING, pauseGuardian STRING, baseToken STRING, baseTokenPriceFeed STRING, extensionDelegate STRING, supplyKink STRING, supplyPerYearInterestRateSlopeLow STRING, supplyPerYearInterestRateSlopeHigh STRING, supplyPerYearInterestRateBase STRING, borrowKink STRING, borrowPerYearInterestRateSlopeLow STRING, borrowPerYearInterestRateSlopeHigh STRING, borrowPerYearInterestRateBase STRING, storeFrontPriceFactor STRING, trackingIndexScale STRING, baseTrackingSupplySpeed STRING, baseTrackingBorrowSpeed STRING, baseMinForRewards STRING, baseBorrowMin STRING, targetReserves STRING, assetConfigs STRING> | {'governor': '0x0000000000000000000000000000000000000000', 'pauseGuardian': '0x000000000000000000000 |                                                              |
| oldConfiguration.governor                           | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| oldConfiguration.pauseGuardian                      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| oldConfiguration.baseToken                          | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| oldConfiguration.baseTokenPriceFeed                 | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| oldConfiguration.extensionDelegate                  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| oldConfiguration.supplyKink                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.supplyPerYearInterestRateSlopeLow  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.supplyPerYearInterestRateSlopeHigh | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.supplyPerYearInterestRateBase      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.borrowKink                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.borrowPerYearInterestRateSlopeLow  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.borrowPerYearInterestRateSlopeHigh | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.borrowPerYearInterestRateBase      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.storeFrontPriceFactor              | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.trackingIndexScale                 | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.baseTrackingSupplySpeed            | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.baseTrackingBorrowSpeed            | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.baseMinForRewards                  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.baseBorrowMin                      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.targetReserves                     | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.assetConfigs                       | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                                                      |                                                              |
| newConfiguration                                    | STRUCT\<governor STRING, pauseGuardian STRING, baseToken STRING, baseTokenPriceFeed STRING, extensionDelegate STRING, supplyKink STRING, supplyPerYearInterestRateSlopeLow STRING, supplyPerYearInterestRateSlopeHigh STRING, supplyPerYearInterestRateBase STRING, borrowKink STRING, borrowPerYearInterestRateSlopeLow STRING, borrowPerYearInterestRateSlopeHigh STRING, borrowPerYearInterestRateBase STRING, storeFrontPriceFactor STRING, trackingIndexScale STRING, baseTrackingSupplySpeed STRING, baseTrackingBorrowSpeed STRING, baseMinForRewards STRING, baseBorrowMin STRING, targetReserves STRING, assetConfigs STRING> | {'governor': '0x6d903f6003cca6255d85cca4d3b5e5146dc33925', 'pauseGuardian': '0xbbf3f1421d886e9b2c5d7 |                                                              |
| newConfiguration.governor                           | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                                                           |                                                              |
| newConfiguration.pauseGuardian                      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xbbf3f1421d886e9b2c5d716b5192ac998af2012c                                                           |                                                              |
| newConfiguration.baseToken                          | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                                                           |                                                              |
| newConfiguration.baseTokenPriceFeed                 | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x8fffffd4afb6115b954bd326cbe7b4ba576818f6                                                           |                                                              |
| newConfiguration.extensionDelegate                  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x285617313887d43256f852cae0ee4de4b68d45b0                                                           |                                                              |
| newConfiguration.supplyKink                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 800000000000000000                                                                                   |                                                              |
| newConfiguration.supplyPerYearInterestRateSlopeLow  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 32500000000000000                                                                                    |                                                              |
| newConfiguration.supplyPerYearInterestRateSlopeHigh | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 400000000000000000                                                                                   |                                                              |
| newConfiguration.supplyPerYearInterestRateBase      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| newConfiguration.borrowKink                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 800000000000000000                                                                                   |                                                              |
| newConfiguration.borrowPerYearInterestRateSlopeLow  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 35000000000000004                                                                                    |                                                              |
| newConfiguration.borrowPerYearInterestRateSlopeHigh | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 250000000000000000                                                                                   |                                                              |
| newConfiguration.borrowPerYearInterestRateBase      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 15000000000000000                                                                                    |                                                              |
| newConfiguration.storeFrontPriceFactor              | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 500000000000000000                                                                                   |                                                              |
| newConfiguration.trackingIndexScale                 | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 1000000000000000                                                                                     |                                                              |
| newConfiguration.baseTrackingSupplySpeed            | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| newConfiguration.baseTrackingBorrowSpeed            | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| newConfiguration.baseMinForRewards                  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 1000000000000                                                                                        |                                                              |
| newConfiguration.baseBorrowMin                      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 100000000                                                                                            |                                                              |
| newConfiguration.targetReserves                     | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 5000000000000                                                                                        |                                                              |
| newConfiguration.assetConfigs                       | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xc00e94Cb662C3520282E6f5717214004A7f26888,0xdbd020CAeF83eFd542f4De03e3cF0C28A4428bd5,18,65000000000 |                                                              |

## 20. Table: Configurator\_v3\_event\_SetExtensionDelegate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldExt            | VARCHAR   |                                                              |             |
| newExt            | VARCHAR   |                                                              |             |

## 21. Table: Configurator\_v3\_event\_SetFactory\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-24 13:42:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16477039                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ccef90ee3841b0a7729ecf6e53e2c9d37add6c8c84c712bc7d32afd86e00a4e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         |                                                              |
| oldFactory        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newFactory        | VARCHAR   | 0xa7f7de6ccad4d83d81676717053883337ac2c1b4                         |                                                              |

## 22. Table: Configurator\_v3\_event\_SetGovernor\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldGovernor       | VARCHAR   |                                                              |             |
| newGovernor       | VARCHAR   |                                                              |             |

## 23. Table: Configurator\_v3\_event\_SetPauseGuardian\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldPauseGuardian  | VARCHAR   |                                                              |             |
| newPauseGuardian  | VARCHAR   |                                                              |             |

## 24. Table: Configurator\_v3\_event\_SetStoreFrontPriceFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2023-03-06 16:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 16770545                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xd4ebbe233d785932959b3d4582f059c0aded370419eb6af74d97b56e4c9287d5 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy               | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldStoreFrontPriceFactor | VARCHAR   | 500000000000000000                                                 |                                                              |
| newStoreFrontPriceFactor | VARCHAR   | 600000000000000000                                                 |                                                              |

## 25. Table: Configurator\_v3\_event\_SetSupplyKink\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 23:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17375147                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c027d5d6b1ca59ebd3bfbc6128a090ed4bd2ed23453b8656daf2bbe9a6d8594 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldKink           | VARCHAR   | 800000000000000000                                                 |                                                              |
| newKink           | VARCHAR   | 950000000000000000                                                 |                                                              |

## 26. Table: Configurator\_v3\_event\_SetSupplyPerYearInterestRateBase\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldIRBase         | VARCHAR   |                                                              |             |
| newIRBase         | VARCHAR   |                                                              |             |

## 27. Table: Configurator\_v3\_event\_SetSupplyPerYearInterestRateSlopeHigh\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 23:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17375147                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c027d5d6b1ca59ebd3bfbc6128a090ed4bd2ed23453b8656daf2bbe9a6d8594 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldIRSlopeHigh    | VARCHAR   | 400000000000000000                                                 |                                                              |
| newIRSlopeHigh    | VARCHAR   | 760000000000000000                                                 |                                                              |

## 28. Table: Configurator\_v3\_event\_SetSupplyPerYearInterestRateSlopeLow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 23:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17375147                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c027d5d6b1ca59ebd3bfbc6128a090ed4bd2ed23453b8656daf2bbe9a6d8594 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| oldIRSlopeLow     | VARCHAR   | 32500000000000000                                                  |                                                              |
| newIRSlopeLow     | VARCHAR   | 34000000000000000                                                  |                                                              |

## 29. Table: Configurator\_v3\_event\_SetTargetReserves\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldTargetReserves | VARCHAR   |                                                              |             |
| newTargetReserves | VARCHAR   |                                                              |             |

## 30. Table: Configurator\_v3\_event\_UpdateAssetBorrowCollateralFactor\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| asset             | VARCHAR   |                                                              |             |
| oldBorrowCF       | VARCHAR   |                                                              |             |
| newBorrowCF       | VARCHAR   |                                                              |             |

## 31. Table: Configurator\_v3\_event\_UpdateAssetLiquidateCollateralFactor\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| asset             | VARCHAR   |                                                              |             |
| oldLiquidateCF    | VARCHAR   |                                                              |             |
| newLiquidateCF    | VARCHAR   |                                                              |             |

## 32. Table: Configurator\_v3\_event\_UpdateAssetLiquidationFactor\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-12-19 13:56:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 16219183                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x4d2fe9f4310741f2afc81a88b64ca06c91a6cabf0d030f35cac71373b6847b1b | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy           | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| asset                | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         |                                                              |
| oldLiquidationFactor | VARCHAR   | 930000000000000000                                                 |                                                              |
| newLiquidationFactor | VARCHAR   | 880000000000000000                                                 |                                                              |

## 33. Table: Configurator\_v3\_event\_UpdateAssetPriceFeed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| asset             | VARCHAR   |                                                              |             |
| oldPriceFeed      | VARCHAR   |                                                              |             |
| newPriceFeed      | VARCHAR   |                                                              |             |

## 34. Table: Configurator\_v3\_event\_UpdateAssetSupplyCap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-31 12:55:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17813126                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc4f99540accb5aa85b7a5c7d2c2f0c1d9ee27a59501f412046825922c145ca7d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 296                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x316f9708bb98af7da9c68c1c3b5e79039cd336e3                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         |                                                              |
| asset             | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| oldSupplyCap      | VARCHAR   | 1200000000000                                                      |                                                              |
| newSupplyCap      | VARCHAR   | 1800000000000                                                      |                                                              |

## 35. Table: Configurator\_v3\_event\_UpdateAsset\_history

| Column                                   | Type                                                                                                                                                                  | Example                                                      | Description |
| ---------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                         | TIMESTAMP                                                                                                                                                             | Timestamp of the block where this event was emitted          |             |
| block\_number                            | INTEGER                                                                                                                                                               | The block number where this event was emitted                |             |
| transaction\_hash                        | VARCHAR                                                                                                                                                               | Hash of the transactions in which this event was emitted     |             |
| log\_index                               | INTEGER                                                                                                                                                               | Integer of the log index position in the block of this event |             |
| contract\_address                        | VARCHAR                                                                                                                                                               | Address of the contract that produced the log                |             |
| cometProxy                               | VARCHAR                                                                                                                                                               |                                                              |             |
| oldAssetConfig                           | STRUCT\<asset STRING, priceFeed STRING, decimals STRING, borrowCollateralFactor STRING, liquidateCollateralFactor STRING, liquidationFactor STRING, supplyCap STRING> |                                                              |             |
| oldAssetConfig.asset                     | VARCHAR                                                                                                                                                               |                                                              |             |
| oldAssetConfig.priceFeed                 | VARCHAR                                                                                                                                                               |                                                              |             |
| oldAssetConfig.decimals                  | VARCHAR                                                                                                                                                               |                                                              |             |
| oldAssetConfig.borrowCollateralFactor    | VARCHAR                                                                                                                                                               |                                                              |             |
| oldAssetConfig.liquidateCollateralFactor | VARCHAR                                                                                                                                                               |                                                              |             |
| oldAssetConfig.liquidationFactor         | VARCHAR                                                                                                                                                               |                                                              |             |
| oldAssetConfig.supplyCap                 | VARCHAR                                                                                                                                                               |                                                              |             |
| newAssetConfig                           | STRUCT\<asset STRING, priceFeed STRING, decimals STRING, borrowCollateralFactor STRING, liquidateCollateralFactor STRING, liquidationFactor STRING, supplyCap STRING> |                                                              |             |
| newAssetConfig.asset                     | VARCHAR                                                                                                                                                               |                                                              |             |
| newAssetConfig.priceFeed                 | VARCHAR                                                                                                                                                               |                                                              |             |
| newAssetConfig.decimals                  | VARCHAR                                                                                                                                                               |                                                              |             |
| newAssetConfig.borrowCollateralFactor    | VARCHAR                                                                                                                                                               |                                                              |             |
| newAssetConfig.liquidateCollateralFactor | VARCHAR                                                                                                                                                               |                                                              |             |
| newAssetConfig.liquidationFactor         | VARCHAR                                                                                                                                                               |                                                              |             |
| newAssetConfig.supplyCap                 | VARCHAR                                                                                                                                                               |                                                              |             |

## 36. Table: GovernorAlpha\_event\_ProposalCreated\_history

| Column            | Type      | Example                                                                                               | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-05 23:13:06+00:00                                                                             | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11395518                                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39f4e846c6d50373ad41e7db463b33e40cb5e9e938aa578bb5684e69688dc5ba                                    | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc0da01a04c3f3e0be433606045bb7017a7323e38                                                            | Address of the contract that produced the log                |
| id                | VARCHAR   | 30                                                                                                    |                                                              |
| proposer          | VARCHAR   | 0x6626593c237f530d15ae9980a95ef938ac15c35c                                                            |                                                              |
| targets           | ARRAY     | \['0x3d9819210A31b4961b30EF54bE2aeD79B9c9Cd3B', '0x7d47d3f06A9C10576bc5DC87ceFbf3288F96Ea04', '0x3d98 |                                                              |
| values            | ARRAY     | \['0', '0', '0']                                                                                      |                                                              |
| signatures        | ARRAY     | \['\_setPendingImplementation(address)', '\_become(address)', '\_grantComp(address,uint256)']         |                                                              |
| calldatas         | ARRAY     | \['0x0000000000000000000000007d47d3f06a9c10576bc5dc87cefbf3288f96ea04', '0x0000000000000000000000003d |                                                              |
| startBlock        | VARCHAR   | 11395519                                                                                              |                                                              |
| endBlock          | VARCHAR   | 11412799                                                                                              |                                                              |
| description       | VARCHAR   | # COMP Contributor Grants                                                                             |                                                              |
| ## Summary        |           |                                                                                                       |                                                              |

The \[Compound Comptroller contract]\(https://etherscan.io/addre||

## 37. Table: GovernorAlpha\_event\_ProposalExecuted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-10 17:03:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11426425                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94a5432e49cf56ba30ebe9029a70de1648f879cd10b5af1c05d329e2e56f629f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 278                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc0da01a04c3f3e0be433606045bb7017a7323e38                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 30                                                                 |                                                              |

## 38. Table: GovernorAlpha\_event\_ProposalQueued\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-25 16:36:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10136051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x10cf1d1313259a4ace4102d0f56ea9453f4ac3f5a53ef5c9f133d81dc9c4ea8c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 301                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc0da01a04c3f3e0be433606045bb7017a7323e38                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 4                                                                  |                                                              |
| eta               | VARCHAR   | 1590597384                                                         |                                                              |

## 39. Table: GovernorAlpha\_event\_VoteCast\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-02 00:53:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11773673                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd9fc56e7a2bab8c649a9fc648853969d2a4263d7362de59b53f68b8120a0189 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 240                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc0da01a04c3f3e0be433606045bb7017a7323e38                         | Address of the contract that produced the log                |
| voter             | VARCHAR   | 0x5bc928bf0dab1e4a2ddd9e347b0f22e88026d76c                         |                                                              |
| proposalId        | VARCHAR   | 36                                                                 |                                                              |
| support           | VARCHAR   | true                                                               |                                                              |
| votes             | VARCHAR   | 29904109787858402606729                                            |                                                              |

## 40. Table: MoneyMarket\_event\_BorrowLiquidated\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2018-12-19 15:49:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 6915694                                                            | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0x9c11c96eae03ad07b105d0468a894f6def9061f02865e781292389cb4662a828 | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0x3fda67f7583380e67ef93072294a7fac882fd7e7                         | Address of the contract that produced the log                |
| targetAccount                | VARCHAR   | 0x3f563dd21f42233c4928cad061494f267578b569                         |                                                              |
| assetBorrow                  | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| borrowBalanceBefore          | VARCHAR   | 1740986793096721140                                                |                                                              |
| borrowBalanceAccumulated     | VARCHAR   | 1741223865483401592                                                |                                                              |
| amountRepaid                 | VARCHAR   | 21000000000000000                                                  |                                                              |
| borrowBalanceAfter           | VARCHAR   | 1720223865483401592                                                |                                                              |
| liquidator                   | VARCHAR   | 0x1055be4bf7338c7606d9efdcf80593f180ba043e                         |                                                              |
| assetCollateral              | VARCHAR   | 0x89d24a6b4ccb1b6faa2625fe562bdd9a23260359                         |                                                              |
| collateralBalanceBefore      | VARCHAR   | 269726107232418879127                                              |                                                              |
| collateralBalanceAccumulated | VARCHAR   | 269749108763546761378                                              |                                                              |
| amountSeized                 | VARCHAR   | 2295735750000000024                                                |                                                              |
| collateralBalanceAfter       | VARCHAR   | 267453373013546761354                                              |                                                              |

## 41. Table: MoneyMarket\_event\_BorrowRepaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-16 01:12:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7225713                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd7de76ecf32501df5b204910e35e0a8297598552c616179788aceeb793304584 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fda67f7583380e67ef93072294a7fac882fd7e7                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xaf712990cb4d56d5cd0782bc687c72ad13dfc3ff                         |                                                              |
| asset             | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| amount            | VARCHAR   | 82889153830499700000                                               |                                                              |
| startingBalance   | VARCHAR   | 82909876118957324925                                               |                                                              |
| newBalance        | VARCHAR   | 21089216482373826                                                  |                                                              |

## 42. Table: MoneyMarket\_event\_BorrowTaken\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2018-11-20 11:16:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 6739219                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x4bacd783aa16803d1beb631889c2d901c32282000778e8e406d501758a3f2b94 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 152                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x3fda67f7583380e67ef93072294a7fac882fd7e7                         | Address of the contract that produced the log                |
| account             | VARCHAR   | 0x1e2bfd353d26e4ad48933c1b518a453d1440969f                         |                                                              |
| asset               | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount              | VARCHAR   | 15000000000000000000                                               |                                                              |
| startingBalance     | VARCHAR   | 0                                                                  |                                                              |
| borrowAmountWithFee | VARCHAR   | 15003750000000000000                                               |                                                              |
| newBalance          | VARCHAR   | 15003750000000000000                                               |                                                              |

## 43. Table: MoneyMarket\_event\_SupplyReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-10-28 22:23:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6601758                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4187106e8eeb08b8b60fa81e790160e962427a7465e3d89cabf657354f3f5ec3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fda67f7583380e67ef93072294a7fac882fd7e7                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xb6d94226eab23ac1602113bae51e0f37d92a50bf                         |                                                              |
| asset             | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| amount            | VARCHAR   | 62417000000000000000                                               |                                                              |
| startingBalance   | VARCHAR   | 0                                                                  |                                                              |
| newBalance        | VARCHAR   | 62417000000000000000                                               |                                                              |

## 44. Table: MoneyMarket\_event\_SupplyWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-05 23:54:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7703989                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x762d05db528f261e5c04b0aad68976e6303fa5fa6fab5e444deb5bc6cd274a0e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fda67f7583380e67ef93072294a7fac882fd7e7                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x70ea762dcd45145e81b1694549941d0991869015                         |                                                              |
| asset             | VARCHAR   | 0x0d8775f648430679a709e98d2b0cb6250d2887ef                         |                                                              |
| amount            | VARCHAR   | 25000084898908246916                                               |                                                              |
| startingBalance   | VARCHAR   | 25000084650992551358                                               |                                                              |
| newBalance        | VARCHAR   | 0                                                                  |                                                              |

## 45. Table: Unitroller\_event\_MarketListed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-22 18:39:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12485775                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x461fdf40adb6ca7079cd5a901ef427b3d4d7f8eb10cd3109bf90005744d375c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         |                                                              |

## 46. Table: cAAVE\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-05-23 12:44:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17322013                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xdf057bfab18e35653c9d25d4f9c80cb792e961a19c618ac5bebe596b3ae586bb | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 20694726679551163928043                                            |                                                              |
| interestAccumulated | VARCHAR   | 111523779193388475                                                 |                                                              |
| borrowIndex         | VARCHAR   | 1153416969556696190                                                |                                                              |
| totalBorrows        | VARCHAR   | 2160251696646302616051                                             |                                                              |

## 47. Table: cAAVE\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-01 12:21:28+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13721022                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c5e0764a153f24dd89b3cf8184bfb7bfd1ac073345086247e647d3f96fd6e3a             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xa29ed649bf632d19a0d045f5a2d85c21079dc0d6                                     |                                                              |
| spender           | VARCHAR   | 0xbd017026e557edd4e0d485b1db2421c401ae7960                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 48. Table: cAAVE\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 03:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17029345                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76d02f36ee9c83928a929af21ea025ca579a63ff58ee2cca2eafeba873667e56 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xc37704a457b1ee87eb657cae584a34961e86acac                         |                                                              |
| borrowAmount      | VARCHAR   | 1555000000000000000000                                             |                                                              |
| accountBorrows    | VARCHAR   | 3565186474627663879772                                             |                                                              |
| totalBorrows      | VARCHAR   | 7290859864588348784281                                             |                                                              |

## 49. Table: cAAVE\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-27 10:00:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13498755                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1fd1b428f372618759367c015bf27a4e1c93d6f068c20c6d0d286715324ff13 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 218                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 14                                                                 |                                                              |
| info              | VARCHAR   | 9                                                                  |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 50. Table: cAAVE\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-28 08:42:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13892723                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xff40eac6175789846c04407bb19471b637ba708526ddb94103b3e8d5d5462932 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x2e767dc1bcdf82a998cf431540fe73568e83c034                         |                                                              |
| borrower          | VARCHAR   | 0x8fd2515a5b29e61220ee080d484d1f2ea4c46e6b                         |                                                              |
| repayAmount       | VARCHAR   | 32684442074701605552                                               |                                                              |
| cTokenCollateral  | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         |                                                              |
| seizeTokens       | VARCHAR   | 47785010418610                                                     |                                                              |

## 51. Table: cAAVE\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-29 14:19:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16933496                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c8586f220447dff459ec54b9dfd22a6690ba735040768f9d744a7ca5b15f60b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 235                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x28aeab635aaf4f68d0f88834c8637174257d942c                         |                                                              |
| mintAmount        | VARCHAR   | 59488388888333775231                                               |                                                              |
| mintTokens        | VARCHAR   | 289347559872                                                       |                                                              |

## 52. Table: cAAVE\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 53. Table: cAAVE\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-18 03:19:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12848198                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a82d0869400aae6868f441214e739d60c0abf38c62e235a27acbff5bc6dde7f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 54. Table: cAAVE\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-07 21:19:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14541141                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7cc2acd03f837009b97c3d21a0efe6fb02ae4cda75a061e70f4d20ab411da275 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 328                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0xa035b9e130f2b1aedc733eefb1c67ba4c503491f                         |                                                              |
| newImplementation | VARCHAR   | 0x3363bae2fc44da742df13cd3ee94b6bb868ea376                         |                                                              |

## 55. Table: cAAVE\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-07-18 03:19:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12848198                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x1a82d0869400aae6868f441214e739d60c0abf38c62e235a27acbff5bc6dde7f | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xd956188795ca6f4a74092ddca33e0ea4ca3a1395                         |                                                              |

## 56. Table: cAAVE\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 57. Table: cAAVE\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-08-04 17:53:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 12960086                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xb83ddf4033f61cda65149428c1a247fe516e53d7f762b55ac64a751d1fb3d7ce | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 329                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 250000000000000000                                                 |                                                              |

## 58. Table: cAAVE\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-22 08:01:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15389113                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x792741e3bd638368540d8693d4279f348bc7bde1a524635a0c617e3c5547be91 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xa090e6e0311ce8fe1f9d7c16921861661097f6a6                         |                                                              |
| redeemAmount      | VARCHAR   | 6248966801882608386                                                |                                                              |
| redeemTokens      | VARCHAR   | 30849686022                                                        |                                                              |

## 59. Table: cAAVE\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 02:27:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13007650                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc015e559b5949e3f9af7ffa234ad01f9db03979764d04c681b7ac78c73becc1f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xdd6e1a285790d4088fd020c65c764babf44b31e8                         |                                                              |
| borrower          | VARCHAR   | 0xdd6e1a285790d4088fd020c65c764babf44b31e8                         |                                                              |
| repayAmount       | VARCHAR   | 1000212127245415896610                                             |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 3417201207710033373382                                             |                                                              |

## 60. Table: cAAVE\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-24 01:32:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14832951                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xabc8e4b3627ad35c62d9b501272c8526b9d33cd65861e6addf81808954594380 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         |                                                              |
| addAmount         | VARCHAR   | 66979783710394602                                                  |                                                              |
| newTotalReserves  | VARCHAR   | 72349028760546971860                                               |                                                              |

## 61. Table: cAAVE\_event\_ReservesReduced\_history

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

## 62. Table: cAAVE\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 21:12:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15563027                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b710f9501a2c81742fb37da2004b0aa1158b34256553801d931c85f21ba2f33 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 624                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xcfc50541c3deaf725ce738ef87ace2ad778ba0c5                         |                                                              |
| to                | VARCHAR   | 0xe65cdb6479bac1e22340e4e755fae7e509ecd06c                         |                                                              |
| amount            | VARCHAR   | 33960230058979                                                     |                                                              |

## 63. Table: cBAT\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-08-13 23:27:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13019809                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x79c071acac17e95fc4ce3ec7d647968aa257df6d88dbd9607a462638cb5d065f | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 305                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| interestAccumulated | VARCHAR   | 338165626454225356604                                              |                                                              |
| borrowIndex         | VARCHAR   | 1143939305036333491                                                |                                                              |
| totalBorrows        | VARCHAR   | 21677781827048166649997096                                         |                                                              |

## 64. Table: cBAT\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 09:48:29+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10689847                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3916d0c5174c13ce6903f147636dfb3e6a4352e46119d9762e62725c2c1e082             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x83c264671710fd453c6a86a0e40857cdb0b7d6e1                                     |                                                              |
| spender           | VARCHAR   | 0xe4c9194962532feb467dce8b3d42419641c6ed2e                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 65. Table: cBAT\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-19 01:33:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10486995                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c912a9fe050b14170b37256bc960cde84f4fb311008a9de7f86ade59fdb1791 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x88886841cfccbf54adbbc0b6c9cbaceabec42b8b                         |                                                              |
| borrowAmount      | VARCHAR   | 1000000000000000000000000                                          |                                                              |
| accountBorrows    | VARCHAR   | 1000000000000000000000000                                          |                                                              |
| totalBorrows      | VARCHAR   | 2503168714952278151495940                                          |                                                              |

## 66. Table: cBAT\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-24 19:04:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9735873                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xda4380b6383e6a3ed350ccecd6361bbdf5d4b6f430af99eefeec21d2be4a20f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 285                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 13                                                                 |                                                              |
| info              | VARCHAR   | 24                                                                 |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 67. Table: cBAT\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-07 11:11:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11808906                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa6b72302293d6b916c141536a8004d5dd437ddca6db70471b052f0957d100923 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 117                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x6780846518290724038e86c98a1e903888338875                         |                                                              |
| borrower          | VARCHAR   | 0x632fc4449f4da91d6994c8ffd77f24027fac2567                         |                                                              |
| repayAmount       | VARCHAR   | 5207424642723996205074                                             |                                                              |
| cTokenCollateral  | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         |                                                              |
| seizeTokens       | VARCHAR   | 662029226534                                                       |                                                              |

## 68. Table: cBAT\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 01:50:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10687665                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x72152052783ebbfc0f7b587e14e6217f4224c3b7e32e3e506580ccae384955c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x4a8f4017d34fd7d23ba4c64107a041d94348ee6a                         |                                                              |
| mintAmount        | VARCHAR   | 516550000000000000000                                              |                                                              |
| mintTokens        | VARCHAR   | 2534849485208                                                      |                                                              |

## 69. Table: cBAT\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 19:08:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810860                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45e4307530c340c5a93899dd6783262d26d0b2d8b439c173938840bf705f14f1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |
| newAdmin          | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |

## 70. Table: cBAT\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 01:21:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7710735                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb92ea2ddcd07e9d014eb4a54fe227cc164fa28fda3d8a0b84b2c1cd375155097 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 71. Table: cBAT\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-05-07 01:21:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 7710735                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xb92ea2ddcd07e9d014eb4a54fe227cc164fa28fda3d8a0b84b2c1cd375155097 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xbae04cbf96391086dc643e842b517734e214d698                         |                                                              |

## 72. Table: cBAT\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 02:21:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7711006                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb55b48cb050fc55983631665088e61a15375cf4aacfe577d720f3539449f05f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |

## 73. Table: cBAT\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2020-12-12 14:10:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 11438576                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x72198c8f10a1958aa97b2f1408700209a14e026e81fabba866e03668e5879c8d | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 500000000000000000                                                 |                                                              |
| newReserveFactorMantissa | VARCHAR   | 250000000000000000                                                 |                                                              |

## 74. Table: cBAT\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-28 18:22:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10355888                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4439550ff01ae4b62d8026e1a1c3dda90c4c931df4fae194208585b03db63650 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x5192c30b8d657ea414d9f059fa7652536b48db1d                         |                                                              |
| redeemAmount      | VARCHAR   | 2248821267322319262338                                             |                                                              |
| redeemTokens      | VARCHAR   | 11055005415239                                                     |                                                              |

## 75. Table: cBAT\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-16 21:12:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10472877                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0e1b35790165fd5c4be8a884364b319a15db4e14d16a345dd15e4db4ebd9c6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x84bf1533a0eb45630d94295df08d6d3a2755a027                         |                                                              |
| borrower          | VARCHAR   | 0x84bf1533a0eb45630d94295df08d6d3a2755a027                         |                                                              |
| repayAmount       | VARCHAR   | 7502272062588034761296                                             |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 3991895044259584980839571                                          |                                                              |

## 76. Table: cBAT\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-15 15:50:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14392066                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea39d84e89e588652d984d5f478c994305aa099507e1edf15af5d820c2e8b577 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xb02592a0d7726b91345983d80ea02a82a661d5eb                         |                                                              |
| to                | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         |                                                              |
| amount            | VARCHAR   | 5286635340814                                                      |                                                              |

## 77. Table: cCOMP\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-08-11 03:11:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 15318260                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xc3ac40f5d82282568c766169927bd95c4156b598b11c891587943fbef8140356 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 945049253278249709555609                                           |                                                              |
| interestAccumulated | VARCHAR   | 370518061633360814                                                 |                                                              |
| borrowIndex         | VARCHAR   | 1122034122846370276                                                |                                                              |
| totalBorrows        | VARCHAR   | 23592759718253092816728                                            |                                                              |

## 78. Table: cCOMP\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-18 00:31:40+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12655200                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea4169eb20600dda1453dacb881398662df3ed7eb522aae35a92541ceee3b2b9             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 268                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x55ca80d688c4ef4b47a44ec517101a54bb6ee202                                     |                                                              |
| spender           | VARCHAR   | 0x681e2a5fa4817233066bbb5f91e0f4a356775a5a                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 79. Table: cCOMP\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-16 07:24:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14396229                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58dadf4bdccaca512f0a193cb65ecc81c8e7d5c7dde6f1c6ce3adfe49c424800 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 358                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xc319bcfd24e50fcf932c98b43bf7ab10460f7ab2                         |                                                              |
| borrowAmount      | VARCHAR   | 4500000000000000000                                                |                                                              |
| accountBorrows    | VARCHAR   | 4500000000000000000                                                |                                                              |
| totalBorrows      | VARCHAR   | 11027835072265585936422                                            |                                                              |

## 80. Table: cCOMP\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-26 08:24:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11332906                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c559ea2490033e5d205ea39f8d9df0ad5037451ffca9042551fc233331b148e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 18                                                                 |                                                              |
| detail            | VARCHAR   | 3                                                                  |                                                              |

## 81. Table: cCOMP\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-06 13:04:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15089085                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x67425390b74a1c5046ff2ec73db709f851bea580fe3730dfd89a95ac66f7f83d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 356                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x625d6d3f3b375e686642dc8d1d438ac58058d09c                         |                                                              |
| borrower          | VARCHAR   | 0xe5934eb6d421cb62ebd74c9d0e336286f09caba2                         |                                                              |
| repayAmount       | VARCHAR   | 4673374946072523                                                   |                                                              |
| cTokenCollateral  | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         |                                                              |
| seizeTokens       | VARCHAR   | 1026746                                                            |                                                              |

## 82. Table: cCOMP\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-10 16:22:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13199069                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x548a1acc28c2734dceb55cab77f7b14be973c2952552f632f6bef535dc64e556 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 30                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x74aa9d1656686cf992594e4121df59ed776c2e51                         |                                                              |
| mintAmount        | VARCHAR   | 142982210000000000                                                 |                                                              |
| mintTokens        | VARCHAR   | 703157527                                                          |                                                              |

## 83. Table: cCOMP\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 84. Table: cCOMP\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-29 22:41:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10960099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x367f85b32d8c33698b5dc95f0ce6fb0c583e25f67c6e929755616ef6ae056a84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 85. Table: cCOMP\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-29 22:41:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10960099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x367f85b32d8c33698b5dc95f0ce6fb0c583e25f67c6e929755616ef6ae056a84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newImplementation | VARCHAR   | 0x338f7e5d19d9953b76dd81446b142c2d9fe03482                         |                                                              |

## 86. Table: cCOMP\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-10-24 10:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 15817508                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x51c80043827a7c84a537b110ad278929c597067d93035e57d478ce39c787db3d | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0xd956188795ca6f4a74092ddca33e0ea4ca3a1395                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xd88b94128ff2b8cf2d7886cd1c1e46757418ca2a                         |                                                              |

## 87. Table: cCOMP\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 88. Table: cCOMP\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2020-10-17 09:17:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 11072572                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xedb643b35ea58bb570489c205ba122ae9d9412ce117714f38507fbb65e784160 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 200000000000000000                                                 |                                                              |

## 89. Table: cCOMP\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 21:26:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11850687                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1acb2ec47cd7385df7576751553daae08e51ad29ca8ecb5d711a39d7d3e1f35 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 161                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x9d50a80609aae214b8d6c34fbbd010a9d4769a76                         |                                                              |
| redeemAmount      | VARCHAR   | 395000000000000000000                                              |                                                              |
| redeemTokens      | VARCHAR   | 1954394044945                                                      |                                                              |

## 90. Table: cCOMP\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-25 02:50:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11324961                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd448a426a53f7e492a26cf0297cf0c6d5457867da80ce8398af1c3b60f6cad85 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 250                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x6666d278005f1e983b076909ff0e0f9ceb1d40ae                         |                                                              |
| borrower          | VARCHAR   | 0x6666d278005f1e983b076909ff0e0f9ceb1d40ae                         |                                                              |
| repayAmount       | VARCHAR   | 708749733486359000                                                 |                                                              |
| accountBorrows    | VARCHAR   | 15618305576536                                                     |                                                              |
| totalBorrows      | VARCHAR   | 39975925927724364987555                                            |                                                              |

## 91. Table: cCOMP\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 19:28:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17246040                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa782279e54120a73013f54748462d89c071365a2c6313e6d752122ce71da9410 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         |                                                              |
| addAmount         | VARCHAR   | 2729754852295662237                                                |                                                              |
| newTotalReserves  | VARCHAR   | 3272248469746016916085                                             |                                                              |

## 92. Table: cCOMP\_event\_ReservesReduced\_history

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

## 93. Table: cCOMP\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-29 05:22:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12918863                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7b7a3b78350c8ef3d962991298494e9767bb81f0929724f9894fd6d5b51f552 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0309c98b1bffa350bcb3f9fb9780970ca32a5060                         |                                                              |
| to                | VARCHAR   | 0x0d6af0a4fcd387182ca106270794d81477f6dffd                         |                                                              |
| amount            | VARCHAR   | 103635820354                                                       |                                                              |

## 94. Table: cDAI\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-08-04 23:30:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17844907                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x4ff1d2bb9b3f385ccb5330f92f0f57938ffe1cd57f8ad79b55d9f357beef4170 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 85                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 69245015833649312559151103                                         |                                                              |
| interestAccumulated | VARCHAR   | 271546814383400250695                                              |                                                              |
| borrowIndex         | VARCHAR   | 1180867095168113377                                                |                                                              |
| totalBorrows        | VARCHAR   | 194426078874181805837133400                                        |                                                              |

## 95. Table: cDAI\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-01 06:56:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9784488                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c0dae7edf149ff34e97fda453c90a725021c5d41dd1dd23b5110617518945af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3560a1450c12eb04cdda3344a6760eb1a5e9140e                         |                                                              |
| spender           | VARCHAR   | 0x0af5d0723708587ff94ad29f937d6da5d357748f                         |                                                              |
| amount            | VARCHAR   | 68144915946                                                        |                                                              |

## 96. Table: cDAI\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-30 06:10:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12733671                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03bcd9904889c89309c118770729c2535518f1fd13963a1e809317637bc07178 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xb3b066eb361efc6634fb48fc8dc8b23518f19ac2                         |                                                              |
| borrowAmount      | VARCHAR   | 1160462831330165832214                                             |                                                              |
| accountBorrows    | VARCHAR   | 13762501540999823456055                                            |                                                              |
| totalBorrows      | VARCHAR   | 1318223276443989191889006088                                       |                                                              |

## 97. Table: cDAI\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 08:23:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13688682                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9183c7d810fb8398860296bab4eece67c91abcefc5738dbefe471482537c1b1e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 18                                                                 |                                                              |
| detail            | VARCHAR   | 3                                                                  |                                                              |

## 98. Table: cDAI\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-13 05:22:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14195843                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2ea3588f8848bbeef11cb524bda1467a358a92075ba7a6f880c31008f0a2e24 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 335                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0xd911560979b78821d7b045c79e36e9cbfc2f6c6f                         |                                                              |
| borrower          | VARCHAR   | 0xf63d29b67aabbafa772c51e29dc7a89d391cfa7e                         |                                                              |
| repayAmount       | VARCHAR   | 503086143770381194752                                              |                                                              |
| cTokenCollateral  | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         |                                                              |
| seizeTokens       | VARCHAR   | 929219727                                                          |                                                              |

## 99. Table: cDAI\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-13 09:23:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13015977                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d9954b195734f346bedcc23fa2b0209a8154f76bdd87ce2d3f032fed495e3c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| mintAmount        | VARCHAR   | 2647071922973183049728                                             |                                                              |
| mintTokens        | VARCHAR   | 12280550977834                                                     |                                                              |

## 100. Table: cDAI\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-23 01:03:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8983575                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x090ce7d33359e5d288ce169f41bb3d2cb55ac17b026a10cf80b3fc4f0c85c827 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 101. Table: cDAI\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-23 01:03:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8983575                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x090ce7d33359e5d288ce169f41bb3d2cb55ac17b026a10cf80b3fc4f0c85c827 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newImplementation | VARCHAR   | 0x99ee778b9a6205657dd03b2b91415c8646d521ec                         |                                                              |

## 102. Table: cDAI\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-12-20 00:26:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 9133122                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x20d692e5986096498627dae978dde8b40b2354aec47a4e901d68010b22f2b261 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x5562024784cc914069d67d89a28e3201bf7b57e7                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xec163986cc9a6593d6addcbff5509430d348030f                         |                                                              |

## 103. Table: cDAI\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2020-12-12 14:10:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 11438576                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x72198c8f10a1958aa97b2f1408700209a14e026e81fabba866e03668e5879c8d | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 50000000000000000                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 150000000000000000                                                 |                                                              |

## 104. Table: cDAI\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-10 18:02:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9456658                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x780e5ab90e39fc4cb72a44f96e15cacfbb847d673810e8f200c8ecc6382e070a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x025f1077bbb98b248c40ad3183d9f229198fb4fe                         |                                                              |
| redeemAmount      | VARCHAR   | 124656968510433612036                                              |                                                              |
| redeemTokens      | VARCHAR   | 617149367619                                                       |                                                              |

## 105. Table: cDAI\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 17:55:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13778867                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5c5acbd5b07f12b28b39e8493a5b700dd1dffdceef63e2500e787aca7da0cb6e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x20724a43172535118863d8c6e84f523ae6aa34ed                         |                                                              |
| borrower          | VARCHAR   | 0x20724a43172535118863d8c6e84f523ae6aa34ed                         |                                                              |
| repayAmount       | VARCHAR   | 101475735511553978905303                                           |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 3716909285766350932772515242                                       |                                                              |

## 106. Table: cDAI\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-04 08:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15895593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb156b62affc99ba87de7699fdb3d6a0a3c4966647118f05d1d4e68711ddd527 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 164                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         |                                                              |
| addAmount         | VARCHAR   | 241439150896042951                                                 |                                                              |
| newTotalReserves  | VARCHAR   | 21357711828629912619625051                                         |                                                              |

## 107. Table: cDAI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-14 02:14:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11253068                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x73b6c4e39cb1b695f47fa6c13de38901b04c5ba75f3d6b62300e2603ae2ad250 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xfee3da0c35702c3289c9bbf170898a549fbed29e                         |                                                              |
| to                | VARCHAR   | 0x141fef8cd8397a390afe94846c8bd6f4ab981c48                         |                                                              |
| amount            | VARCHAR   | 4506088935761                                                      |                                                              |

## 108. Table: cETH\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-08-19 15:17:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 15372032                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x55fb471b0c6f78086616f151c552227b9b8f4f5e67912e885f4f23564133ac24 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| interestAccumulated | VARCHAR   | 7743771562630588                                                   |                                                              |
| borrowIndex         | VARCHAR   | 1092935211195686010                                                |                                                              |
| totalBorrows        | VARCHAR   | 15591373828018818404652                                            |                                                              |

## 109. Table: cETH\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 18:49:47+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16356805                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b3074d6b629e161494dc58cac3115191c2fc4b20da36f885c6aefc22364c51e             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x00d5c81473241a08fc36ea6ad64dd9571363657a                                     |                                                              |
| spender           | VARCHAR   | 0x68b3465833fb72a70ecdf485e0e4c7bd8665fc45                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 110. Table: cETH\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 04:39:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13618280                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d00ef361a3e221d6d3f4f95372e15183343b1d0b668b77f89380d476043298f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x99fd1378ca799ed6772fe7bcdc9b30b389518962                         |                                                              |
| borrowAmount      | VARCHAR   | 40000000000000000000                                               |                                                              |
| accountBorrows    | VARCHAR   | 40000000000000000000                                               |                                                              |
| totalBorrows      | VARCHAR   | 54439859044462716990951                                            |                                                              |

## 111. Table: cETH\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-30 19:11:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12737195                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca3193eb5a6267132dad6561a7ea21da5515c5542573e87fefaa093adbf7ed51 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 2                                                                  |                                                              |
| info              | VARCHAR   | 75                                                                 |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 112. Table: cETH\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-09 09:07:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17221902                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x00140da034ec8808ab7e9cc2f1954b55c408c8059f6ac8beb76c32d1b1bada88 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x6ee33c4a192118ea664612aec6f7b6e4aef78b87                         |                                                              |
| borrower          | VARCHAR   | 0x46ba9970e469a212084527aeb321c3f3ed53d9be                         |                                                              |
| repayAmount       | VARCHAR   | 388352070264856709                                                 |                                                              |
| cTokenCollateral  | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         |                                                              |
| seizeTokens       | VARCHAR   | 17264647073172                                                     |                                                              |

## 113. Table: cETH\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 11:04:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15370896                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x779f0372f101bd5c38d5859f7ff004f0b69e3d4151086539c7489c77d21a077e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 363                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x05fe5507da021d3df44d7d28519e69c77c5cf879                         |                                                              |
| mintAmount        | VARCHAR   | 1000000000000000                                                   |                                                              |
| mintTokens        | VARCHAR   | 4983333                                                            |                                                              |

## 114. Table: cETH\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 02:25:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7711026                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f182cfe347e5373c311f9d76b5a2562e0074baae7bf8a5a88c2c99a24ef8094 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0xa7ff0d561cd15ed525e31bbe0af3fe34ac2059f6                         |                                                              |
| newAdmin          | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |

## 115. Table: cETH\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 01:25:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7710758                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe60e30c7131f043b17a214cfa27e7b6ae652e056141ae84bc4cc3dfe17e016a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 116. Table: cETH\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-05-07 01:25:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 7710758                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xe60e30c7131f043b17a214cfa27e7b6ae652e056141ae84bc4cc3dfe17e016a3 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xc64c4cba055efa614ce01f4bad8a9f519c4f8fab                         |                                                              |

## 117. Table: cETH\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 02:24:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7711021                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d0e7e5bbe2f2e3980f844937965f8e875b7e4216d74b85d7077b33b12761790 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |

## 118. Table: cETH\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2019-05-07 01:27:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 7710769                                                            | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x993f40d11754d20296538074d6ca256f4a7d6b41c1082f9317033ef1df18e5a2 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 100000000000000000                                                 |                                                              |

## 119. Table: cETH\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-05 04:22:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8487894                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7bac56d5057f0d9a7e21ab85de72af6f741c685a04fc95aa05ccf86483e7a077 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x04583e7b1a7f3bf06c45382065f7bd0a8741627d                         |                                                              |
| redeemAmount      | VARCHAR   | 24425530711919765                                                  |                                                              |
| redeemTokens      | VARCHAR   | 122073994                                                          |                                                              |

## 120. Table: cETH\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-13 02:35:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11044583                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe02f15812fb45e29b9e447b1d1e2374751e4b6174f126534b3657b2224d48508 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 320                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x0be4b1633bc2e673289e1f708d16bf3218f4a118                         |                                                              |
| borrower          | VARCHAR   | 0x0be4b1633bc2e673289e1f708d16bf3218f4a118                         |                                                              |
| repayAmount       | VARCHAR   | 300000000000000000                                                 |                                                              |
| accountBorrows    | VARCHAR   | 2602390350724790080                                                |                                                              |
| totalBorrows      | VARCHAR   | 75958762536275010470973                                            |                                                              |

## 121. Table: cETH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-02 05:34:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13144442                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65b291fe40c73d68a03141fbfdff8b881ea56076f7a4f82ec0730d0b2388b940 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 184                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x000000f15851d0875e878a83451163999bf5da51                         |                                                              |
| to                | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         |                                                              |
| amount            | VARCHAR   | 574172732506                                                       |                                                              |

## 122. Table: cLINK\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-08-03 02:51:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17831607                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xfed96f8e6ac9428fd343de7b84b1008b087c340a274432941d170c08ed18a2bd | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 289                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 431779475875906006455375                                           |                                                              |
| interestAccumulated | VARCHAR   | 21303347596758949                                                  |                                                              |
| borrowIndex         | VARCHAR   | 1120834242170136175                                                |                                                              |
| totalBorrows        | VARCHAR   | 6520459723714254169515                                             |                                                              |

## 123. Table: cLINK\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-06 19:49:11+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16991717                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f4cf2da33b0826d933e079b5ff5aa26b103189590f557a4de976cfed896f864             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x302037d4f06c4258d742428a78e1f3774d58bb70                                     |                                                              |
| spender           | VARCHAR   | 0xe66b31678d6c16e9ebf358268a790b763c133750                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 124. Table: cLINK\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-24 22:18:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13291106                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf4d763305611e47c12c38ca3301a9e373f1d9f465284b89efdcabedfea24d002 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xaa5c4dea076e3a912fde4215ea425ac404802ff4                         |                                                              |
| borrowAmount      | VARCHAR   | 93284003801754200000                                               |                                                              |
| accountBorrows    | VARCHAR   | 93284003801754200000                                               |                                                              |
| totalBorrows      | VARCHAR   | 853492703613911313930340                                           |                                                              |

## 125. Table: cLINK\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-05 02:59:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12962496                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4437d1057b1d573dbd10a9619143a0a4c563a0f9cddf4bd62fc212ed3ab3dd6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 14                                                                 |                                                              |
| detail            | VARCHAR   | 4                                                                  |                                                              |

## 126. Table: cLINK\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-24 07:35:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12887725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60c531996505b37f9b3346778c3bac638652f16149feb2d37bd41e8b7f29f4dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0xe0090ec6895c087a393f0e45f1f85098a6c33bef                         |                                                              |
| borrower          | VARCHAR   | 0x6e832c7002101ebd201efd863ee826a96caeff88                         |                                                              |
| repayAmount       | VARCHAR   | 27241402305232368293                                               |                                                              |
| cTokenCollateral  | VARCHAR   | 0x70e36f6bf80a52b3b46b3af8e106cc0ed743e8e4                         |                                                              |
| seizeTokens       | VARCHAR   | 6062937619                                                         |                                                              |

## 127. Table: cLINK\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-24 17:29:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13289813                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39f83c04b07e0fd7d5baca5d9b43b2ef9a6c5073cc5caf19107c380edce6080b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0xafe6600f85c28a143858defb1eb4439f93f56cc9                         |                                                              |
| mintAmount        | VARCHAR   | 200106241183146959469                                              |                                                              |
| mintTokens        | VARCHAR   | 997531055862                                                       |                                                              |

## 128. Table: cLINK\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 129. Table: cLINK\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-21 21:38:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12286030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa05f057356e6cf40ad05dedd81f35660f0cd17c0344f3a2c32e464a502363011 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 130. Table: cLINK\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-28 19:52:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12724484                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x694de552980bc831eaf3c44dc4f8107fba6823e3a1293ea3a4816c309ea8eb39 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 252                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x24aa720906378bb8364228bddb8cabbc1f6fe1ba                         |                                                              |
| newImplementation | VARCHAR   | 0xa035b9e130f2b1aedc733eefb1c67ba4c503491f                         |                                                              |

## 131. Table: cLINK\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-04-21 21:38:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12286030                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xa05f057356e6cf40ad05dedd81f35660f0cd17c0344f3a2c32e464a502363011 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xd956188795ca6f4a74092ddca33e0ea4ca3a1395                         |                                                              |

## 132. Table: cLINK\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 133. Table: cLINK\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-05-22 18:39:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 12485775                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x461fdf40adb6ca7079cd5a901ef427b3d4d7f8eb10cd3109bf90005744d375c7 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 250000000000000000                                                 |                                                              |

## 134. Table: cLINK\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 09:59:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14158260                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf4bbaef4da5f133be663f453dd23b00bc8e44ae5fc1183a10f3be117bfc9f7bf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xe46bb685df9eac4ed3004ef326199eecdaaf6a53                         |                                                              |
| redeemAmount      | VARCHAR   | 397314077647133762838                                              |                                                              |
| redeemTokens      | VARCHAR   | 1976542927089                                                      |                                                              |

## 135. Table: cLINK\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-12 16:33:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12620725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xad34dfa0dd548d2c38cc2f906d151e939d394836f8c2f5f8ab725f23056d5463 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 420                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x779ed3c5e32569ee2f18f88005619134bd42073e                         |                                                              |
| borrower          | VARCHAR   | 0x779ed3c5e32569ee2f18f88005619134bd42073e                         |                                                              |
| repayAmount       | VARCHAR   | 7500000000000000000000                                             |                                                              |
| accountBorrows    | VARCHAR   | 8045471043812276220                                                |                                                              |
| totalBorrows      | VARCHAR   | 397582669334086496366558                                           |                                                              |

## 136. Table: cLINK\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-08 19:28:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17217852                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba57c8b2bbbedb9972ad8a1da7f0efffd6ca258d3f54a0ffdf15981b81703347 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         |                                                              |
| addAmount         | VARCHAR   | 12646559017678128407                                               |                                                              |
| newTotalReserves  | VARCHAR   | 11939394363027746359788                                            |                                                              |

## 137. Table: cLINK\_event\_ReservesReduced\_history

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

## 138. Table: cLINK\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 19:02:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13641064                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1e510f68540d4843a80f5702933ad6787246f715471fa7ae43a25ac93865319f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         |                                                              |
| to                | VARCHAR   | 0xcf61e8634a1c69c1612b2772400a447566e51184                         |                                                              |
| amount            | VARCHAR   | 17523399405                                                        |                                                              |

## 139. Table: cMKR\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-04-01 11:24:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 16953985                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x33ab95db9e5a6d040efeb33964f71a6cf6d87b7d41e1f810edd6196e264dedab | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 482350979150320183620                                              |                                                              |
| interestAccumulated | VARCHAR   | 428030693721276                                                    |                                                              |
| borrowIndex         | VARCHAR   | 1058098237085085165                                                |                                                              |
| totalBorrows        | VARCHAR   | 994502327377626460                                                 |                                                              |

## 140. Table: cMKR\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 00:29:59+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17382413                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85794f16217f00bd024625b78fd7d78fe87a56783cd3241cb384b7137ce8636f             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 301                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0000e0ca771e21bd00057f54a68c30d400000000                                     |                                                              |
| spender           | VARCHAR   | 0xd82fa167727a4dc6d6f55830a2c47abbb4b3a0f8                                     |                                                              |
| amount            | VARCHAR   | 115339776388732929035197660848497720713218148788040405586178452820382218977280 |                                                              |

## 141. Table: cMKR\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-21 10:00:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13657498                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x71d2cef27d3e1a19c0ee692c4274149236a4eceadcc38b321c70f22f65cf8fd2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x57ef012861c4937a76b5d6061be800199a2b9100                         |                                                              |
| borrowAmount      | VARCHAR   | 200000000000000000000                                              |                                                              |
| accountBorrows    | VARCHAR   | 200000000000000000000                                              |                                                              |
| totalBorrows      | VARCHAR   | 200053369622584484349                                              |                                                              |

## 142. Table: cMKR\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-04 12:34:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12958656                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x00f8f7fc860de1efe2caad03322fb3a8cf975054d511120f1d04ee16b69d0069 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 14                                                                 |                                                              |
| info              | VARCHAR   | 9                                                                  |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 143. Table: cMKR\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-14 20:31:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17480568                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0753d305e4c4385917b7ce11b2578f218859bff85b46c927a803f2fca3d15dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 85                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0xda7d7a4640dfd472d243dceadf40d0e1db891afb                         |                                                              |
| borrower          | VARCHAR   | 0x69353c7fe37875c0f83dc7170428ef8184a15914                         |                                                              |
| repayAmount       | VARCHAR   | 252850000000000030                                                 |                                                              |
| cTokenCollateral  | VARCHAR   | 0x4ddc2d193948926d02f9b1fe9e1daa0718270ed5                         |                                                              |
| seizeTokens       | VARCHAR   | 511829679                                                          |                                                              |

## 144. Table: cMKR\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-07 09:02:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13757648                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x531ed5944dd33f760a9860db4c52ed87caeaff729995342b6a47a9218178f9bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0xe5e8506a590766d738d80affc6b5e538c4b92f82                         |                                                              |
| mintAmount        | VARCHAR   | 49972418092842694                                                  |                                                              |
| mintTokens        | VARCHAR   | 249642858                                                          |                                                              |

## 145. Table: cMKR\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 146. Table: cMKR\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-16 05:30:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12836064                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e5169b835cfe53007687173a469cd8286f5b7d8c9c70a503a5bf1e922664998 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 147. Table: cMKR\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-25 04:08:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14651607                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4c9a72cafbac174c2935d78bf39f1483781a1a95a25c7f549eb72632c96f2e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 487                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0xa035b9e130f2b1aedc733eefb1c67ba4c503491f                         |                                                              |
| newImplementation | VARCHAR   | 0x3363bae2fc44da742df13cd3ee94b6bb868ea376                         |                                                              |

## 148. Table: cMKR\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-07-16 05:30:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12836064                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x6e5169b835cfe53007687173a469cd8286f5b7d8c9c70a503a5bf1e922664998 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xd956188795ca6f4a74092ddca33e0ea4ca3a1395                         |                                                              |

## 149. Table: cMKR\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 150. Table: cMKR\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-08-03 02:21:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 12949662                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xbaa41f11e7f06d003f442aa45be3a7671e59ecc9aeeee4752f11c005e8ca2295 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 250000000000000000                                                 |                                                              |

## 151. Table: cMKR\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-05 07:38:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14144675                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab59ba8d9ecdb6382a5f175a194d417b49e436689bd9c7c0caaa08735ee60724 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 346                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x48edf93fb962d737e46ec3e1b3402e919bd2f00b                         |                                                              |
| redeemAmount      | VARCHAR   | 175800000000000000000                                              |                                                              |
| redeemTokens      | VARCHAR   | 878219954500                                                       |                                                              |

## 152. Table: cMKR\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-28 22:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16071334                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f2c2efcc842a59d5cafc639354471d3da787bcc1af4953c612d099c49f4b0a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 347                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x8333c1b5131cc694c3a238e41e50cbc236e73dbc                         |                                                              |
| borrower          | VARCHAR   | 0x8333c1b5131cc694c3a238e41e50cbc236e73dbc                         |                                                              |
| repayAmount       | VARCHAR   | 202100540000000000                                                 |                                                              |
| accountBorrows    | VARCHAR   | 51715907634                                                        |                                                              |
| totalBorrows      | VARCHAR   | 131240499615291607437                                              |                                                              |

## 153. Table: cMKR\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-08 17:14:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13966069                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x675f1c0edfbef48f25130106219acf332acda4de5941fff53e28749a3363413f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         |                                                              |
| addAmount         | VARCHAR   | 200566614038006991                                                 |                                                              |
| newTotalReserves  | VARCHAR   | 401783019522052494                                                 |                                                              |

## 154. Table: cMKR\_event\_ReservesReduced\_history

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

## 155. Table: cMKR\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-18 02:50:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13247128                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x751a34ab107a985ac6c185a524388932b667a7ac459cc06e7f290cd5344794d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x95b4ef2869ebd94beb4eee400a99824bf5dc325b                         |                                                              |
| to                | VARCHAR   | 0x1f63475e6aa6ad3cb182a2509264735f9db5b12f                         |                                                              |
| amount            | VARCHAR   | 20695436301                                                        |                                                              |

## 156. Table: cREP\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-06-16 16:33:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 7970621                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x1076be12f6d272e04d73089a397ccf1e7698a66efcd33a443bc608cc3475647a | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| interestAccumulated | VARCHAR   | 27391565549037346                                                  |                                                              |
| borrowIndex         | VARCHAR   | 1006216197759421467                                                |                                                              |
| totalBorrows        | VARCHAR   | 4242128217390206639927                                             |                                                              |

## 157. Table: cREP\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-11 15:57:23+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9651156                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x57ea6572389880addc76770d02754329cfa5734ec534ab308c71aa3f878d1db4             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x25aa942412588b55b490f4799980ed51e2aeedd0                                     |                                                              |
| spender           | VARCHAR   | 0x749fcdf919cd3ff2e2f2a09f505c0c1ccddc169a                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 158. Table: cREP\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-08 04:14:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8699119                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc002aaf4d6d15426ca62115313067f5e27b7150f8afda3a9e0c45fa0672e034 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x03d4695df4b8d321d31c94de8f430e3450f50498                         |                                                              |
| borrowAmount      | VARCHAR   | 11000000000000000000                                               |                                                              |
| accountBorrows    | VARCHAR   | 54210531466753650445                                               |                                                              |
| totalBorrows      | VARCHAR   | 6493985376449471506083                                             |                                                              |

## 159. Table: cREP\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-25 21:51:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9944157                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3a3ffeb370f9acb78742b9d5465cb92a80196fee03efa6db1f35947fcd90e899 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 111                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 13                                                                 |                                                              |
| info              | VARCHAR   | 38                                                                 |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 160. Table: cREP\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-04 17:02:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9417363                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x612f87e92ac42abb190e6f4400792996d59d4d15f8d4180924dabf826cfac96d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x00e36307236118b7d5ff9e1fa3a2506fd5257b8a                         |                                                              |
| borrower          | VARCHAR   | 0x40335581dd8692b698762168908d4ea23b0b94f9                         |                                                              |
| repayAmount       | VARCHAR   | 6819451856585715712                                                |                                                              |
| cTokenCollateral  | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         |                                                              |
| seizeTokens       | VARCHAR   | 534872943496                                                       |                                                              |

## 161. Table: cREP\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-14 01:03:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9478063                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e6d2aa693bed95aefd8329a99ce3f711efe8a6eb37f050ce9537640a094733a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x40335581dd8692b698762168908d4ea23b0b94f9                         |                                                              |
| mintAmount        | VARCHAR   | 11567062240226005994                                               |                                                              |
| mintTokens        | VARCHAR   | 57731780925                                                        |                                                              |

## 162. Table: cREP\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 19:03:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810842                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9e32717b00003d3ed6229defd06e0bac46788cd51445031a3e8b48247ddfdb6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |
| newAdmin          | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |

## 163. Table: cREP\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 01:24:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7710755                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2fd160cc282c7be223c4fe2370b90fd07485459db0332790c9bf02e4b1fbeaab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 164. Table: cREP\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-05-07 01:24:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 7710755                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x2fd160cc282c7be223c4fe2370b90fd07485459db0332790c9bf02e4b1fbeaab | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xbae04cbf96391086dc643e842b517734e214d698                         |                                                              |

## 165. Table: cREP\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 18:56:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810812                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f3797416dd817f1b2ba5fef2e07010d3e64e67a81b24f82d55cb90bb492312f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |

## 166. Table: cREP\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2019-05-07 01:26:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 7710767                                                            | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x0bb9e9001d471fd30b63bc34a68752452e8d753f055cf6fb02efccdab8990305 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 100000000000000000                                                 |                                                              |

## 167. Table: cREP\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-16 10:40:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9682066                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7bccd2495f95045792cb254277694b4548cae9a875e3c2e9a9baa89bca946268 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xf9e840ae653484ee1ae1463077e7a888bcdfcfd2                         |                                                              |
| redeemAmount      | VARCHAR   | 1000002187109148252                                                |                                                              |
| redeemTokens      | VARCHAR   | 4990991364                                                         |                                                              |

## 168. Table: cREP\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-24 21:37:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9548612                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76841c3de6c7b4d8ab39b1f5e3ac25e92bfe5372e651bc373451dc9e1f98ce5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x7f737d9f92d3d03684d1ee568ff4abf65efac453                         |                                                              |
| borrower          | VARCHAR   | 0x7f737d9f92d3d03684d1ee568ff4abf65efac453                         |                                                              |
| repayAmount       | VARCHAR   | 2982400000000000000                                                |                                                              |
| accountBorrows    | VARCHAR   | 17214153899625                                                     |                                                              |
| totalBorrows      | VARCHAR   | 7669399951234620504969                                             |                                                              |

## 169. Table: cREP\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-05 15:46:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8490949                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x610a5d79c624fecb6b41ae424d6d22b8c66fc30e2c7699cbb77573757c0dae21 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         |                                                              |
| to                | VARCHAR   | 0xaba5ab3a3b1d890a16ee83a3fc7fa5b1502573c6                         |                                                              |
| amount            | VARCHAR   | 5498824453                                                         |                                                              |

## 170. Table: cSAI\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-10-22 02:50:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 8787712                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x094bbbd3b0cde565054cea82f4439468604470306dc799ccd6983c1f697f34ec | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| interestAccumulated | VARCHAR   | 8255572473595241612                                                |                                                              |
| borrowIndex         | VARCHAR   | 1074727811785115646                                                |                                                              |
| totalBorrows        | VARCHAR   | 23310903454118835227948692                                         |                                                              |

## 171. Table: cSAI\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-26 01:35:23+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17340045                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3c3deb30d73e4905c6e63393a793a62a8809649ec0764b1c69884fb4bfa24276             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 323                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x6c5b404785f235bbdd20d29dc934a693f551925d                                     |                                                              |
| spender           | VARCHAR   | 0x881d40237659c251811cec9c364ef91dc08d300c                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 172. Table: cSAI\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-22 11:53:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8790157                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4388a8d66666e6dc0c643135c66f027580c42c1f913dfcb4f7df1040bf483458 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xf466555a017cbda0718d3e3097676cfa0519a1a0                         |                                                              |
| borrowAmount      | VARCHAR   | 10000000000000000                                                  |                                                              |
| accountBorrows    | VARCHAR   | 10000000000000000                                                  |                                                              |
| totalBorrows      | VARCHAR   | 23367876947451217967801136                                         |                                                              |

## 173. Table: cSAI\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-10 02:14:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10429006                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6366293b20f09635504dbee80da8f08892c2c8456ec09eb7e4e3f3dfbdff9ca5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 366                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 2                                                                  |                                                              |
| info              | VARCHAR   | 75                                                                 |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 174. Table: cSAI\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-20 20:22:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8970348                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2bd13038b0636dd924b74f28fceed4e5b8a76e1b99208b073195fb774f92400b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x15fda64fcdbca27a60aa8c6ca882aa3e1de4ea41                         |                                                              |
| borrower          | VARCHAR   | 0x5142126b4573ae1a23e4c8ab2a16631cae725325                         |                                                              |
| repayAmount       | VARCHAR   | 15055743568429616189                                               |                                                              |
| cTokenCollateral  | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         |                                                              |
| seizeTokens       | VARCHAR   | 334226017624                                                       |                                                              |

## 175. Table: cSAI\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-07 04:47:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8888067                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd65fcbdafc804917bcf016566793ef5e9d45901f18f8d704ffb28b78bbc64f4b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x000000f54395c554346bfd24e6a1ccd90b881a4e                         |                                                              |
| mintAmount        | VARCHAR   | 19944815450895761335                                               |                                                              |
| mintTokens        | VARCHAR   | 94876120791                                                        |                                                              |

## 176. Table: cSAI\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 02:26:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7711033                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7fe848449b59c1d5873f55034d215f59e7d196a9607c8c935418cf74287cc773 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0xa7ff0d561cd15ed525e31bbe0af3fe34ac2059f6                         |                                                              |
| newAdmin          | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |

## 177. Table: cSAI\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 01:24:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7710752                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8caa40e8b5227b7a1079a9e883d92de018957e5256f356aa6d28b2610e7b1c44 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 178. Table: cSAI\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-05-07 01:24:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 7710752                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x8caa40e8b5227b7a1079a9e883d92de018957e5256f356aa6d28b2610e7b1c44 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xa1046abfc2598f48c44fb320d281d3f3c0733c9a                         |                                                              |

## 179. Table: cSAI\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 02:22:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7711011                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac071637b4e899a6120d988111b824b4fe00ceda3bcf1077a446371b72d2874c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |

## 180. Table: cSAI\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2019-05-07 01:26:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 7710765                                                            | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xbb57079b94f35270bf0bacd55d6419fdaddfc2611945c9826792c20a1eb8727c | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 100000000000000000                                                 |                                                              |

## 181. Table: cSAI\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-20 05:11:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14994819                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7378c7063e2a440afd5ceb62381902a032d2f1b1d95d58f81fb2bc220422f89a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x11be04c82c55c97597503e27f811baccaa140bc5                         |                                                              |
| redeemAmount      | VARCHAR   | 34596863241826712069                                               |                                                              |
| redeemTokens      | VARCHAR   | 161292582500                                                       |                                                              |

## 182. Table: cSAI\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-29 04:17:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9019180                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4b84002f7346815ab98729506546e47c489e6e2af029ba79c23851b686e22cef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x000000aaee6a496aaf7b7452518781786313400f                         |                                                              |
| borrower          | VARCHAR   | 0x000000aaee6a496aaf7b7452518781786313400f                         |                                                              |
| repayAmount       | VARCHAR   | 7592676886489180250012                                             |                                                              |
| accountBorrows    | VARCHAR   | 155406624831534273928724                                           |                                                              |
| totalBorrows      | VARCHAR   | 10932720905517646841200067                                         |                                                              |

## 183. Table: cSAI\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-20 00:48:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9133215                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0c8054c3c2cc3825cdb5322ef56c95056a86dd458c9921980a135db4e8eba4d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |
| reduceAmount      | VARCHAR   | 100000000000000000000000                                           |                                                              |
| newTotalReserves  | VARCHAR   | 25770079704105919224120                                            |                                                              |

## 184. Table: cSAI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-13 23:24:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10060775                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7dbec63a4b123bd4e6ee98e4a08056c619f4d9c4e76f8e6dbfc231d3f5ea249 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x45a2fdfed7f7a2c791fb1bdf6075b83fad821dde                         |                                                              |
| to                | VARCHAR   | 0x00000000000080c886232e9b7ebbfb942b5987aa                         |                                                              |
| amount            | VARCHAR   | 496298341365                                                       |                                                              |

## 185. Table: cSUSHI\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-06-01 00:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17382358                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x677ca80ec42f44bdf8dea4c7bbcfae1ece310c15e79d53ff68545676d2682b67 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 234                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 3138903915190562975465848                                          |                                                              |
| interestAccumulated | VARCHAR   | 5198164144358838851                                                |                                                              |
| borrowIndex         | VARCHAR   | 1133513347501963494                                                |                                                              |
| totalBorrows        | VARCHAR   | 102509385281618344660251                                           |                                                              |

## 186. Table: cSUSHI\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-25 11:51:48+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13874179                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfbeae77faf8385429aa1a943b1c3b7e2c86e542267d259797f5e25ae80cd6569             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 575                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc4858640a084ec2ff6e01e8dab8eb7868d78937f                                     |                                                              |
| spender           | VARCHAR   | 0x881d40237659c251811cec9c364ef91dc08d300c                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 187. Table: cSUSHI\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-22 11:59:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16025403                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc1f9575fb29441d97bc74566bcbd225829472ccb22427c37f747dc8f546d45c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 490                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xe79fe94ad715d7efcb6dfb1a53051721ac0e7270                         |                                                              |
| borrowAmount      | VARCHAR   | 250000000000000000000                                              |                                                              |
| accountBorrows    | VARCHAR   | 1809031835476274775304                                             |                                                              |
| totalBorrows      | VARCHAR   | 662824835286814516519380                                           |                                                              |

## 188. Table: cSUSHI\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-19 18:52:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14037690                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04bafea33cdb659fc0e2c96c588da554d9d6d32436ab922cdfebc18c82e73aba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 14                                                                 |                                                              |
| info              | VARCHAR   | 9                                                                  |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 189. Table: cSUSHI\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-26 14:42:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15832915                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2273e3fd9c57c9f488842d09b07e42e108cc0eff24675a88e3906c22ea6be1e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x80d4230c0a68fc59cb264329d3a717fcaa472a13                         |                                                              |
| borrower          | VARCHAR   | 0x412a66bdaede5aa901fb125db45c53956a3d835f                         |                                                              |
| repayAmount       | VARCHAR   | 113136471681886982068360                                           |                                                              |
| cTokenCollateral  | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         |                                                              |
| seizeTokens       | VARCHAR   | 915120718312891                                                    |                                                              |

## 190. Table: cSUSHI\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 00:58:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16351474                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0fed2eb89ce96c6eff54a3c5290bee51b2d63cfb62f9cd423dd45858ca4d38f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 259                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x653c053c3ab26eb8d3ce668c1e4608b742c5eeab                         |                                                              |
| mintAmount        | VARCHAR   | 129502370000000000                                                 |                                                              |
| mintTokens        | VARCHAR   | 631624627                                                          |                                                              |

## 191. Table: cSUSHI\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 192. Table: cSUSHI\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-18 03:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12848166                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5401c256787aa50fae65a8e9fdf52cef9cf05bf3a8a502c5b2b5211375185db5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 193. Table: cSUSHI\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-18 03:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12848166                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5401c256787aa50fae65a8e9fdf52cef9cf05bf3a8a502c5b2b5211375185db5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newImplementation | VARCHAR   | 0xa035b9e130f2b1aedc733eefb1c67ba4c503491f                         |                                                              |

## 194. Table: cSUSHI\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-07-18 03:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12848166                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x5401c256787aa50fae65a8e9fdf52cef9cf05bf3a8a502c5b2b5211375185db5 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xd956188795ca6f4a74092ddca33e0ea4ca3a1395                         |                                                              |

## 195. Table: cSUSHI\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 196. Table: cSUSHI\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-08-04 17:53:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 12960086                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xb83ddf4033f61cda65149428c1a247fe516e53d7f762b55ac64a751d1fb3d7ce | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 326                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 250000000000000000                                                 |                                                              |

## 197. Table: cSUSHI\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-17 08:37:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13242183                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x430c7f923ae9a9a017cc2de5084a988733628c0ff03846dd53b916863333c82e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 248                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xbc4bd1f1c6858e16184890b4cd134aee52a35fd5                         |                                                              |
| redeemAmount      | VARCHAR   | 3818673832083229282969                                             |                                                              |
| redeemTokens      | VARCHAR   | 19075683087892                                                     |                                                              |

## 198. Table: cSUSHI\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-10 23:42:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13393903                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe85a8c4399789dbe5854553e9e5df8146e790248fdc834906964a032368725ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x22d1300bba03910ed6cc33ba57bec39d43219fe7                         |                                                              |
| borrower          | VARCHAR   | 0x22d1300bba03910ed6cc33ba57bec39d43219fe7                         |                                                              |
| repayAmount       | VARCHAR   | 50000000000000000000                                               |                                                              |
| accountBorrows    | VARCHAR   | 25288767362885641                                                  |                                                              |
| totalBorrows      | VARCHAR   | 1807170545437599527707                                             |                                                              |

## 199. Table: cSUSHI\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-10 13:21:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13198222                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x53a19a90dbbc5634dae480fe1d17440b0fead2ddde5e32b4e2f5319e9669ef6a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         |                                                              |
| addAmount         | VARCHAR   | 44970630547235516509                                               |                                                              |
| newTotalReserves  | VARCHAR   | 60053617742416987675                                               |                                                              |

## 200. Table: cSUSHI\_event\_ReservesReduced\_history

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

## 201. Table: cSUSHI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-21 12:53:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14049027                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85dcbb142df192f9a9529f44090a4c5f0726ff9f49ea9c3310962d3500cb1b15 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x4b0181102a0112a2ef11abee5563bb4a3176c9d7                         |                                                              |
| to                | VARCHAR   | 0x73372fd360663a0688c7db7017331495a192f28a                         |                                                              |
| amount            | VARCHAR   | 13706048804479                                                     |                                                              |

## 202. Table: cTUSD\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-05-27 12:31:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17350402                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x9f43d453b09244a6b8401f4b9e7e7c374ea683f5e03d6f02be658842073e64b0 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 333708547757978948512872                                           |                                                              |
| interestAccumulated | VARCHAR   | 173316553271629872079                                              |                                                              |
| borrowIndex         | VARCHAR   | 1085954424426531745                                                |                                                              |
| totalBorrows        | VARCHAR   | 524198264305054842033041                                           |                                                              |

## 203. Table: cTUSD\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-03 00:21:47+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17609857                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdfba196fefeb5c414aeeecdc36587e304561a3555248b5b695ea5196b6c9da4f             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x5192a2278aa4223070ee9fe4098e7f6e8bd8ddcc                                     |                                                              |
| spender           | VARCHAR   | 0x40aa958dd87fc8305b97f2ba922cddca374bcd7f                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 204. Table: cTUSD\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-24 13:16:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13868116                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2920db02f1d56709111070b8e683dec3e3097c35765dba1816b2dda8bf81ceb1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xb13c4878c03374c1019bcfa90f2c87f633f1aa8d                         |                                                              |
| borrowAmount      | VARCHAR   | 100000000000000000                                                 |                                                              |
| accountBorrows    | VARCHAR   | 100000000000000000                                                 |                                                              |
| totalBorrows      | VARCHAR   | 48637976047038650845188022                                         |                                                              |

## 205. Table: cTUSD\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-24 19:13:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12498853                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2cbf665fd6a47dc8b7cef9e04c1d241fbf5f33c613ad39afe89a2b7d729f9e45 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 14                                                                 |                                                              |
| detail            | VARCHAR   | 4                                                                  |                                                              |

## 206. Table: cTUSD\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-13 23:47:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14770396                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d88ae976cdd22a6a9dd08246cc55e03836ae690814e7b895949c28a12332c04 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x6ee33c4a192118ea664612aec6f7b6e4aef78b87                         |                                                              |
| borrower          | VARCHAR   | 0x4a8f4017d34fd7d23ba4c64107a041d94348ee6a                         |                                                              |
| repayAmount       | VARCHAR   | 1253687618869425810386                                             |                                                              |
| cTokenCollateral  | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         |                                                              |
| seizeTokens       | VARCHAR   | 17839695804571                                                     |                                                              |

## 207. Table: cTUSD\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 17:41:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17033466                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0476b61e4b7d0bdcca1cd483de2973f1925e86278342a400d61d076ff9ef7c33 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x4ba70b22891c85936d4950f451140b844b7966e3                         |                                                              |
| mintAmount        | VARCHAR   | 4232395864550000000000                                             |                                                              |
| mintTokens        | VARCHAR   | 20327349997775                                                     |                                                              |

## 208. Table: cTUSD\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 209. Table: cTUSD\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-07 11:45:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11008385                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4c88ed5b09b30e55dcb102c1d03af953c2516e79105fd45dafccaf21484ac52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 210. Table: cTUSD\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-25 04:08:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14651607                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4c9a72cafbac174c2935d78bf39f1483781a1a95a25c7f549eb72632c96f2e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 493                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0xa035b9e130f2b1aedc733eefb1c67ba4c503491f                         |                                                              |
| newImplementation | VARCHAR   | 0x3363bae2fc44da742df13cd3ee94b6bb868ea376                         |                                                              |

## 211. Table: cTUSD\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2020-10-07 11:45:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 11008385                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xa4c88ed5b09b30e55dcb102c1d03af953c2516e79105fd45dafccaf21484ac52 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xfb564da37b41b2f6b6edcc3e56fbf523bd9f2012                         |                                                              |

## 212. Table: cTUSD\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 213. Table: cTUSD\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-05-21 17:41:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 12479085                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x2ecc4f0e36bd8146ad6ae9375033bbdde32f23d9cdac387440bc737ca30b31f0 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 75000000000000000                                                  |                                                              |

## 214. Table: cTUSD\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 03:17:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17425785                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf194aa7eae4f1da088b7c0224dbcb7e1bab3adb75d7f6bc75a610ba17817538c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xb99cc7e10fe0acc68c50c7829f473d81e23249cc                         |                                                              |
| redeemAmount      | VARCHAR   | 237021316259301694754                                              |                                                              |
| redeemTokens      | VARCHAR   | 1119904178708                                                      |                                                              |

## 215. Table: cTUSD\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-01 20:46:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14502599                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03f61dc57840117275a8929a9da41ad1fcf1b053fa34bda3fc1d35e1c438c40b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 633                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x26c04bc43dd9262e1dc2ee644ee07d0aaba46864                         |                                                              |
| borrower          | VARCHAR   | 0x26c04bc43dd9262e1dc2ee644ee07d0aaba46864                         |                                                              |
| repayAmount       | VARCHAR   | 755007509776632966387742                                           |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 47851045738091654692949925                                         |                                                              |

## 216. Table: cTUSD\_event\_ReservesAdded\_history

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

## 217. Table: cTUSD\_event\_ReservesReduced\_history

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

## 218. Table: cTUSD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 03:11:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15318262                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x15374a4ae1db5113fbe0884452b3c1ce3e238473bea5c5e78c64c85f759bc267 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xb99cc7e10fe0acc68c50c7829f473d81e23249cc                         |                                                              |
| to                | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         |                                                              |
| amount            | VARCHAR   | 21945003264030638                                                  |                                                              |

## 219. Table: cToken\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-02-11 21:45:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 14187285                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xb3081f0573eb61034ee3c69d39427f15c22fa3150948c5c399e83aecea5ab9fa | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 2811462405912                                                      |                                                              |
| interestAccumulated | VARCHAR   | 645839                                                             |                                                              |
| borrowIndex         | VARCHAR   | 1041504323307167243                                                |                                                              |
| totalBorrows        | VARCHAR   | 109483311457                                                       |                                                              |

## 220. Table: cToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 07:39:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15559002                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43416eee60ed1ea45d9b3251fb62cc88157920947d0c57bf79e9974896634375 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 234                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xe66b31678d6c16e9ebf358268a790b763c133750                         |                                                              |
| spender           | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         |                                                              |
| amount            | VARCHAR   | 32823763388                                                        |                                                              |

## 221. Table: cToken\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-28 19:31:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12724387                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35068d6fd19002bb163bcd4676a61b69b6ecc2370f5dd3b4f0e06db1abed4871 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 218                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12392f67bdf24fae0af363c24ac620a2f67dad86                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x193b04617800323922f963c97d92377c588da996                         |                                                              |
| borrowAmount      | VARCHAR   | 600519402279273984523                                              |                                                              |
| accountBorrows    | VARCHAR   | 600519402279273984523                                              |                                                              |
| totalBorrows      | VARCHAR   | 85833153078292054929146769                                         |                                                              |

## 222. Table: cToken\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-29 18:42:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8645358                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb432e7df9b2c9d45aefd0f910deaac64445d27ee9131e3b37b284cca06769b1e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5dce57282a584d2746faf1593d3121fcac444dc                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x10aab4b0ef76aa2ac9b5909e671517a1171b050e                         |                                                              |
| borrower          | VARCHAR   | 0x6a84c6bff095d29d9618ea0b3fa6bacb37e640e6                         |                                                              |
| repayAmount       | VARCHAR   | 55494004441285900000                                               |                                                              |
| cTokenCollateral  | VARCHAR   | 0x6c8c6b02e7b2be14d4fa6022dfd6d75921d90e4e                         |                                                              |
| seizeTokens       | VARCHAR   | 1865127052926                                                      |                                                              |

## 223. Table: cToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-24 16:48:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9156663                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe722f9a8219496a3b30c8be7ac138e41a5e791cd77eda7f93bdee1e4dfd8a868 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x7d9dd81ac0447af79b3a60cde49738730eb077e6                         |                                                              |
| mintAmount        | VARCHAR   | 25005455617796317623                                               |                                                              |
| mintTokens        | VARCHAR   | 124805275786                                                       |                                                              |

## 224. Table: cToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-05 22:02:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8492601                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7f051f5f7a9bc20d1e1bc2c83bfa3d27454b141cef95bf79a62a18ac38274b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x158079ee67fce2f58472a96584a73c7ab9ac95c1                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x9b4e28020b94b28f9f09ede87f588e89c283cffd                         |                                                              |
| redeemAmount      | VARCHAR   | 20000000000000000000                                               |                                                              |
| redeemTokens      | VARCHAR   | 99829079481                                                        |                                                              |

## 225. Table: cToken\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-11 09:48:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9258894                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74777a2384b0bac46e7b2ed1bb0413e05f895eaba369794d5732458871613d0e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x0006e4548aed4502ec8c844567840ce6ef1013f5                         |                                                              |
| borrower          | VARCHAR   | 0x0006e4548aed4502ec8c844567840ce6ef1013f5                         |                                                              |
| repayAmount       | VARCHAR   | 7000001641                                                         |                                                              |
| accountBorrows    | VARCHAR   | 15081                                                              |                                                              |
| totalBorrows      | VARCHAR   | 15762676114121                                                     |                                                              |

## 226. Table: cToken\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 08:06:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16554122                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa7c2fad4deef7af52809ba41cff7184fa1747e68119b9fd682348b9329b0b3a9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         |                                                              |
| addAmount         | VARCHAR   | 25164053258338005308                                               |                                                              |
| newTotalReserves  | VARCHAR   | 21580728514749476497454880                                         |                                                              |

## 227. Table: cToken\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-30 11:38:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12140390                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88c07d09327092bf912d7ce81846f75293d6d5d0d7e52d2f5f9eaaf23223b0e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 83                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |
| reduceAmount      | VARCHAR   | 27000000000                                                        |                                                              |
| newTotalReserves  | VARCHAR   | 3021200238289                                                      |                                                              |

## 228. Table: cToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-25 18:57:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15213444                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1aa96d9ca311d74a58cc1df97460ab5329ae5da30a6815ba4acb176add93c08a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x477fa5406598f8eb1945291867e1654c4d931659                         |                                                              |
| to                | VARCHAR   | 0x0000e0ca771e21bd00057f54a68c30d400000000                         |                                                              |
| amount            | VARCHAR   | 1853386592623                                                      |                                                              |

## 229. Table: cTokenv3\_event\_AbsorbCollateral\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-04-26 20:02:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17132644                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x080a23a064f3a25225b9d8239ec8d67479f2a5b079cf659410f9ef0d676b5208 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| absorber           | VARCHAR   | 0xfde0d1575ed8e06fbf36256bcdfa1f359281455a                         |                                                              |
| borrower           | VARCHAR   | 0x49707808908f0c2450b3f2672e012edbf49ed808                         |                                                              |
| asset              | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         |                                                              |
| collateralAbsorbed | VARCHAR   | 6000000000000                                                      |                                                              |
| usdValue           | VARCHAR   | 23121                                                              |                                                              |

## 230. Table: cTokenv3\_event\_AbsorbDebt\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-25 18:53:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16707195                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8da5bb2de91f01b318aba7ffd4a8783af24291054b6a6250a4fd758362f0fc69 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| absorber          | VARCHAR   | 0x344922c7d3cfb0fca5c81233616482f12d64de1b                         |                                                              |
| borrower          | VARCHAR   | 0x2b5b4665a8f639757a3613fd88c4c70baec259bf                         |                                                              |
| basePaidOut       | VARCHAR   | 10245186610                                                        |                                                              |
| usdValue          | VARCHAR   | 1024416209133                                                      |                                                              |

## 231. Table: cTokenv3\_event\_BuyCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-26 20:02:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17132644                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x080a23a064f3a25225b9d8239ec8d67479f2a5b079cf659410f9ef0d676b5208 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xacc0e971c273af3f49f82029ad297d0898d8a266                         |                                                              |
| asset             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| baseAmount        | VARCHAR   | 73490501949                                                        |                                                              |
| collateralAmount  | VARCHAR   | 42164085141663866109                                               |                                                              |

## 232. Table: cTokenv3\_event\_PauseAction\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| supplyPaused      | VARCHAR   |                                                              |             |
| transferPaused    | VARCHAR   |                                                              |             |
| withdrawPaused    | VARCHAR   |                                                              |             |
| absorbPaused      | VARCHAR   |                                                              |             |
| buyPaused         | VARCHAR   |                                                              |             |

## 233. Table: cTokenv3\_event\_SupplyCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 22:41:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16357955                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e9f532838e5efd50ca9a4ef8930ba3baceccdc2772930c78ef08f47ad53159c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x74a81f84268744a40febc48f8b812a1f188d80c3                         |                                                              |
| dst               | VARCHAR   | 0x11b50686d3983c14c0d0972a5e46e38e0d9b2e14                         |                                                              |
| asset             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 381000000000000000000                                              |                                                              |

## 234. Table: cTokenv3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-18 14:10:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17286941                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x532bf78150cc50b3f09beec2ff1f18c383298b7bdefbdca796a0db3a0fb69469 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 275                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa397a8c2086c554b531c02e29f3291c9704b00c7                         |                                                              |
| dst               | VARCHAR   | 0x8ae43d8a9086bc17d0b93c87c2b5bb313e8c2a78                         |                                                              |
| amount            | VARCHAR   | 10000000000000000                                                  |                                                              |

## 235. Table: cTokenv3\_event\_TransferCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 07:25:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17832973                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1e99793799470d90094f49a35db302bfa3f86571860f44854f132ef08daf1666 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 321                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0d8e060ca2d847553ec14394ee6b304623e0d1d6                         |                                                              |
| to                | VARCHAR   | 0x42188c0139ee990aebcadf45ced459da4c7b6895                         |                                                              |
| asset             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 700000000000000000                                                 |                                                              |

## 236. Table: cTokenv3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-07 13:31:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16577216                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x01ed3a47df11b6016bfaf28da9fef297b837323c1e27c24e094da4e1c7afc225 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xd0fca12a4ff8d38468ddb2730aa5d662f19cd94b                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| amount            | VARCHAR   | 962204928479476140                                                 |                                                              |

## 237. Table: cTokenv3\_event\_WithdrawCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-26 03:37:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17560980                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x740e0accb7363ab81119ec7aa5f3b1190d82f9ff1f11d850a0f4018f36dacace | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x068287025be1d8597184e04771fe5286fefb47de                         |                                                              |
| to                | VARCHAR   | 0x068287025be1d8597184e04771fe5286fefb47de                         |                                                              |
| asset             | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         |                                                              |
| amount            | VARCHAR   | 4990453320000000000                                                |                                                              |

## 238. Table: cTokenv3\_event\_WithdrawReserves\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 239. Table: cTokenv3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 02:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16652636                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba8a5b76e660311087397ebe0fc5f7e02746e884490e6cd43261180b68a93f33 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x0658b4d806befe9669a9fa4528708c99f1e5dcde                         |                                                              |
| to                | VARCHAR   | 0x0658b4d806befe9669a9fa4528708c99f1e5dcde                         |                                                              |
| amount            | VARCHAR   | 74572651                                                           |                                                              |

## 240. Table: cUNI\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-01-06 23:20:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 16350988                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xd7a0f1e67f083843716b01312e84f1ba08fc26b3e104ef92066e351d89a7fd01 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 185                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 3605641560250774065206705                                          |                                                              |
| interestAccumulated | VARCHAR   | 657306920618126169                                                 |                                                              |
| borrowIndex         | VARCHAR   | 1148660098056786637                                                |                                                              |
| totalBorrows        | VARCHAR   | 493098107592222736434829                                           |                                                              |

## 241. Table: cUNI\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-27 07:14:23+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15837850                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0af0994601eaa39deac6c55bfd441d98a8aa411455ab124397f617ebe138b4ac             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x82892e764845087a1483f42b7380129c7749eb24                                     |                                                              |
| spender           | VARCHAR   | 0x881d40237659c251811cec9c364ef91dc08d300c                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 242. Table: cUNI\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 10:46:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14139044                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x658b174a48e9e722887c29693f45461d237a77d4f88ce72fd8f450af1213a35b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 423                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x8baa085221e88f320bef9c57329482f8c755fb30                         |                                                              |
| borrowAmount      | VARCHAR   | 200000000000000000000                                              |                                                              |
| accountBorrows    | VARCHAR   | 918431788207256379910                                              |                                                              |
| totalBorrows      | VARCHAR   | 561142564613737443757214                                           |                                                              |

## 243. Table: cUNI\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-06 01:59:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14330523                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf00047971ef5c0cf6217a06d584ef682e71e334942f7291d755011ec93734dc8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 834                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 40                                                                 |                                                              |
| detail            | VARCHAR   | 4                                                                  |                                                              |

## 244. Table: cUNI\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-16 15:35:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11667066                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x127710847390f4b5ac06f6ba37afb88e5bfc0e3b408685a32563e08179c9e828 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x00000000e84f2bbdfb129ed6e495c7f879f3e634                         |                                                              |
| borrower          | VARCHAR   | 0x7b52f8029640b3d8a1a7e7e2dead673db4f290fb                         |                                                              |
| repayAmount       | VARCHAR   | 18850042340212856137861                                            |                                                              |
| cTokenCollateral  | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         |                                                              |
| seizeTokens       | VARCHAR   | 22448647373                                                        |                                                              |

## 245. Table: cUNI\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-29 04:30:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12918647                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x749c0a15a5bd9c2dad9a13a7f19049cdcf191d8eed5991142ad3528e6aa028fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x0650d780292142835f6ac58dd8e2a336e87b4393                         |                                                              |
| mintAmount        | VARCHAR   | 2353216275315777789932                                             |                                                              |
| mintTokens        | VARCHAR   | 11636756334417                                                     |                                                              |

## 246. Table: cUNI\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 247. Table: cUNI\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-23 22:05:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10921410                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc61dc37f590933bd2852882dbc249624dd39620beee9ce324557a26bffdaf0af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 248. Table: cUNI\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-14 02:18:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11852041                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f92935835ad9ca0ffdecbf02c84e8420f5017fdd538a791509f32f700f687ab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x338f7e5d19d9953b76dd81446b142c2d9fe03482                         |                                                              |
| newImplementation | VARCHAR   | 0xa1849880593e96d2f7df77d0d38a7f2372ae10e0                         |                                                              |

## 249. Table: cUNI\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-10-24 10:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 15817508                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x51c80043827a7c84a537b110ad278929c597067d93035e57d478ce39c787db3d | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0xd88b94128ff2b8cf2d7886cd1c1e46757418ca2a                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xd956188795ca6f4a74092ddca33e0ea4ca3a1395                         |                                                              |

## 250. Table: cUNI\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 251. Table: cUNI\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2020-10-03 19:34:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 10984837                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x7cb66b64f7fa208e439366ba03eb7a2f8f5cb67499bae59b069fca6792c88a60 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 140                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 200000000000000000                                                 |                                                              |

## 252. Table: cUNI\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 22:29:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15556278                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d8a4a1f7f65a96be080f025ca05749dd6f0afe402cdd74fe2958b709f6437fb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x0650d780292142835f6ac58dd8e2a336e87b4393                         |                                                              |
| redeemAmount      | VARCHAR   | 11664359461712588924                                               |                                                              |
| redeemTokens      | VARCHAR   | 57500874197                                                        |                                                              |

## 253. Table: cUNI\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-18 08:39:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12657450                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x390b5ed9e761e09cafc04c7ccd2063d5ad2c31e53af4b6899f461ee86caad266 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 252                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x01dc417c6ea32788104426fa980330269d7786b3                         |                                                              |
| borrower          | VARCHAR   | 0x13f1d78ffd5e5fda865d18812bde6153caf40f17                         |                                                              |
| repayAmount       | VARCHAR   | 1650132505870953603296                                             |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 749311628465819592183282                                           |                                                              |

## 254. Table: cUNI\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-09 21:29:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15935149                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x017eee2af17e3c8b2e2710f8f811a77a95ce36303139b03f4f06b866283bdf53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         |                                                              |
| addAmount         | VARCHAR   | 11968936726815315522                                               |                                                              |
| newTotalReserves  | VARCHAR   | 63316342611528513945024                                            |                                                              |

## 255. Table: cUNI\_event\_ReservesReduced\_history

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

## 256. Table: cUNI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 18:26:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16170402                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3269507de15346f9e974c0197e91dd61e6dc8e922feba4572da55ffc2845d71b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xb990b8b21cc1ec7c0704789ccd21bd516fe52ba3                         |                                                              |
| to                | VARCHAR   | 0x35a18000230da775cac24873d00ff85bccded550                         |                                                              |
| amount            | VARCHAR   | 24631451585                                                        |                                                              |

## 257. Table: cUSDC\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-03-22 09:14:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 12087722                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x080aadca35d5ac7cb3bdd91f9034c2bea3de03a2f00e13aa518c33188996a2f0 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 248                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| interestAccumulated | VARCHAR   | 3779027153                                                         |                                                              |
| borrowIndex         | VARCHAR   | 1171775096238089004                                                |                                                              |
| totalBorrows        | VARCHAR   | 2232816857723945                                                   |                                                              |

## 258. Table: cUSDC\_event\_Approval\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-22 07:06:49+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8199046                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9d6de70fd0a3de4afaa390c5b8409cfc32ea34e257eace05d2700e93d8f632a9            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                                    | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3186ecc1be7c22a5bdd873cd3937a0c98021eee2                                    |                                                              |
| spender           | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                                    |                                                              |
| amount            | VARCHAR   | 57896044618658097711785492504343953926634992332820282019728792003956564819968 |                                                              |

## 259. Table: cUSDC\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 00:54:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16165179                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1855e065b71efab75c5ddd537507c79222ee5c3ce75510a6e080b7fb211dd32a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 130                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x0b498ff89709d3838a063f1dfa463091f9801c2b                         |                                                              |
| borrowAmount      | VARCHAR   | 1232439772                                                         |                                                              |
| accountBorrows    | VARCHAR   | 1197308339190                                                      |                                                              |
| totalBorrows      | VARCHAR   | 249137721194920                                                    |                                                              |

## 260. Table: cUSDC\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-16 20:36:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12253318                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe2fc68ff1271ed7b432baadccce11b3ca33c673fc3ed551e661dd20686e2bc25 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 13                                                                 |                                                              |
| info              | VARCHAR   | 38                                                                 |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 261. Table: cUSDC\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 07:26:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16167131                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x97f6822da72bc468e2337877e6d82205d5c2d0e52ec6bc9f44d026a70c703cba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x9a0ef593dcc6a77f80699c9fa00d1e138b67d832                         |                                                              |
| borrower          | VARCHAR   | 0xfe8260a826dc1f6e606118a2069f564d7a50ae5f                         |                                                              |
| repayAmount       | VARCHAR   | 19862092058                                                        |                                                              |
| cTokenCollateral  | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         |                                                              |
| seizeTokens       | VARCHAR   | 559191344993818                                                    |                                                              |

## 262. Table: cUSDC\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-11 11:07:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9649862                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5870796078ad462b668df51012da781de6fe616ea64e7e99ee81dfda1bf6e713 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x00000000008943c65caf789fffcf953be156f6f8                         |                                                              |
| mintAmount        | VARCHAR   | 805082                                                             |                                                              |
| mintTokens        | VARCHAR   | 3833198266                                                         |                                                              |

## 263. Table: cUSDC\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 19:09:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810866                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x44e8a51b433a4a28450744e008e0ea8c21187d1d63ccfedb055b33cf509ee46a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |
| newAdmin          | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |

## 264. Table: cUSDC\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 01:25:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7710760                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x13e2fe64ecf2c03243b4238477b268f4c0245d51bce7f7d9f1689ba60680b32c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 265. Table: cUSDC\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-05-07 01:25:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 7710760                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x13e2fe64ecf2c03243b4238477b268f4c0245d51bce7f7d9f1689ba60680b32c | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xc64c4cba055efa614ce01f4bad8a9f519c4f8fab                         |                                                              |

## 266. Table: cUSDC\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 18:59:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810823                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x617dec069be260681a5df8e69d0b56a5e9fb4b98ee6cb43ff7499ea8cf0ed848 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |

## 267. Table: cUSDC\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2020-12-12 14:10:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 11438576                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x72198c8f10a1958aa97b2f1408700209a14e026e81fabba866e03668e5879c8d | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 140                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 50000000000000000                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 75000000000000000                                                  |                                                              |

## 268. Table: cUSDC\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-28 10:49:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10153748                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x668b643727a9fe5b4f6ad2bbd528dc5bd3c3ecf1ea87d3fa7f17303c3a53b29e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x0034ea9808e620a0ef79261c51af20614b742b24                         |                                                              |
| redeemAmount      | VARCHAR   | 3000000                                                            |                                                              |
| redeemTokens      | VARCHAR   | 14259585351                                                        |                                                              |

## 269. Table: cUSDC\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-04 00:39:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9046574                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4a1323cfd3b5c02d4ba1676975be863f697a599c01877d93bdd92bf81227ace9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x10aab4b0ef76aa2ac9b5909e671517a1171b050e                         |                                                              |
| borrower          | VARCHAR   | 0x586e32930ac05127de429bd566eaa2758fcbd9bc                         |                                                              |
| repayAmount       | VARCHAR   | 179898654367                                                       |                                                              |
| accountBorrows    | VARCHAR   | 726805834038                                                       |                                                              |
| totalBorrows      | VARCHAR   | 15187743776944                                                     |                                                              |

## 270. Table: cUSDC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-28 00:03:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12124288                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb08f362619ef987f5af4860524361c2623018338d18d8faa8427b82e1cdf19a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 248                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x5b67871c3a857de81a1ca0f9f7945e5670d986dc                         |                                                              |
| to                | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| amount            | VARCHAR   | 691791590326272                                                    |                                                              |

## 271. Table: cUSDCv3\_event\_AbsorbCollateral\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-06-10 04:22:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17447372                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x792ac4c23bb0df553e7456298238d4a8d443d57e03a02152d24955480b24f115 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| absorber           | VARCHAR   | 0x315a52d08f38e9ea75dc5ce86e6e6c02251e575f                         |                                                              |
| borrower           | VARCHAR   | 0xb9e00bcea6b85e7cc532878ad59ae1859d5af67f                         |                                                              |
| asset              | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         |                                                              |
| collateralAbsorbed | VARCHAR   | 610382087022813692831                                              |                                                              |
| usdValue           | VARCHAR   | 1836047678057                                                      |                                                              |

## 272. Table: cUSDCv3\_event\_AbsorbDebt\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-22 11:36:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15588622                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6dddbdce30e40ee3ff73d1d064f17512469e193fa7611904615b813af8d1773c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 516                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| absorber          | VARCHAR   | 0xaec1f48e02cfb822be958b68c7957156eb3f0b6e                         |                                                              |
| borrower          | VARCHAR   | 0x2b384212edc04ae8bb41738d05ba20e33277bf33                         |                                                              |
| basePaidOut       | VARCHAR   | 90170                                                              |                                                              |
| usdValue          | VARCHAR   | 9017677                                                            |                                                              |

## 273. Table: cUSDCv3\_event\_BuyCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-05 15:02:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17628443                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x717df6ae5f6ecd84ec4f92abb8cdde7b779fe8e4fb30942a98158d7c33c77d35 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x50a77ba863dbaa84269133e5625ef80072f1884a                         |                                                              |
| asset             | VARCHAR   | 0xc00e94cb662c3520282e6f5717214004a7f26888                         |                                                              |
| baseAmount        | VARCHAR   | 1705776330                                                         |                                                              |
| collateralAmount  | VARCHAR   | 32587308617569391416                                               |                                                              |

## 274. Table: cUSDCv3\_event\_PauseAction\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| supplyPaused      | VARCHAR   |                                                              |             |
| transferPaused    | VARCHAR   |                                                              |             |
| withdrawPaused    | VARCHAR   |                                                              |             |
| absorbPaused      | VARCHAR   |                                                              |             |
| buyPaused         | VARCHAR   |                                                              |             |

## 275. Table: cUSDCv3\_event\_SupplyCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 10:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17349685                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32fba8e5682068edf37cd4805004ccbc4d20933f5699bd6e221bc2c347fb8b5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x29fca5052da9b93b2b25809135022ec367355995                         |                                                              |
| dst               | VARCHAR   | 0x29fca5052da9b93b2b25809135022ec367355995                         |                                                              |
| asset             | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         |                                                              |
| amount            | VARCHAR   | 100000000000000000                                                 |                                                              |

## 276. Table: cUSDCv3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 15:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17828077                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18e4f653eb1a4ce2b025375eab45d817c332da12f02d9de64604c456329146d6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 448                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x15262005f57cffa6f8c8a5ae4918202fd7fb8a04                         |                                                              |
| dst               | VARCHAR   | 0x15262005f57cffa6f8c8a5ae4918202fd7fb8a04                         |                                                              |
| amount            | VARCHAR   | 2500000000000                                                      |                                                              |

## 277. Table: cUSDCv3\_event\_TransferCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-11 01:15:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16801518                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe1c17710e9ee107113fb32383c66227e22e107ea1eba6b4d324c5acad555d191 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe1011eed6e26ccea4dbc86d11bf40add79119899                         |                                                              |
| to                | VARCHAR   | 0x80870b156ff0a8508e22b879d4e157d1dfa028ab                         |                                                              |
| asset             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 197548544960592402858                                              |                                                              |

## 278. Table: cUSDCv3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 21:35:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17473779                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb5d7c8abd83149388515bce346d8f8abe9a8410dd51e631cc9652025eb3ea1f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x995a09ed0b24ee13fbfcfbe60cad2fb6281b479f                         |                                                              |
| amount            | VARCHAR   | 2768750993779                                                      |                                                              |

## 279. Table: cUSDCv3\_event\_WithdrawCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 22:07:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16729516                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ebeb7fc6192e63ea11f3cb0f9d693401713138cfe750bf65fe5154f748937f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xf00e9ebc55fc836c81296d217218dd82d3159bd4                         |                                                              |
| to                | VARCHAR   | 0x540a83e36e5e6aa916a6c591934d800e17115048                         |                                                              |
| asset             | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000000                                             |                                                              |

## 280. Table: cUSDCv3\_event\_WithdrawReserves\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 281. Table: cUSDCv3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 18:25:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15555074                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x84977ae268435be0dc11acbc422de551f12439c90dce3a18114997d327e9f6a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 264                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc3d688b66703497daa19211eedff47f25384cdc3                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x9aceffd332ff7214f30511241029e909801a64d5                         |                                                              |
| to                | VARCHAR   | 0x9aceffd332ff7214f30511241029e909801a64d5                         |                                                              |
| amount            | VARCHAR   | 4003000000                                                         |                                                              |

## 282. Table: cUSDT\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-08-19 06:53:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13054183                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xd11d305e41455fbd4dda0e63eb4976aebe6e912a7c48f3d7c1976cce3fc7b83d | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 512                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 237223133597085                                                    |                                                              |
| interestAccumulated | VARCHAR   | 380593183                                                          |                                                              |
| borrowIndex         | VARCHAR   | 1108112560834179460                                                |                                                              |
| totalBorrows        | VARCHAR   | 477966195126776                                                    |                                                              |

## 283. Table: cUSDT\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-04 19:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17409194                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6ffc74e2df17188d0b36633f69fd76f1b0249f938cfa25e78b3670cca4f6aa9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x299c1bd9b48d97474b8aa993ebafb74cbc4b3269                         |                                                              |
| spender           | VARCHAR   | 0x216b4b4ba9f3e719726886d34a177484278bfcae                         |                                                              |
| amount            | VARCHAR   | 110000000000000                                                    |                                                              |

## 284. Table: cUSDT\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-02 10:55:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11958401                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x874df4e8c38b501aa4a2d7687037674e34f6904a864f4b2a3c3af4885c8e885a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 295                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xed04f413245a8651fc6998a6a1413b8e330dd7df                         |                                                              |
| borrowAmount      | VARCHAR   | 270000000                                                          |                                                              |
| accountBorrows    | VARCHAR   | 987478079                                                          |                                                              |
| totalBorrows      | VARCHAR   | 260870102613509                                                    |                                                              |

## 285. Table: cUSDT\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-04 01:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13156318                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf6b855ad5856dd7255df0a2ee954007cf73336c919f8165e1c5b2b68c8b3f625 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 14                                                                 |                                                              |
| detail            | VARCHAR   | 4                                                                  |                                                              |

## 286. Table: cUSDT\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-08 05:33:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16781488                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x303fdcb64615c52c31c6f4d852aaf3229ae0af17e48e50b83f09dcdb23e40b4a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x78bde1fe54d93d6bc483e160205f4b7e1c7ca5fb                         |                                                              |
| borrower          | VARCHAR   | 0x9d0ddf73322ece2bbdd79c47fb308538e981a7f3                         |                                                              |
| repayAmount       | VARCHAR   | 680877937                                                          |                                                              |
| cTokenCollateral  | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         |                                                              |
| seizeTokens       | VARCHAR   | 166340514                                                          |                                                              |

## 287. Table: cUSDT\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 22:41:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11590788                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa490e07c6f1d1c128e0641a77f349b0e3b67017273ca98a17d5ac5895e33ecf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 231                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x041574605e774e06a89bb52b79df8800d503c0ae                         |                                                              |
| mintAmount        | VARCHAR   | 1117000000                                                         |                                                              |
| mintTokens        | VARCHAR   | 5444629984559                                                      |                                                              |

## 288. Table: cUSDT\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 289. Table: cUSDT\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-15 21:13:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9879363                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e77fae02434ab498e6dd80cdb1bb3fbe53ee76a46749c0faa11bb850d431519 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 290. Table: cUSDT\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-15 21:13:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9879363                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e77fae02434ab498e6dd80cdb1bb3fbe53ee76a46749c0faa11bb850d431519 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newImplementation | VARCHAR   | 0x976aa93ca5aaa569109f4267589c619a097f001d                         |                                                              |

## 291. Table: cUSDT\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2020-04-15 21:13:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 9879363                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x7e77fae02434ab498e6dd80cdb1bb3fbe53ee76a46749c0faa11bb850d431519 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0x6bc8fe27d0c7207733656595e73c0d5cf7afae36                         |                                                              |

## 292. Table: cUSDT\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 293. Table: cUSDT\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2020-12-12 14:10:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 11438576                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x72198c8f10a1958aa97b2f1408700209a14e026e81fabba866e03668e5879c8d | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 200000000000000000                                                 |                                                              |
| newReserveFactorMantissa | VARCHAR   | 75000000000000000                                                  |                                                              |

## 294. Table: cUSDT\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-28 22:45:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16928880                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0952c201d05ea5014d041c4cbd2e3644b4d4b053237c0abf2a6156afe0075dfc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x372025203d25589ec3adad82652de78ec76ffabc                         |                                                              |
| redeemAmount      | VARCHAR   | 2000000000                                                         |                                                              |
| redeemTokens      | VARCHAR   | 8988499031175                                                      |                                                              |

## 295. Table: cUSDT\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 19:39:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14598313                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5cc66b571344c18776809fa209467c338d962bf0e789a663930e3774ed56ad6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x5f02795b7ef92fe8487c989d60f70c3f1ae84981                         |                                                              |
| borrower          | VARCHAR   | 0x5f02795b7ef92fe8487c989d60f70c3f1ae84981                         |                                                              |
| repayAmount       | VARCHAR   | 23358990450                                                        |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 512178430576133                                                    |                                                              |

## 296. Table: cUSDT\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-04 05:29:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15074139                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27ec903b4352e94efe09af221f969b7258c3f1e9c4ad8a51f788893e594fb2ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         |                                                              |
| addAmount         | VARCHAR   | 7377228                                                            |                                                              |
| newTotalReserves  | VARCHAR   | 3112142993850                                                      |                                                              |

## 297. Table: cUSDT\_event\_ReservesReduced\_history

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

## 298. Table: cUSDT\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-28 09:29:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16924948                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2dab181b7f3fb5feaf41cdf94e97120ec0e183d64dad8f77b41a0a4f7a92c14 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 310                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xf650c3d88d12db855b8bf7d11be6c55a4e07dcc9                         |                                                              |
| to                | VARCHAR   | 0x2aff603eac292e9abdfc2ee74e41241bb02e80aa                         |                                                              |
| amount            | VARCHAR   | 363784634252890                                                    |                                                              |

## 299. Table: cWBTC2\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-06-23 15:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17543297                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xa59dddb1b72e89266bc6575d3e54eeb26d3482dae23956c82c868e42875753e2 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 301                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 1423077420126                                                      |                                                              |
| interestAccumulated | VARCHAR   | 188003                                                             |                                                              |
| borrowIndex         | VARCHAR   | 1083675126697786268                                                |                                                              |
| totalBorrows        | VARCHAR   | 23823465102                                                        |                                                              |

## 300. Table: cWBTC2\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 09:14:47+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16289454                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x574c71a56a900e8a7515fa23c1013e678a14496d5fcb39266f72daa8c5979753             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xb603bade19edcd95a780151a694e8e57c15a066b                                     |                                                              |
| spender           | VARCHAR   | 0x3b6f1fe07cdab8a43f39c3b99ba8ff26e28db8b4                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 301. Table: cWBTC2\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-29 23:42:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16936273                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4d9d38566e44563f47df8fcbf3a2bd7c54c9b7fbb8f8e00ca72a923cf85585e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xeb312f4921aebbe99facacfe92f22b942cbd7599                         |                                                              |
| borrowAmount      | VARCHAR   | 200000000                                                          |                                                              |
| accountBorrows    | VARCHAR   | 2432857522                                                         |                                                              |
| totalBorrows      | VARCHAR   | 13482666852                                                        |                                                              |

## 302. Table: cWBTC2\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-27 05:19:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12119237                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e665b8a9bd9cbddda20297ca119d0aa635cf681030a9af6da8dc9f0fb8333e8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 288                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 18                                                                 |                                                              |
| detail            | VARCHAR   | 3                                                                  |                                                              |

## 303. Table: cWBTC2\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-18 01:00:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16851244                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd286f3365f7c609c83c84a1d1801c637e87a11a05f5263fd6e2ccd2e111bbda8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x78bde1fe54d93d6bc483e160205f4b7e1c7ca5fb                         |                                                              |
| borrower          | VARCHAR   | 0xd69de0d2cb5a1d3a52228ebe7beb03d76cca668e                         |                                                              |
| repayAmount       | VARCHAR   | 4038061                                                            |                                                              |
| cTokenCollateral  | VARCHAR   | 0x39aa39c021dfbae8fac545936693ac917d5e7563                         |                                                              |
| seizeTokens       | VARCHAR   | 5271055521430                                                      |                                                              |

## 304. Table: cWBTC2\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 16:15:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17145750                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x56852bd53690bc3fe800b3b8b69ebfba074f5f26f559b2561c733d00a49b2225 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 188                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x173ac361f92f8ba8bd42efeb46c1edff36111a07                         |                                                              |
| mintAmount        | VARCHAR   | 29944003                                                           |                                                              |
| mintTokens        | VARCHAR   | 1491644781                                                         |                                                              |

## 305. Table: cWBTC2\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 306. Table: cWBTC2\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-14 19:44:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12038653                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1753d0cc7d9619bc82493e44144a6435ae58c1f132a03a786d6d8384fba83d6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 120                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 307. Table: cWBTC2\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-28 19:52:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12724484                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x694de552980bc831eaf3c44dc4f8107fba6823e3a1293ea3a4816c309ea8eb39 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 260                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x24aa720906378bb8364228bddb8cabbc1f6fe1ba                         |                                                              |
| newImplementation | VARCHAR   | 0xa035b9e130f2b1aedc733eefb1c67ba4c503491f                         |                                                              |

## 308. Table: cWBTC2\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-03-14 19:44:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12038653                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x1753d0cc7d9619bc82493e44144a6435ae58c1f132a03a786d6d8384fba83d6b | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xf2e5db36b0682f2cd6bc805c3a4236194e01f4d5                         |                                                              |

## 309. Table: cWBTC2\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 310. Table: cWBTC2\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-03-19 14:54:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 12069867                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xa9d9a710ec465fb742346bff8169acf3defae1722b6ca61589006dd6b7e9c374 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 200000000000000000                                                 |                                                              |

## 311. Table: cWBTC2\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-28 05:46:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14292812                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d242878e048bbebca91e2c4fdeb5ce0b78b047f01a6fa1d3167f66f81fc53b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x0b498ff89709d3838a063f1dfa463091f9801c2b                         |                                                              |
| redeemAmount      | VARCHAR   | 16918349                                                           |                                                              |
| redeemTokens      | VARCHAR   | 843329843                                                          |                                                              |

## 312. Table: cWBTC2\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-20 05:11:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12861450                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa60bd9804a452f7adff1d76198933525e75f0edfdbfc6e9ddfe82b92012db132 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xcd615848c10c89f6afcc3f353b2c0b690c535a27                         |                                                              |
| borrower          | VARCHAR   | 0xcd615848c10c89f6afcc3f353b2c0b690c535a27                         |                                                              |
| repayAmount       | VARCHAR   | 400677304                                                          |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 427198655169                                                       |                                                              |

## 313. Table: cWBTC2\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 01:20:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15487431                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x611ca6d6825e4efc8f138aae618e99f4ef3fba3352ac41278cbbe1e65847bb7f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         |                                                              |
| addAmount         | VARCHAR   | 200726                                                             |                                                              |
| newTotalReserves  | VARCHAR   | 10826192316                                                        |                                                              |

## 314. Table: cWBTC2\_event\_ReservesReduced\_history

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

## 315. Table: cWBTC2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 22:15:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14161624                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e5ef22e59ee0ee47561a6e3e4d38977eb296c5e0c1ff5cd183ca3249e0a1a30 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 169                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x456bcf03c84ae67e840c7a0036562d360b6d09c1                         |                                                              |
| to                | VARCHAR   | 0xccf4429db6322d5c611ee964527d42e5d685dd6a                         |                                                              |
| amount            | VARCHAR   | 599205143                                                          |                                                              |

## 316. Table: cWBTC\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2020-12-10 00:39:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 11422012                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x9377fe89432721adba3506aaeead2f4efc347c96f2db35cd0e28f4f63b0f3aa3 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| interestAccumulated | VARCHAR   | 145311                                                             |                                                              |
| borrowIndex         | VARCHAR   | 1076070184583612382                                                |                                                              |
| totalBorrows        | VARCHAR   | 53927520114                                                        |                                                              |

## 317. Table: cWBTC\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-25 20:11:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12110200                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d3d3780579110b2ffe59cdb2cad790f98223cfafad9b083e7415cc67729ce12 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x22e1da822a7f321114a63483a0d2187566aab8c4                         |                                                              |
| spender           | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                         |                                                              |
| amount            | VARCHAR   | 1601618357                                                         |                                                              |

## 318. Table: cWBTC\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-08 23:02:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10028450                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76f862be0c3cb101d59f39be95e14f2d5a8b651f0623142bd615f63546ce378a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x0dce81512c2fa29b81ea9833fd29b2f068678385                         |                                                              |
| borrowAmount      | VARCHAR   | 500000                                                             |                                                              |
| accountBorrows    | VARCHAR   | 500000                                                             |                                                              |
| totalBorrows      | VARCHAR   | 667691395                                                          |                                                              |

## 319. Table: cWBTC\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-30 13:48:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10762521                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa7b03a3bca919813618bd034dd130850d1ad90f71b5a0d428de7a550e2fe6567 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 13                                                                 |                                                              |
| info              | VARCHAR   | 38                                                                 |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 320. Table: cWBTC\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-01 17:13:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10575197                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2bb8a03edcfdd7bc61cfdb0566569253b625ec5ad62943446f7da15acdf39204 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x7b2ef92fdecdf4a156365eb78c9e92b44588fe84                         |                                                              |
| borrower          | VARCHAR   | 0x476e23bfc5415397021a74e525640b328a12b81e                         |                                                              |
| repayAmount       | VARCHAR   | 6522839                                                            |                                                              |
| cTokenCollateral  | VARCHAR   | 0x5d3a536e4d6dbd6114cc1ead35777bab948e3643                         |                                                              |
| seizeTokens       | VARCHAR   | 3970993064975                                                      |                                                              |

## 321. Table: cWBTC\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-17 00:15:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8364660                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f94d3f86238fdad72c535ada504bd795d0764665b6d93337142e1a06d494258 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x2e13c8f1e1d66919d04f12e49fbc4a3c03d286d2                         |                                                              |
| mintAmount        | VARCHAR   | 4589683                                                            |                                                              |
| mintTokens        | VARCHAR   | 229461833                                                          |                                                              |

## 322. Table: cWBTC\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-16 23:04:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8164690                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x509012d8a2743992d1f71449120bff64053b79c8ab09f0ec77edabbcf83e1ba6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0xa7ff0d561cd15ed525e31bbe0af3fe34ac2059f6                         |                                                              |
| newAdmin          | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |

## 323. Table: cWBTC\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-16 19:47:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8163813                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa0d8748bfd292071a40f9cd7cd64304f521a2ff04ab7734a84845687f2402121 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 324. Table: cWBTC\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-07-16 19:47:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 8163813                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xa0d8748bfd292071a40f9cd7cd64304f521a2ff04ab7734a84845687f2402121 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xbae04cbf96391086dc643e842b517734e214d698                         |                                                              |

## 325. Table: cWBTC\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-16 22:55:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8164642                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb59b44d2d3f03ff75a15a23f1aa5127e9b27dda88e09b2d484b300f56f1466a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |

## 326. Table: cWBTC\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2019-07-16 20:26:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 8163976                                                            | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xed30de97cddac9f29a91a5f3ca08bed04059e72eb71c09a67e37934a7820caa2 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 100000000000000000                                                 |                                                              |

## 327. Table: cWBTC\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-27 10:27:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12907584                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x025b822b62c9cb75effb3acede39b5288cfc969a9e5560fc93f629d7ea5e6563 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xa9f6f345122b7fbfa08795b6579f0f803d1db8f6                         |                                                              |
| redeemAmount      | VARCHAR   | 200000000                                                          |                                                              |
| redeemTokens      | VARCHAR   | 9898790876                                                         |                                                              |

## 328. Table: cWBTC\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-07 22:01:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11610104                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe967459da51409ba5f61b380f0bf03b090c6252610b3a3818236cb4e28a32a1b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xb58c4358669bb70df715b6747447eb63afea8916                         |                                                              |
| borrower          | VARCHAR   | 0xb58c4358669bb70df715b6747447eb63afea8916                         |                                                              |
| repayAmount       | VARCHAR   | 6100644648                                                         |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 81512708695                                                        |                                                              |

## 329. Table: cWBTC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-18 05:56:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14408661                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb424d2385e87c8b2cb7a0f85eae4eab537f5ac2bf957bb429b0760080f6fe985 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 305                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xdef552464abbee855ce3e84437cbf65777a35e88                         |                                                              |
| to                | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         |                                                              |
| amount            | VARCHAR   | 197975817                                                          |                                                              |

## 330. Table: cWETHv3\_event\_AbsorbCollateral\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| absorber           | VARCHAR   |                                                              |             |
| borrower           | VARCHAR   |                                                              |             |
| asset              | VARCHAR   |                                                              |             |
| collateralAbsorbed | VARCHAR   |                                                              |             |
| usdValue           | VARCHAR   |                                                              |             |

## 331. Table: cWETHv3\_event\_AbsorbDebt\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| absorber          | VARCHAR   |                                                              |             |
| borrower          | VARCHAR   |                                                              |             |
| basePaidOut       | VARCHAR   |                                                              |             |
| usdValue          | VARCHAR   |                                                              |             |

## 332. Table: cWETHv3\_event\_BuyCollateral\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| buyer             | VARCHAR   |                                                              |             |
| asset             | VARCHAR   |                                                              |             |
| baseAmount        | VARCHAR   |                                                              |             |
| collateralAmount  | VARCHAR   |                                                              |             |

## 333. Table: cWETHv3\_event\_PauseAction\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| supplyPaused      | VARCHAR   |                                                              |             |
| transferPaused    | VARCHAR   |                                                              |             |
| withdrawPaused    | VARCHAR   |                                                              |             |
| absorbPaused      | VARCHAR   |                                                              |             |
| buyPaused         | VARCHAR   |                                                              |             |

## 334. Table: cWETHv3\_event\_SupplyCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-10 14:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16798459                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2758f611b5db1d3f577603df89c5ae5a01ed8a3326824ce2aca6e6ea50eb3348 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x67cc801c8267f2a3ebbb42c744fe745eb3371066                         |                                                              |
| dst               | VARCHAR   | 0x67cc801c8267f2a3ebbb42c744fe745eb3371066                         |                                                              |
| asset             | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         |                                                              |
| amount            | VARCHAR   | 3662199389545910647                                                |                                                              |

## 335. Table: cWETHv3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 02:21:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17845756                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e89d40e351c976ba057b83511f930b3d879ff2f594bf77746b47ef7ee122d2d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 356                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa397a8c2086c554b531c02e29f3291c9704b00c7                         |                                                              |
| dst               | VARCHAR   | 0x61ff9cbe2d6ce98f4c8ecf3807339474f4c09630                         |                                                              |
| amount            | VARCHAR   | 5500000000000000                                                   |                                                              |

## 336. Table: cWETHv3\_event\_TransferCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-18 14:30:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17074161                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x00b5740c5dec733533a4f6eb0dcfa04cc1735852120b972d30b801b4bcd2cb0f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3ff21f1930b39a53f79ddf79d2c809477d33bf78                         |                                                              |
| to                | VARCHAR   | 0x25537c8aedce52928c87e610f1e731cf078ded36                         |                                                              |
| asset             | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         |                                                              |
| amount            | VARCHAR   | 107231347482693256                                                 |                                                              |

## 337. Table: cWETHv3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-28 21:50:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17360304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69a344292e27c5de140555a894aceb09e7c176d3fb107a72095c271b13c9fc7a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x6d910bea79aaf318e7170c6fb8318d9c466b2164                         |                                                              |
| amount            | VARCHAR   | 999999999999999                                                    |                                                              |

## 338. Table: cWETHv3\_event\_WithdrawCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 13:52:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17421822                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9bba88b226cf42f25a2b50429393ccb688a5e7528c7d63e75edc7002361489eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xb4ab9ccc51d5e8532da753aa71aa0bdede948e63                         |                                                              |
| to                | VARCHAR   | 0xb4ab9ccc51d5e8532da753aa71aa0bdede948e63                         |                                                              |
| asset             | VARCHAR   | 0xbe9895146f7af43049ca1c1ae358b0541ea49704                         |                                                              |
| amount            | VARCHAR   | 435340000000000000000                                              |                                                              |

## 339. Table: cWETHv3\_event\_WithdrawReserves\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 340. Table: cWETHv3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-17 04:31:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17710621                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35c89ee5374ab1d15ff176843bfabf58f59968104db4559438ccc566e84a542a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 367                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17581a9e3356d9a858b789d68b4d866e593ae94                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x56aa33f20e25baa99e916c91abb4f59ae72491e0                         |                                                              |
| to                | VARCHAR   | 0xa397a8c2086c554b531c02e29f3291c9704b00c7                         |                                                              |
| amount            | VARCHAR   | 1200000000000000000000                                             |                                                              |

## 341. Table: cYFI\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-07-11 23:04:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 15124213                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xacc210bfbbff43622eb77eb73c0ac127e2cd4a4252595626926414cafbafa4f3 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 411                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 138795445550656820177                                              |                                                              |
| interestAccumulated | VARCHAR   | 16032041200267                                                     |                                                              |
| borrowIndex         | VARCHAR   | 1064775218295704999                                                |                                                              |
| totalBorrows        | VARCHAR   | 10219586656922848352                                               |                                                              |

## 342. Table: cYFI\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-01 16:06:35+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16535048                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05480b7aeb31abb07ed63f9b73260395da154614ebf1382c18fc47219b2734fd             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 248                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x1a2d11cb90d1de13bb81ee7b772a08ac234a8058                                     |                                                              |
| spender           | VARCHAR   | 0x0bc529c00c6401aef6d220be8c6ea1667f6ad93e                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 343. Table: cYFI\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-30 06:34:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16295829                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51e4d5872bb84fded584b8f1f1f7c7835a4e4e1521147ba38b477326863f096c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x4da4b904cbc38ec8e0b14d542314318850cca976                         |                                                              |
| borrowAmount      | VARCHAR   | 34000000000000                                                     |                                                              |
| accountBorrows    | VARCHAR   | 34000000000000                                                     |                                                              |
| totalBorrows      | VARCHAR   | 4032508155615150126                                                |                                                              |

## 344. Table: cYFI\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-20 16:55:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14043644                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45cee10c21e4ef71c66dc9c79953bc59faf7ff9ba44acd31ffa667fd179042ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 478                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 14                                                                 |                                                              |
| info              | VARCHAR   | 9                                                                  |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 345. Table: cYFI\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-08 10:39:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15101421                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x206627c750b61164d4c54bb1c5104baae5f308dc7419ae8138ca2bd1b1b1d54a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x625d6d3f3b375e686642dc8d1d438ac58058d09c                         |                                                              |
| borrower          | VARCHAR   | 0xa6660932dc1556ea11116982ae2a37f64f95ace6                         |                                                              |
| repayAmount       | VARCHAR   | 270565784477022                                                    |                                                              |
| cTokenCollateral  | VARCHAR   | 0xface851a4921ce59e912d19329929ce6da6eb0c7                         |                                                              |
| seizeTokens       | VARCHAR   | 1450550001                                                         |                                                              |

## 346. Table: cYFI\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-08 12:21:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14545085                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x985aa94561057c15cc9eb8795671ce0ac7f8be575e4894b170f050da9b0eb754 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 455                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x1f84ca2c0a406b32e083e4e41032fd148364df48                         |                                                              |
| mintAmount        | VARCHAR   | 31554037977058738890                                               |                                                              |
| mintTokens        | VARCHAR   | 156161917653                                                       |                                                              |

## 347. Table: cYFI\_event\_NewAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdmin          | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 348. Table: cYFI\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-18 03:19:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12848198                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0606b7ecf56f809dcda9d3bd0bfb2589c3734c264d67c3ee551dc94a352faddc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 349. Table: cYFI\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-07 21:19:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14541141                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7cc2acd03f837009b97c3d21a0efe6fb02ae4cda75a061e70f4d20ab411da275 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 326                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0xa035b9e130f2b1aedc733eefb1c67ba4c503491f                         |                                                              |
| newImplementation | VARCHAR   | 0x3363bae2fc44da742df13cd3ee94b6bb868ea376                         |                                                              |

## 350. Table: cYFI\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-07-18 03:19:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12848198                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x0606b7ecf56f809dcda9d3bd0bfb2589c3734c264d67c3ee551dc94a352faddc | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xd956188795ca6f4a74092ddca33e0ea4ca3a1395                         |                                                              |

## 351. Table: cYFI\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldPendingAdmin   | VARCHAR   |                                                              |             |
| newPendingAdmin   | VARCHAR   |                                                              |             |

## 352. Table: cYFI\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2021-08-04 17:53:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 12960086                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xb83ddf4033f61cda65149428c1a247fe516e53d7f762b55ac64a751d1fb3d7ce | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 332                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactorMantissa | VARCHAR   | 250000000000000000                                                 |                                                              |

## 353. Table: cYFI\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-20 15:19:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13062868                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3bd35de6580e6b8e8bbfd8aed8d03da2bc7dbc4d4a46b44ca16aef398dc3da5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x34790cbd16280497a6e0081b5927126a058aff45                         |                                                              |
| redeemAmount      | VARCHAR   | 2327056328044463980                                                |                                                              |
| redeemTokens      | VARCHAR   | 11635144153                                                        |                                                              |

## 354. Table: cYFI\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-13 18:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16820714                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xffc180236dc85937fd67b8b201dbdba835216a14bbaa8d0c019e394e3ce4188f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xe52f5349153b8eb3b89675af45ac7502c4997e6a                         |                                                              |
| borrower          | VARCHAR   | 0xe52f5349153b8eb3b89675af45ac7502c4997e6a                         |                                                              |
| repayAmount       | VARCHAR   | 2115110040000000000                                                |                                                              |
| accountBorrows    | VARCHAR   | 13251239357581829514                                               |                                                              |
| totalBorrows      | VARCHAR   | 13253437400238458282                                               |                                                              |

## 355. Table: cYFI\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-12 20:55:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15956459                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28f0c0c7d73edf307a4613eac5387032f845f9d220d4836f32b38a134f0a828d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         |                                                              |
| addAmount         | VARCHAR   | 891121868229330                                                    |                                                              |
| newTotalReserves  | VARCHAR   | 385975419934486193                                                 |                                                              |

## 356. Table: cYFI\_event\_ReservesReduced\_history

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

## 357. Table: cYFI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-18 08:01:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15165434                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e1cc41c243a8fa7784354236049c9b292ee17eeb8cfe209153ab9320cbe044d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x49707808908f0c2450b3f2672e012edbf49ed808                         |                                                              |
| to                | VARCHAR   | 0x80a2ae356fc9ef4305676f7a3e2ed04e12c33946                         |                                                              |
| amount            | VARCHAR   | 4011915358                                                         |                                                              |

## 358. Table: cZRX\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2020-06-28 14:37:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 10354850                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xf138687a9b5824db88f676ef93c7566084157153b1bb594c899e709c5376aeed | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| interestAccumulated | VARCHAR   | 6180983833993321927                                                |                                                              |
| borrowIndex         | VARCHAR   | 1057623374059161777                                                |                                                              |
| totalBorrows        | VARCHAR   | 14485598321549363267423501                                         |                                                              |

## 359. Table: cZRX\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-13 09:13:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15526071                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x831319ba1f235889b1212ff90f31eaf63430e2e67447db7fd12322aa8140abf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 311                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xe66b31678d6c16e9ebf358268a790b763c133750                         |                                                              |
| spender           | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         |                                                              |
| amount            | VARCHAR   | 2929735185                                                         |                                                              |

## 360. Table: cZRX\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-11 15:31:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9651037                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3026f28d0fbbfd3dc79de6721df61a6b1b5a58c827b4806deab1e783459e1554 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 111                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x3d1a8bf4b5db60f71386f1e714c1402ba9476242                         |                                                              |
| borrowAmount      | VARCHAR   | 3000000000000000000000                                             |                                                              |
| accountBorrows    | VARCHAR   | 50250017192780510155462                                            |                                                              |
| totalBorrows      | VARCHAR   | 355450972014330725063676                                           |                                                              |

## 361. Table: cZRX\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-30 19:29:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8253883                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x388b7c4a5bdf64972c141dc928a9e2600a0ccdbd0e7037cfbc8a547abc5ff93b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 64                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 9                                                                  |                                                              |
| info              | VARCHAR   | 45                                                                 |                                                              |
| detail            | VARCHAR   | 3                                                                  |                                                              |

## 362. Table: cZRX\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-18 08:45:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14984066                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8277d77909eab9d0aaf5129dd96f294d98369dd5dcaf92fa1ff0d2acd1d0efd6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x9a0ef593dcc6a77f80699c9fa00d1e138b67d832                         |                                                              |
| borrower          | VARCHAR   | 0x601e6e7711b9e3b1b20e1e8016038a32dfc86ddd                         |                                                              |
| repayAmount       | VARCHAR   | 1759126177236512095468                                             |                                                              |
| cTokenCollateral  | VARCHAR   | 0xc11b1268c1a384e55c48c2391d8d480264a3a7f4                         |                                                              |
| seizeTokens       | VARCHAR   | 120479033                                                          |                                                              |

## 363. Table: cZRX\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-28 23:59:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11948957                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdb5e45abe91a55fd516bfd481d76e520ce3d106ffe710ebb9b408679f4cdc4c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x31d76b3201271e90c61ba9650f27b5bf6ba2785a                         |                                                              |
| mintAmount        | VARCHAR   | 592000000000000000000                                              |                                                              |
| mintTokens        | VARCHAR   | 2898061256340                                                      |                                                              |

## 364. Table: cZRX\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-25 19:06:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8810853                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe2981b5b7f9dab645104f19f748c738ef51ce5c9bff15824e26d94baa6c87f74 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |
| newAdmin          | VARCHAR   | 0x6d903f6003cca6255d85cca4d3b5e5146dc33925                         |                                                              |

## 365. Table: cZRX\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 01:20:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7710733                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb892790453ea3a1ca4756687c8d799949a4aac82152f8d9d10a96e2adaa17d1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x3d9819210a31b4961b30ef54be2aed79b9c9cd3b                         |                                                              |

## 366. Table: cZRX\_event\_NewMarketInterestRateModel\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2019-05-07 01:20:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 7710733                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xbb892790453ea3a1ca4756687c8d799949a4aac82152f8d9d10a96e2adaa17d1 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| oldInterestRateModel | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newInterestRateModel | VARCHAR   | 0xbae04cbf96391086dc643e842b517734e214d698                         |                                                              |

## 367. Table: cZRX\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-07 02:20:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7710998                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ec2e54402e1d2d17349345451adb7c2af526fbbd4643eba6b4146207552f6dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x8b8592e9570e96166336603a1b4bd1e8db20fa20                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 368. Table: cZRX\_event\_NewReserveFactor\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2020-12-12 14:10:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 11438576                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x72198c8f10a1958aa97b2f1408700209a14e026e81fabba866e03668e5879c8d | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| oldReserveFactorMantissa | VARCHAR   | 500000000000000000                                                 |                                                              |
| newReserveFactorMantissa | VARCHAR   | 250000000000000000                                                 |                                                              |

## 369. Table: cZRX\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-14 07:56:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8931291                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0043a5f661baeeaf280c53c477e16c4b8f6277a2e66e9deaf77295f4c2ad60cb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x4fe95c36bb9b3a81f278569525162f91615e77d7                         |                                                              |
| redeemAmount      | VARCHAR   | 172000000000000000000                                              |                                                              |
| redeemTokens      | VARCHAR   | 858120760162                                                       |                                                              |

## 370. Table: cZRX\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-18 21:20:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12660770                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24402525224c4dbb23cf75450f7d2e8b6a65dfaa3673aa562468b13074461ed0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x4a6eafba4db3eedafc052ebaa2a117806f79699f                         |                                                              |
| borrower          | VARCHAR   | 0x02deec8b09d4ec879d4e6793e496e6b58a7d723d                         |                                                              |
| repayAmount       | VARCHAR   | 21130758205110918715                                               |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 19015506143790301931609736                                         |                                                              |

## 371. Table: cZRX\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-14 08:05:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8931334                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb7b13c3fda5f77d917c70bac9101a1afa7fd2ad8ad16eaf1fba8227b59d415f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0011e3c93627956b12742b3c0b2e92250ea30a1f                         |                                                              |
| to                | VARCHAR   | 0xb3319f5d18bc0d84dd1b4825dcde5d5f7266d407                         |                                                              |
| amount            | VARCHAR   | 18244837028                                                        |                                                              |
