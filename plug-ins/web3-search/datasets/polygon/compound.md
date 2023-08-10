# compound

## 1. Table: CometRewards\_v3\_event\_GovernorTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 00:54:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39413597                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f720b315488dd7e6a95bbad33c9850265fb494e43fbd69c5e63d555cd41244c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 312                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45939657d1ca34a8fa39a924b71d28fe8431e581                         | Address of the contract that produced the log                |
| oldGovernor       | VARCHAR   | 0x6103db328d4864dc16bd2f0ee1b9a92e3f87f915                         |                                                              |
| newGovernor       | VARCHAR   | 0xcc3e7c85bb0ee4f09380e041fee95a0caedd4a02                         |                                                              |

## 2. Table: CometRewards\_v3\_event\_RewardClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 06:30:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45491357                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4d81e98e4d21d3173c9c3485555bfdb3e7393b32e82b8b8c5bcda25f1b5d6fc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45939657d1ca34a8fa39a924b71d28fe8431e581                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x1d805329aea7db354bbea01395df1482854b8321                         |                                                              |
| recipient         | VARCHAR   | 0x1d805329aea7db354bbea01395df1482854b8321                         |                                                              |
| token             | VARCHAR   | 0x8505b9d2254a7ae468c0e9dd10ccea3a837aef5c                         |                                                              |
| amount            | VARCHAR   | 69771000000000000                                                  |                                                              |

## 3. Table: Configurator\_v3\_event\_AddAsset\_history

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

## 4. Table: Configurator\_v3\_event\_CometDeployed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-18 20:42:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42868304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x36c0a9169d0f036ce97db11bb3927de81701d5e7ee57967b1992b01f54812c8e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 683                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x83e0f742cacbe66349e3701b171ee2487a26e738                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         |                                                              |
| newComet          | VARCHAR   | 0x8ae12468b2cb55d5f9a1fd0a2315147e433adf29                         |                                                              |

## 5. Table: Configurator\_v3\_event\_GovernorTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 00:51:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39413533                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed2d0b9c4794ac3a98b242e574a73f1881b183eb2f57056b50e0d74d07332299 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x83e0f742cacbe66349e3701b171ee2487a26e738                         | Address of the contract that produced the log                |
| oldGovernor       | VARCHAR   | 0x6103db328d4864dc16bd2f0ee1b9a92e3f87f915                         |                                                              |
| newGovernor       | VARCHAR   | 0xcc3e7c85bb0ee4f09380e041fee95a0caedd4a02                         |                                                              |

## 6. Table: Configurator\_v3\_event\_SetBaseBorrowMin\_history

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

## 7. Table: Configurator\_v3\_event\_SetBaseMinForRewards\_history

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

## 8. Table: Configurator\_v3\_event\_SetBaseTokenPriceFeed\_history

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

## 9. Table: Configurator\_v3\_event\_SetBaseTrackingBorrowSpeed\_history

| Column                     | Type      | Example                                                      | Description |
| -------------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp           | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number              | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash          | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index                 | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address          | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy                 | VARCHAR   |                                                              |             |
| oldBaseTrackingBorrowSpeed | VARCHAR   |                                                              |             |
| newBaseTrackingBorrowSpeed | VARCHAR   |                                                              |             |

## 10. Table: Configurator\_v3\_event\_SetBaseTrackingSupplySpeed\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-05-18 20:42:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 42868304                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0x36c0a9169d0f036ce97db11bb3927de81701d5e7ee57967b1992b01f54812c8e | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 681                                                                | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x83e0f742cacbe66349e3701b171ee2487a26e738                         | Address of the contract that produced the log                |
| cometProxy                 | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         |                                                              |
| oldBaseTrackingSupplySpeed | VARCHAR   | 0                                                                  |                                                              |
| newBaseTrackingSupplySpeed | VARCHAR   | 401967592592                                                       |                                                              |

## 11. Table: Configurator\_v3\_event\_SetBorrowKink\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldKink           | VARCHAR   |                                                              |             |
| newKink           | VARCHAR   |                                                              |             |

## 12. Table: Configurator\_v3\_event\_SetBorrowPerYearInterestRateBase\_history

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

## 13. Table: Configurator\_v3\_event\_SetBorrowPerYearInterestRateSlopeHigh\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldIRSlopeHigh    | VARCHAR   |                                                              |             |
| newIRSlopeHigh    | VARCHAR   |                                                              |             |

## 14. Table: Configurator\_v3\_event\_SetBorrowPerYearInterestRateSlopeLow\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldIRSlopeLow     | VARCHAR   |                                                              |             |
| newIRSlopeLow     | VARCHAR   |                                                              |             |

## 15. Table: Configurator\_v3\_event\_SetConfiguration\_history

| Column                                              | Type                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | Example                                                                                              | Description                                                  |
| --------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp                                    | TIMESTAMP                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 2023-03-07 17:49:30+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number                                       | INTEGER                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 40078393                                                                                             | The block number where this event was emitted                |
| transaction\_hash                                   | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x6eef97e8cda567347cd08f864b38cd327c9e3a869e3f973f6f72a37360eb5add                                   | Hash of the transactions in which this event was emitted     |
| log\_index                                          | INTEGER                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 171                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address                                   | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x83e0f742cacbe66349e3701b171ee2487a26e738                                                           | Address of the contract that produced the log                |
| cometProxy                                          | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xf25212e676d1f7f89cd72ffee66158f541246445                                                           |                                                              |
| oldConfiguration                                    | STRUCT\<governor STRING, pauseGuardian STRING, baseToken STRING, baseTokenPriceFeed STRING, extensionDelegate STRING, supplyKink STRING, supplyPerYearInterestRateSlopeLow STRING, supplyPerYearInterestRateSlopeHigh STRING, supplyPerYearInterestRateBase STRING, borrowKink STRING, borrowPerYearInterestRateSlopeLow STRING, borrowPerYearInterestRateSlopeHigh STRING, borrowPerYearInterestRateBase STRING, storeFrontPriceFactor STRING, trackingIndexScale STRING, baseTrackingSupplySpeed STRING, baseTrackingBorrowSpeed STRING, baseMinForRewards STRING, baseBorrowMin STRING, targetReserves STRING, assetConfigs STRING> | {'governor': '0xcc3e7c85bb0ee4f09380e041fee95a0caedd4a02', 'pauseGuardian': '0xcc3e7c85bb0ee4f09380e |                                                              |
| oldConfiguration.governor                           | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xcc3e7c85bb0ee4f09380e041fee95a0caedd4a02                                                           |                                                              |
| oldConfiguration.pauseGuardian                      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xcc3e7c85bb0ee4f09380e041fee95a0caedd4a02                                                           |                                                              |
| oldConfiguration.baseToken                          | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                                                           |                                                              |
| oldConfiguration.baseTokenPriceFeed                 | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xfe4a8cc5b5b2366c1b58bea3858e81843581b2f7                                                           |                                                              |
| oldConfiguration.extensionDelegate                  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xbde8f31d2ddda895264e27dd990fab3dc87b372d                                                           |                                                              |
| oldConfiguration.supplyKink                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 800000000000000000                                                                                   |                                                              |
| oldConfiguration.supplyPerYearInterestRateSlopeLow  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 32500000000000000                                                                                    |                                                              |
| oldConfiguration.supplyPerYearInterestRateSlopeHigh | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 400000000000000000                                                                                   |                                                              |
| oldConfiguration.supplyPerYearInterestRateBase      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.borrowKink                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 800000000000000000                                                                                   |                                                              |
| oldConfiguration.borrowPerYearInterestRateSlopeLow  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 35000000000000004                                                                                    |                                                              |
| oldConfiguration.borrowPerYearInterestRateSlopeHigh | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 250000000000000000                                                                                   |                                                              |
| oldConfiguration.borrowPerYearInterestRateBase      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 15000000000000000                                                                                    |                                                              |
| oldConfiguration.storeFrontPriceFactor              | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 500000000000000000                                                                                   |                                                              |
| oldConfiguration.trackingIndexScale                 | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 1000000000000000                                                                                     |                                                              |
| oldConfiguration.baseTrackingSupplySpeed            | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.baseTrackingBorrowSpeed            | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| oldConfiguration.baseMinForRewards                  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 1000000000000                                                                                        |                                                              |
| oldConfiguration.baseBorrowMin                      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 100000000                                                                                            |                                                              |
| oldConfiguration.targetReserves                     | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 5000000000000                                                                                        |                                                              |
| oldConfiguration.assetConfigs                       | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619,0xF9680D99D6C9589e2a93a78A04A279e509205945,18,82500000000 |                                                              |
| newConfiguration                                    | STRUCT\<governor STRING, pauseGuardian STRING, baseToken STRING, baseTokenPriceFeed STRING, extensionDelegate STRING, supplyKink STRING, supplyPerYearInterestRateSlopeLow STRING, supplyPerYearInterestRateSlopeHigh STRING, supplyPerYearInterestRateBase STRING, borrowKink STRING, borrowPerYearInterestRateSlopeLow STRING, borrowPerYearInterestRateSlopeHigh STRING, borrowPerYearInterestRateBase STRING, storeFrontPriceFactor STRING, trackingIndexScale STRING, baseTrackingSupplySpeed STRING, baseTrackingBorrowSpeed STRING, baseMinForRewards STRING, baseBorrowMin STRING, targetReserves STRING, assetConfigs STRING> | {'governor': '0xcc3e7c85bb0ee4f09380e041fee95a0caedd4a02', 'pauseGuardian': '0x8ab717cac3cbc4934e638 |                                                              |
| newConfiguration.governor                           | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xcc3e7c85bb0ee4f09380e041fee95a0caedd4a02                                                           |                                                              |
| newConfiguration.pauseGuardian                      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x8ab717cac3cbc4934e63825b88442f5810aaf6e5                                                           |                                                              |
| newConfiguration.baseToken                          | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                                                           |                                                              |
| newConfiguration.baseTokenPriceFeed                 | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xfe4a8cc5b5b2366c1b58bea3858e81843581b2f7                                                           |                                                              |
| newConfiguration.extensionDelegate                  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0xbde8f31d2ddda895264e27dd990fab3dc87b372d                                                           |                                                              |
| newConfiguration.supplyKink                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 800000000000000000                                                                                   |                                                              |
| newConfiguration.supplyPerYearInterestRateSlopeLow  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 32500000000000000                                                                                    |                                                              |
| newConfiguration.supplyPerYearInterestRateSlopeHigh | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 400000000000000000                                                                                   |                                                              |
| newConfiguration.supplyPerYearInterestRateBase      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| newConfiguration.borrowKink                         | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 800000000000000000                                                                                   |                                                              |
| newConfiguration.borrowPerYearInterestRateSlopeLow  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 35000000000000004                                                                                    |                                                              |
| newConfiguration.borrowPerYearInterestRateSlopeHigh | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 250000000000000000                                                                                   |                                                              |
| newConfiguration.borrowPerYearInterestRateBase      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 15000000000000000                                                                                    |                                                              |
| newConfiguration.storeFrontPriceFactor              | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 600000000000000000                                                                                   |                                                              |
| newConfiguration.trackingIndexScale                 | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 1000000000000000                                                                                     |                                                              |
| newConfiguration.baseTrackingSupplySpeed            | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0                                                                                                    |                                                              |
| newConfiguration.baseTrackingBorrowSpeed            | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 402083333333                                                                                         |                                                              |
| newConfiguration.baseMinForRewards                  | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 1000000000000                                                                                        |                                                              |
| newConfiguration.baseBorrowMin                      | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 100000000                                                                                            |                                                              |
| newConfiguration.targetReserves                     | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 5000000000000                                                                                        |                                                              |
| newConfiguration.assetConfigs                       | VARCHAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | 0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619,0xF9680D99D6C9589e2a93a78A04A279e509205945,18,77500000000 |                                                              |

## 16. Table: Configurator\_v3\_event\_SetExtensionDelegate\_history

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

## 17. Table: Configurator\_v3\_event\_SetFactory\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 00:06:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39412431                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09dbaea6060b8162533c3212465aeda9e9ed823033a0d6abfcff0e12d2b16a66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 208                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x83e0f742cacbe66349e3701b171ee2487a26e738                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         |                                                              |
| oldFactory        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newFactory        | VARCHAR   | 0x2f9e3953b2ef89fa265f2a32ed9f80d00229125b                         |                                                              |

## 18. Table: Configurator\_v3\_event\_SetGovernor\_history

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

## 19. Table: Configurator\_v3\_event\_SetPauseGuardian\_history

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

## 20. Table: Configurator\_v3\_event\_SetStoreFrontPriceFactor\_history

| Column                   | Type      | Example                                                      | Description |
| ------------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp         | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number            | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash        | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index               | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address        | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy               | VARCHAR   |                                                              |             |
| oldStoreFrontPriceFactor | VARCHAR   |                                                              |             |
| newStoreFrontPriceFactor | VARCHAR   |                                                              |             |

## 21. Table: Configurator\_v3\_event\_SetSupplyKink\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldKink           | VARCHAR   |                                                              |             |
| newKink           | VARCHAR   |                                                              |             |

## 22. Table: Configurator\_v3\_event\_SetSupplyPerYearInterestRateBase\_history

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

## 23. Table: Configurator\_v3\_event\_SetSupplyPerYearInterestRateSlopeHigh\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldIRSlopeHigh    | VARCHAR   |                                                              |             |
| newIRSlopeHigh    | VARCHAR   |                                                              |             |

## 24. Table: Configurator\_v3\_event\_SetSupplyPerYearInterestRateSlopeLow\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy        | VARCHAR   |                                                              |             |
| oldIRSlopeLow     | VARCHAR   |                                                              |             |
| newIRSlopeLow     | VARCHAR   |                                                              |             |

## 25. Table: Configurator\_v3\_event\_SetTargetReserves\_history

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

## 26. Table: Configurator\_v3\_event\_UpdateAssetBorrowCollateralFactor\_history

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

## 27. Table: Configurator\_v3\_event\_UpdateAssetLiquidateCollateralFactor\_history

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

## 28. Table: Configurator\_v3\_event\_UpdateAssetLiquidationFactor\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| cometProxy           | VARCHAR   |                                                              |             |
| asset                | VARCHAR   |                                                              |             |
| oldLiquidationFactor | VARCHAR   |                                                              |             |
| newLiquidationFactor | VARCHAR   |                                                              |             |

## 29. Table: Configurator\_v3\_event\_UpdateAssetPriceFeed\_history

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

## 30. Table: Configurator\_v3\_event\_UpdateAssetSupplyCap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-18 20:42:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42868304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x36c0a9169d0f036ce97db11bb3927de81701d5e7ee57967b1992b01f54812c8e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 677                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x83e0f742cacbe66349e3701b171ee2487a26e738                         | Address of the contract that produced the log                |
| cometProxy        | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         |                                                              |
| asset             | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                         |                                                              |
| oldSupplyCap      | VARCHAR   | 11000000000000000000000                                            |                                                              |
| newSupplyCap      | VARCHAR   | 20000000000000000000000                                            |                                                              |

## 31. Table: Configurator\_v3\_event\_UpdateAsset\_history

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

## 32. Table: cUSDCv3\_event\_AbsorbCollateral\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-05-12 06:12:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 42603624                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x6a2c5fb17b176e445d4e684589030245c69035d4fcfaf6607116a64f4eedd09c | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| absorber           | VARCHAR   | 0x5a13d329a193ca3b1fe2d7b459097eddba14c28f                         |                                                              |
| borrower           | VARCHAR   | 0xdb1a1a83fe6546296e436a661a6d5073cc4ee732                         |                                                              |
| asset              | VARCHAR   | 0x1bfd67037b42cf73acf2047067bd4f2c47d9bfd6                         |                                                              |
| collateralAbsorbed | VARCHAR   | 646                                                                |                                                              |
| usdValue           | VARCHAR   | 16949878                                                           |                                                              |

## 33. Table: cUSDCv3\_event\_AbsorbDebt\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-08 07:49:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42445461                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7838e48bf8562816001ffd1571445304b00028ac479da3dfda2b455d9fe89a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| absorber          | VARCHAR   | 0xeb8e013b62211c7dcb12481379d1a879384a9000                         |                                                              |
| borrower          | VARCHAR   | 0xa54f59fbc7626a25e54a910f9323d87681890f31                         |                                                              |
| basePaidOut       | VARCHAR   | 266341676                                                          |                                                              |
| usdValue          | VARCHAR   | 26639521067                                                        |                                                              |

## 34. Table: cUSDCv3\_event\_BuyCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 18:20:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43721831                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b4931e715b1a3470a680813a886ac2b1e7aec0a701b06ac7379197ea0dbecc5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 583                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0xeb8e013b62211c7dcb12481379d1a879384a9000                         |                                                              |
| asset             | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| baseAmount        | VARCHAR   | 268693684                                                          |                                                              |
| collateralAmount  | VARCHAR   | 379075574759869306567                                              |                                                              |

## 35. Table: cUSDCv3\_event\_PauseAction\_history

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

## 36. Table: cUSDCv3\_event\_SupplyCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 14:53:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45942908                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2c3bbe4056014d40c19e7ca3428ff5ff18be6bf6e14dc70db8f26b9332760029 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x59e242d352ae13166b4987ae5c990c232f7f7cd6                         |                                                              |
| dst               | VARCHAR   | 0xe8f39efdb911ae8ef48df93dd6f5fba93db15597                         |                                                              |
| asset             | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| amount            | VARCHAR   | 238000000000000000000                                              |                                                              |

## 37. Table: cUSDCv3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 02:29:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45962213                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe20e5f96d72a105ad64ec780250a201157323e2853551b32d326ede8addd2cbf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xbc9ee85f27a3ea1260082197fdff373f986a45b2                         |                                                              |
| dst               | VARCHAR   | 0xbc9ee85f27a3ea1260082197fdff373f986a45b2                         |                                                              |
| amount            | VARCHAR   | 100                                                                |                                                              |

## 38. Table: cUSDCv3\_event\_TransferCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-31 19:18:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45751272                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8875db9281aaaceffcdee9801ee0815fde4a74a28fd736a2c3f21055a37e79ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xb50685c25485ca8c520f5286bbbf1d3f216d6989                         |                                                              |
| to                | VARCHAR   | 0x0ee0616cc47735dab6aa6bfa16a03301d1fc4db3                         |                                                              |
| asset             | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| amount            | VARCHAR   | 1000000592619694753                                                |                                                              |

## 39. Table: cUSDCv3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-03 07:54:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42247926                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x088fe3cfb79806d20be390ae01e152bb5408c103f5849b8bd8d18a4ecbb1bb4f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 408                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xa76ba6e28ac5660c8cf9374bda3c892b326749ff                         |                                                              |
| amount            | VARCHAR   | 3                                                                  |                                                              |

## 40. Table: cUSDCv3\_event\_WithdrawCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-17 02:03:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45169763                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf944b99ba0d432a4b0897143eebfb3c226469c5d325a68a0b0bb316de3b1e36c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x195eac2474a4d88bb72c4c7948f1bb9506b0c4c4                         |                                                              |
| to                | VARCHAR   | 0x195eac2474a4d88bb72c4c7948f1bb9506b0c4c4                         |                                                              |
| asset             | VARCHAR   | 0x1bfd67037b42cf73acf2047067bd4f2c47d9bfd6                         |                                                              |
| amount            | VARCHAR   | 79868                                                              |                                                              |

## 41. Table: cUSDCv3\_event\_WithdrawReserves\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 42. Table: cUSDCv3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 04:40:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43851665                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x71d115b3ee3c581f7d03060a8ff85dcead6e2bfdbc79c45781e0440d2c883c41 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 386                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf25212e676d1f7f89cd72ffee66158f541246445                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xfad6983c3b3a8242604af96422eb2a8175e4626e                         |                                                              |
| to                | VARCHAR   | 0xfad6983c3b3a8242604af96422eb2a8175e4626e                         |                                                              |
| amount            | VARCHAR   | 3187                                                               |                                                              |
