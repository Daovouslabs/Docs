# aave

## 1. Table: AToken\_v2\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 04:55:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32918477                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x311041fffb6ac0aa3cb6e630172d61cc35ea374e3543d1ebd127804346c6b225 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd45b7c061016102f9fa220502908f2c0f1add1d7                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x698758319f4182bc4ec4823ce31756f6af241ac6                         |                                                              |
| spender           | VARCHAR   | 0x1111111254eeb25477b68fb85ed929f73a960582                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: AToken\_v2\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-05 17:51:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14312459                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd88be7bc8780882088cc2e1c6ea7789e32b2956b06315d53b69e6559e29aa704 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd45b7c061016102f9fa220502908f2c0f1add1d7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc6eb02cc8e5ba7424b7e79e31791ea48f7a565fd                         |                                                              |
| to                | VARCHAR   | 0x2ecf2a2e74b19aab2a62312167aff4b78e93b6c5                         |                                                              |
| value             | VARCHAR   | 2800000000000000000                                                |                                                              |
| index             | VARCHAR   | 1000017879435186127588417234                                       |                                                              |

## 3. Table: AToken\_v2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 14:13:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18420993                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7caf357a62347f8c2ba82c08f61733b770a262a1e621a92f451eaa793d73b725 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x46a51127c3ce23fb7ab1de06226147f446e4a857                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x001e3ba199b4ff4b5b6e97acd96dafc0e2e4156e                         |                                                              |
| target            | VARCHAR   | 0x931db3f0c27956f9959293533f5191fd6954c9bb                         |                                                              |
| value             | VARCHAR   | 3006718055                                                         |                                                              |
| index             | VARCHAR   | 1015768444978678224428394845                                       |                                                              |

## 4. Table: AToken\_v2\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-15 01:10:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12121016                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f25bcf35f903e1440a6b520379f66bc45b5855039b5b888ecd4f814d121d770 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd45b7c061016102f9fa220502908f2c0f1add1d7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xba7f21acbce5f9b039e566cc0029c9eb7934ca42                         |                                                              |
| value             | VARCHAR   | 1097388136071575196                                                |                                                              |
| index             | VARCHAR   | 1000012108645171292508836912                                       |                                                              |

## 5. Table: AToken\_v2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 18:02:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22417666                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed139707966d39adf6fcc314e4fb2b4df89a86e6138531c8ac0ae31cd054c566 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x46a51127c3ce23fb7ab1de06226147f446e4a857                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7f90122bf0700f9e7e1f688fe926940e8839f353                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 2502313352                                                         |                                                              |

## 6. Table: AToken\_v3\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 15:33:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31282938                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8511cf6ddf84cbc8cdac3ca60d9b2b8ec6b03e798c52b627777727799b2b0370 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xdb1bf5cb3b4d3f55bfcb290f079178c81692d9b5                         |                                                              |
| spender           | VARCHAR   | 0x00e39085c877328619fdb2a47d995c516a5fa869                         |                                                              |
| value             | VARCHAR   | 5214524                                                            |                                                              |

## 7. Table: AToken\_v3\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-30 02:49:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17976305                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x216d1b57b649f70f32a629538cd4f51ce7a9f2f1cf1cf24b75cddff91445f8c4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0116bc6d6248a99cfcc0d644ed3250a7c45b3c94                         |                                                              |
| to                | VARCHAR   | 0xf7fc20d9d1d8dfe55f5f2c3180272a5747dd327f                         |                                                              |
| value             | VARCHAR   | 15619812                                                           |                                                              |
| index             | VARCHAR   | 1000161804352069223871727536                                       |                                                              |

## 8. Table: AToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-31 17:44:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21783043                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x659b852c1362bcb9094dba7cc719bf0b05bf9d5a0d55e5c570d67db46a098056 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0dcd7b66be110d19c72a4ba6740697fc73bad170                         |                                                              |
| target            | VARCHAR   | 0x0dcd7b66be110d19c72a4ba6740697fc73bad170                         |                                                              |
| value             | VARCHAR   | 16822950                                                           |                                                              |
| balanceIncrease   | VARCHAR   | 8271                                                               |                                                              |
| index             | VARCHAR   | 1000597124996954682323075372                                       |                                                              |

## 9. Table: AToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-05-15 06:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 30040333                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xe5fcaff187f210b3f06811d991cfd225614b0cd06b1cae2008f4009e0499fced | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x625e7708f30ca75bfd92586e17077590c60eb4cd                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0xb97ef9ef8734c71904d8002f8b6bc66dd9c48a6e                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| treasury             | VARCHAR   | 0x5ba7fd868c40c16f7adfae6cf87121e13fc2f7a0                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| aTokenDecimals       | VARCHAR   | 6                                                                  |                                                              |
| aTokenName           | VARCHAR   | Aave Avalanche USDC                                                |                                                              |
| aTokenSymbol         | VARCHAR   | aAvaUSDC                                                           |                                                              |
| params               | VARCHAR   | 0x30783130                                                         |                                                              |

## 10. Table: AToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-29 15:41:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30649394                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e772c58f063819dc647c9b5d98d5da1e968acf747d2e0e46b5c6815750136f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x625e7708f30ca75bfd92586e17077590c60eb4cd                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x9c90d1bcbc6b69e168c786c9a52a2817575ab758                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x9c90d1bcbc6b69e168c786c9a52a2817575ab758                         |                                                              |
| value             | VARCHAR   | 2020000000                                                         |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1020614914467184454659880437                                       |                                                              |

## 11. Table: AToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 01:23:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29861300                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8804a050e4a31fe80d4ea2179a12da1af42a7a5500590c7cf3e087980ff7f444 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x00e39085c877328619fdb2a47d995c516a5fa869                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 3618214                                                            |                                                              |

## 12. Table: LendingPoolConfigurator\_v2\_event\_ATokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-04 08:43:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29577182                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6da4fafc12a05dc85179f6282f808c0b08ea4981501a2fcd297c91c0ba00365 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x230b618ad4c475393a7239ae03630042281bd86e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| proxy             | VARCHAR   | 0xdfe521292ece2a4f44242efbcd66bc594ca9714b                         |                                                              |
| implementation    | VARCHAR   | 0x44b4221c950fcf23a40e68dea29fed0bb88893a9                         |                                                              |

## 13. Table: LendingPoolConfigurator\_v2\_event\_BorrowingDisabledOnReserve\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 14. Table: LendingPoolConfigurator\_v2\_event\_BorrowingEnabledOnReserve\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-20 13:24:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4607272                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb302fd9a11eb40b8fe5cde45ed3eae3ec17b6f30d97897ae357e3b4de4e1ab87 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x230b618ad4c475393a7239ae03630042281bd86e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| stableRateEnabled | VARCHAR   | false                                                              |                                                              |

## 15. Table: LendingPoolConfigurator\_v2\_event\_CollateralConfigurationChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-09-20 13:24:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 4607272                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xb302fd9a11eb40b8fe5cde45ed3eae3ec17b6f30d97897ae357e3b4de4e1ab87 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x230b618ad4c475393a7239ae03630042281bd86e                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0xc7198437980c041c805a1edcba50c1ce5db95118                         |                                                              |
| ltv                  | VARCHAR   | 0                                                                  |                                                              |
| liquidationThreshold | VARCHAR   | 0                                                                  |                                                              |
| liquidationBonus     | VARCHAR   | 0                                                                  |                                                              |

## 16. Table: LendingPoolConfigurator\_v2\_event\_ReserveActivated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 17. Table: LendingPoolConfigurator\_v2\_event\_ReserveDeactivated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 18. Table: LendingPoolConfigurator\_v2\_event\_ReserveDecimalsChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| decimals          | VARCHAR   |                                                              |             |

## 19. Table: LendingPoolConfigurator\_v2\_event\_ReserveFactorChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-28 15:41:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4957383                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26f44a25710984195703bdce8476cdfc0818cdc9954c8fec9ba64161b69949f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x230b618ad4c475393a7239ae03630042281bd86e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x50b7545627a5162f82a992c33b87adc75187b218                         |                                                              |
| factor            | VARCHAR   | 1000                                                               |                                                              |

## 20. Table: LendingPoolConfigurator\_v2\_event\_ReserveFrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 21. Table: LendingPoolConfigurator\_v2\_event\_ReserveInitialized\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2021-09-20 13:23:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 4607228                                                            | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x9dcd392af519a2f01341e1cbbcb78778475175b23af679f825f79dbd20814da6 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x230b618ad4c475393a7239ae03630042281bd86e                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0x63a72806098bd3d9520cc43356dd78afe5d386d9                         |                                                              |
| aToken                      | VARCHAR   | 0xd45b7c061016102f9fa220502908f2c0f1add1d7                         |                                                              |
| stableDebtToken             | VARCHAR   | 0x66904e4f3f44e3925d22ceca401b6f2da085c98f                         |                                                              |
| variableDebtToken           | VARCHAR   | 0x8352e3fd18b8d84d3c8a1b538d788899073c7a8e                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0x6724e923e4bb58fcdf7cee7a5e7bbb47b99c2647                         |                                                              |

## 22. Table: LendingPoolConfigurator\_v2\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| strategy          | VARCHAR   |                                                              |             |

## 23. Table: LendingPoolConfigurator\_v2\_event\_ReserveUnfrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 24. Table: LendingPoolConfigurator\_v2\_event\_StableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| proxy             | VARCHAR   |                                                              |             |
| implementation    | VARCHAR   |                                                              |             |

## 25. Table: LendingPoolConfigurator\_v2\_event\_StableRateDisabledOnReserve\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 26. Table: LendingPoolConfigurator\_v2\_event\_StableRateEnabledOnReserve\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 27. Table: LendingPoolConfigurator\_v2\_event\_VariableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| proxy             | VARCHAR   |                                                              |             |
| implementation    | VARCHAR   |                                                              |             |

## 28. Table: LendingPool\_v2\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 14:43:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29927315                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2fb9745d79ce6ff6cbf80ed7c5ba1fca64b41a020ab021c1be83787f8881f2db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xa7d7079b0fead91f3e65f86e8915cb59c1a4c664                         |                                                              |
| user              | VARCHAR   | 0xa3b61c4a1cf9b8339724458ef6c6322488210aea                         |                                                              |
| onBehalfOf        | VARCHAR   | 0xa3b61c4a1cf9b8339724458ef6c6322488210aea                         |                                                              |
| amount            | VARCHAR   | 2000000000                                                         |                                                              |
| borrowRateMode    | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 29523565811359497266145309                                         |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 29. Table: LendingPool\_v2\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-15 23:28:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9622510                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xafe65ec565312470e46bb019a7fc39fc006158a8bb2696dc68d84df12f79a717 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| user              | VARCHAR   | 0x054c950a46c720125554683227159cfe525d9dd9                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x054c950a46c720125554683227159cfe525d9dd9                         |                                                              |
| amount            | VARCHAR   | 1499101148002150396                                                |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 30. Table: LendingPool\_v2\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 04:27:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18489374                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x10e097056680cc11da68e9b77748c225b35645b148bd894d636dadf3a7ba0dca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x1b279613b81b2c16da34659678caecf479f462db                         |                                                              |
| initiator         | VARCHAR   | 0x1b279613b81b2c16da34659678caecf479f462db                         |                                                              |
| asset             | VARCHAR   | 0xc7198437980c041c805a1edcba50c1ce5db95118                         |                                                              |
| amount            | VARCHAR   | 193634032                                                          |                                                              |
| premium           | VARCHAR   | 174270                                                             |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 31. Table: LendingPool\_v2\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2022-06-20 10:05:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 16278089                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0x51f2fc0dd2f5725094bd40e266f01fc2d26863b1cabbe940371cbda5176418bb | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| debtAsset                  | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| user                       | VARCHAR   | 0x401c869d5b8b469c3bf4ee0c1a69d426298fd744                         |                                                              |
| debtToCover                | VARCHAR   | 987172867829568582                                                 |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 1085890154612525440                                                |                                                              |
| liquidator                 | VARCHAR   | 0x148fc961f079292178a9df62289d8efde46fe1cb                         |                                                              |
| receiveAToken              | VARCHAR   | false                                                              |                                                              |

## 32. Table: LendingPool\_v2\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-20 13:20:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4607038                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1da95a52c8e09837580bcce7202161e31fecd92030ee43bcf1eaf730c7ccb0ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |

## 33. Table: LendingPool\_v2\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 34. Table: LendingPool\_v2\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 16:23:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13500930                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb973a1863048546c8e195e4e013714e560a3b3089c3b4e26e610abc1a6cf7c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x50b7545627a5162f82a992c33b87adc75187b218                         |                                                              |
| user              | VARCHAR   | 0x0a4fc1b3308e763a6a322f38138748a781d5b576                         |                                                              |
| repayer           | VARCHAR   | 0x0a4fc1b3308e763a6a322f38138748a781d5b576                         |                                                              |
| amount            | VARCHAR   | 10524725                                                           |                                                              |

## 35. Table: LendingPool\_v2\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-08-06 16:47:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 33575817                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x7e7a19dbff4254bc1427aa308b7498ac3569c79d06a9c037ccbbcfa8610d4f89 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| liquidityRate       | VARCHAR   | 895341015659993064568427                                           |                                                              |
| stableBorrowRate    | VARCHAR   | 30000000000000000000000000                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 12439867322562639142353316                                         |                                                              |
| liquidityIndex      | VARCHAR   | 1005070406756169443409102821                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1024784908824559432046051685                                       |                                                              |

## 36. Table: LendingPool\_v2\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 16:47:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25615987                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab2f7593f56788fec71b86dcb44fa3838db106968b86aff82fbaceccde64ff0f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| user              | VARCHAR   | 0xb25219a402f18160d30b7e827cf9f592989b081b                         |                                                              |

## 37. Table: LendingPool\_v2\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-17 11:43:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30134209                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0db447187dde5ca8bf4fe726396e9bfd3a7c614b11a1d8ef47cb5d1988d58942 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xa7d7079b0fead91f3e65f86e8915cb59c1a4c664                         |                                                              |
| user              | VARCHAR   | 0x06534b0bf7ff378f162d4f348390bda53b15fa35                         |                                                              |

## 38. Table: LendingPool\_v2\_event\_Swap\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |
| rateMode          | VARCHAR   |                                                              |             |

## 39. Table: LendingPool\_v2\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-04 12:30:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5203243                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x959c8fe4ebcd249379e3e37b8ba4783e5369522d90f7408fb5e436d0ec492b0e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |

## 40. Table: LendingPool\_v2\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 08:10:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10467048                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26528ecd7af9681113447c214280e2b726b1542d9ce37f884ac68f8f2f140e58 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f01aed16d97e3ab5ab2b501154dc9bb0f1a5a2c                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| user              | VARCHAR   | 0x00639e7e0ef1ec719ea297e707618fafbe0ffda7                         |                                                              |
| to                | VARCHAR   | 0x00639e7e0ef1ec719ea297e707618fafbe0ffda7                         |                                                              |
| amount            | VARCHAR   | 1259157334453884583                                                |                                                              |

## 41. Table: PoolConfigurator\_event\_ATokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 06:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30040333                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5fcaff187f210b3f06811d991cfd225614b0cd06b1cae2008f4009e0499fced | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| proxy             | VARCHAR   | 0x6d80113e533a2c0fe82eabd35f1875dcea89ea97                         |                                                              |
| implementation    | VARCHAR   | 0x1e81af09001ad208bda68ff022544db2102a752d                         |                                                              |

## 42. Table: PoolConfigurator\_event\_BorrowCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 08:18:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24249245                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5d3eb44f7c90e7487ebaf79c4869f20179f3af78aff8554341e678af76d1571 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x5947bb275c521040051d82396192181b413227a3                         |                                                              |
| oldBorrowCap      | VARCHAR   | 0                                                                  |                                                              |
| newBorrowCap      | VARCHAR   | 207081                                                             |                                                              |

## 43. Table: PoolConfigurator\_event\_BorrowableInIsolationChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 13:43:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11974739                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb03f76a9559e2b98da2014497bfe475edd1c34e26b7be143d5d562c6fad836f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xb97ef9ef8734c71904d8002f8b6bc66dd9c48a6e                         |                                                              |
| borrowable        | VARCHAR   | true                                                               |                                                              |

## 44. Table: PoolConfigurator\_event\_BridgeProtocolFeeUpdated\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| oldBridgeProtocolFee | VARCHAR   |                                                              |             |
| newBridgeProtocolFee | VARCHAR   |                                                              |             |

## 45. Table: PoolConfigurator\_event\_CollateralConfigurationChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-03-11 13:08:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 27300857                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x1e6793fcc4713dc0585bdb40ee1170a07acc90fd46c50012d6046018cdfda5de | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0x5c49b268c9841aff1cc3b0a418ff5c3442ee3f3b                         |                                                              |
| ltv                  | VARCHAR   | 0                                                                  |                                                              |
| liquidationThreshold | VARCHAR   | 8000                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10500                                                              |                                                              |

## 46. Table: PoolConfigurator\_event\_DebtCeilingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 13:40:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11974674                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xef5df5d48529b3ff32ffaeed5f33789744a2ede15d40ada9c09cf597e905bfaa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x9702230a8ea53601f5cd2dc00fdbc13d4df4a8c7                         |                                                              |
| oldDebtCeiling    | VARCHAR   | 0                                                                  |                                                              |
| newDebtCeiling    | VARCHAR   | 5000000                                                            |                                                              |

## 47. Table: PoolConfigurator\_event\_EModeAssetCategoryChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-30 12:58:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16715092                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xacfaf49090d3182e0c77a0d9e41b3be157fc24bbf18da9dacc9c2bfb3d65ba3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x2b2c81e08f1af8835a78bb2a90ae924ace0ea4be                         |                                                              |
| oldCategoryId     | VARCHAR   | 0                                                                  |                                                              |
| newCategoryId     | VARCHAR   | 2                                                                  |                                                              |

## 48. Table: PoolConfigurator\_event\_EModeCategoryAdded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-07-31 22:34:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 33330336                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x11e9651b84a651b1ce435447ab73e79a8ec2a3504deab4c27ec76678579c02fb | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| categoryId           | VARCHAR   | 1                                                                  |                                                              |
| ltv                  | VARCHAR   | 9300                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 9500                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10100                                                              |                                                              |
| oracle               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| label                | VARCHAR   | Stablecoins                                                        |                                                              |

## 49. Table: PoolConfigurator\_event\_FlashloanPremiumToProtocolUpdated\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2023-05-15 06:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 30040333                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0xe5fcaff187f210b3f06811d991cfd225614b0cd06b1cae2008f4009e0499fced | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumToProtocol | VARCHAR   | 0                                                                  |                                                              |
| newFlashloanPremiumToProtocol | VARCHAR   | 4                                                                  |                                                              |

## 50. Table: PoolConfigurator\_event\_FlashloanPremiumTotalUpdated\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2023-05-15 06:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 30040333                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xe5fcaff187f210b3f06811d991cfd225614b0cd06b1cae2008f4009e0499fced | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumTotal | VARCHAR   | 9                                                                  |                                                              |
| newFlashloanPremiumTotal | VARCHAR   | 5                                                                  |                                                              |

## 51. Table: PoolConfigurator\_event\_LiquidationProtocolFeeChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 13:45:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11974791                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e6d5ee4d7222ee919c30682219fa493fa5d6e09184c3df9d5daf43f30a9096a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| oldFee            | VARCHAR   | 0                                                                  |                                                              |
| newFee            | VARCHAR   | 1000                                                               |                                                              |

## 52. Table: PoolConfigurator\_event\_ReserveActive\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| active            | VARCHAR   |                                                              |             |

## 53. Table: PoolConfigurator\_event\_ReserveBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 13:39:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11974622                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7801b9913a5b6af0edbc39c4dcaf37196916b935dd26c7a0d0ed94fd6df8dcf2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x50b7545627a5162f82a992c33b87adc75187b218                         |                                                              |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 54. Table: PoolConfigurator\_event\_ReserveDropped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 55. Table: PoolConfigurator\_event\_ReserveFactorChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-20 08:50:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28985066                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x259fb521d7bdc0690cf5f72c6e25efd6fc80ba79e0fc66912edbc0ee5e00b28c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| oldReserveFactor  | VARCHAR   | 1000                                                               |                                                              |
| newReserveFactor  | VARCHAR   | 1500                                                               |                                                              |

## 56. Table: PoolConfigurator\_event\_ReserveFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-03 12:22:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25779365                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x525e7cad64bd164b01bb6cf0fff47a459a20e30b655598a699fc1af048211787 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| frozen            | VARCHAR   | true                                                               |                                                              |

## 57. Table: PoolConfigurator\_event\_ReserveInitialized\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2022-09-23 07:25:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 20167422                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0xdfe07773091925a3dd20f233360aab86c004b87f90d80d20bde67bec13c20965 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| aToken                      | VARCHAR   | 0x8ffdf2de812095b1d19cb146e4c004587c0a0692                         |                                                              |
| stableDebtToken             | VARCHAR   | 0xa5e408678469d23efdb7694b1b0a85bb0669e8bd                         |                                                              |
| variableDebtToken           | VARCHAR   | 0xa8669021776bc142dfca87c21b4a52595bcbb40a                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0x79a906e8c998d2fb5c5d66d23c4c5416fe0168d6                         |                                                              |

## 58. Table: PoolConfigurator\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 07:34:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30804240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ce6b2cde6152f591a1a17a6a1fbe5e176404a50d5a454d60b2a0538ecdb7750 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x50b7545627a5162f82a992c33b87adc75187b218                         |                                                              |
| oldStrategy       | VARCHAR   | 0x79a906e8c998d2fb5c5d66d23c4c5416fe0168d6                         |                                                              |
| newStrategy       | VARCHAR   | 0x354e84ec43acd91e1c0135c3e691960e881db4b7                         |                                                              |

## 59. Table: PoolConfigurator\_event\_ReservePaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-16 10:15:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12178304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d5fd6679d84d23cec94741c86b9fe783e67e7cd70a2963aad8045a44767a30f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x50b7545627a5162f82a992c33b87adc75187b218                         |                                                              |
| paused            | VARCHAR   | false                                                              |                                                              |

## 60. Table: PoolConfigurator\_event\_ReserveStableRateBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-01 08:44:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12849531                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf58db63cabebad05bb2eb33df25a18fcc2bba467bec79e06d247bcf30910a019 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x50b7545627a5162f82a992c33b87adc75187b218                         |                                                              |
| enabled           | VARCHAR   | false                                                              |                                                              |

## 61. Table: PoolConfigurator\_event\_SiloedBorrowingChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| oldState          | VARCHAR   |                                                              |             |
| newState          | VARCHAR   |                                                              |             |

## 62. Table: PoolConfigurator\_event\_StableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 06:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30040333                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5fcaff187f210b3f06811d991cfd225614b0cd06b1cae2008f4009e0499fced | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| proxy             | VARCHAR   | 0xf15f26710c827dde8acba678682f3ce24f2fb56e                         |                                                              |
| implementation    | VARCHAR   | 0x893411580e590d62ddbca8a703d61cc4a8c7b2b9                         |                                                              |

## 63. Table: PoolConfigurator\_event\_SupplyCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 18:02:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31118572                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8a83d50327c29bdbf487d4c16d43746fa8f9b8c3eefba13838e4599df65d090 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x2b2c81e08f1af8835a78bb2a90ae924ace0ea4be                         |                                                              |
| oldSupplyCap      | VARCHAR   | 2000000                                                            |                                                              |
| newSupplyCap      | VARCHAR   | 2200000                                                            |                                                              |

## 64. Table: PoolConfigurator\_event\_UnbackedMintCapChanged\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| asset              | VARCHAR   |                                                              |             |
| oldUnbackedMintCap | VARCHAR   |                                                              |             |
| newUnbackedMintCap | VARCHAR   |                                                              |             |

## 65. Table: PoolConfigurator\_event\_VariableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 06:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30040333                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5fcaff187f210b3f06811d991cfd225614b0cd06b1cae2008f4009e0499fced | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| proxy             | VARCHAR   | 0x4a1c3ad6ed28a636ee1751c69071f6be75deb8b8                         |                                                              |
| implementation    | VARCHAR   | 0xa0d9c1e9e48ca30c8d8c3b5d69ff5dc1f6dffc24                         |                                                              |

## 66. Table: Pool\_v3\_event\_BackUnbacked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| backer            | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |

## 67. Table: Pool\_v3\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 21:51:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32693240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9564a828e1a148e18a9bf6607f8fad41ad48e48f9ee2fd749e0ef0c329f0fef0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xb97ef9ef8734c71904d8002f8b6bc66dd9c48a6e                         |                                                              |
| user              | VARCHAR   | 0x4ea3c5a2720eda6759f50ed2fc23e1bc795d00d0                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x4ea3c5a2720eda6759f50ed2fc23e1bc795d00d0                         |                                                              |
| amount            | VARCHAR   | 243                                                                |                                                              |
| interestRateMode  | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 31458155936047911807223890                                         |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 68. Table: Pool\_v3\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 20:08:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32945389                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb38c6f9ff2a21d6083fdaaa3c0b3500d00db21bb5b45e33edd8f0a83f0386973 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x49f5b996814fed1dd39285b92a59cfb2dfd8d4f9                         |                                                              |
| initiator         | VARCHAR   | 0x1322c4ea25d6c908dc491b2561ed1161b064c631                         |                                                              |
| asset             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| amount            | VARCHAR   | 71541780899846220000                                               |                                                              |
| interestRateMode  | VARCHAR   | 0                                                                  |                                                              |
| premium           | VARCHAR   | 35770890449923110                                                  |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 69. Table: Pool\_v3\_event\_IsolationModeTotalDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 06:12:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32410148                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcfed0a47506f48f065941b5033cbccb447b4b9191211661b42594b9df757d274 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x9702230a8ea53601f5cd2dc00fdbc13d4df4a8c7                         |                                                              |
| totalDebt         | VARCHAR   | 962197                                                             |                                                              |

## 70. Table: Pool\_v3\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-06-15 09:25:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 31356084                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0xfebea1ec4f45a8aac75812fe8d609d694e35a74b22ca8372cad90edfbe883050 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0xb97ef9ef8734c71904d8002f8b6bc66dd9c48a6e                         |                                                              |
| debtAsset                  | VARCHAR   | 0xb97ef9ef8734c71904d8002f8b6bc66dd9c48a6e                         |                                                              |
| user                       | VARCHAR   | 0x46f2204a44b13242ea9faab75b1a15ae6cfbbbe0                         |                                                              |
| debtToCover                | VARCHAR   | 15735161243                                                        |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 15876777694                                                        |                                                              |
| liquidator                 | VARCHAR   | 0x0dd8c1e6dd0770e50f8fab66574dede48f3cd655                         |                                                              |
| receiveAToken              | VARCHAR   | false                                                              |                                                              |

## 71. Table: Pool\_v3\_event\_MintUnbacked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |
| onBehalfOf        | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| referralCode      | VARCHAR   |                                                              |             |

## 72. Table: Pool\_v3\_event\_MintedToTreasury\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-13 19:00:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26215907                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x413e62c4fb6c312aa03fa4a6eaf84423469290ef38e705f2a5ee54ab0902adbf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x5947bb275c521040051d82396192181b413227a3                         |                                                              |
| amountMinted      | VARCHAR   | 47156794539008442                                                  |                                                              |

## 73. Table: Pool\_v3\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 74. Table: Pool\_v3\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 11:52:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28648177                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7908682176f470f6d283dbc22411610063d0a0b81dd99cba0ed256ced42d6a84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| user              | VARCHAR   | 0x67165052d842662efd917874c1878512d6b0b4fe                         |                                                              |
| repayer           | VARCHAR   | 0x67165052d842662efd917874c1878512d6b0b4fe                         |                                                              |
| amount            | VARCHAR   | 6636401                                                            |                                                              |
| useATokens        | VARCHAR   | true                                                               |                                                              |

## 75. Table: Pool\_v3\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-08-03 01:05:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 33419902                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x79a43acc918ba437fda56484d70b49a7debb08ee9d41f7ec12739ce6407502f2 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| liquidityRate       | VARCHAR   | 4262494327053471819457944                                          |                                                              |
| stableBorrowRate    | VARCHAR   | 79814089199094865176271459                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 21223384739140121917457886                                         |                                                              |
| liquidityIndex      | VARCHAR   | 1007541498237347861310123467                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1032303290658519490266271026                                       |                                                              |

## 76. Table: Pool\_v3\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 22:07:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33457190                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0f383f5c6728f4b2c4ea79f80dec26d2e537a97874752137d089084f9b5fdbc1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| user              | VARCHAR   | 0x262de401248378d3d62a325adb2e052786b340f9                         |                                                              |

## 77. Table: Pool\_v3\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 09:38:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15797948                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14110c6f6c9bb71b67f26777dc25f71f403511554584376990f1e9e52c71e465 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| user              | VARCHAR   | 0x0087fb5367d680170916c350d1b5bba973f60397                         |                                                              |

## 78. Table: Pool\_v3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-17 01:44:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30116650                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa1b1ab90c164f90d2f2b0bbe9695a4f0e9cc1227bc4519e76bf702fd0487dd7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| user              | VARCHAR   | 0x08b7e2f17bf9c98dc1f30d79b827fd5d25e1e573                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x08b7e2f17bf9c98dc1f30d79b827fd5d25e1e573                         |                                                              |
| amount            | VARCHAR   | 1326                                                               |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 79. Table: Pool\_v3\_event\_SwapBorrowRateMode\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-04 07:28:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30889062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d86dcccfb72d8313fd6e9a5980752a905065c3b39c477a9fb0dc4e9ad3750bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xb97ef9ef8734c71904d8002f8b6bc66dd9c48a6e                         |                                                              |
| user              | VARCHAR   | 0x543017cd4828a626620abca137edb58c635f45d6                         |                                                              |
| interestRateMode  | VARCHAR   | 1                                                                  |                                                              |

## 80. Table: Pool\_v3\_event\_UserEModeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 19:28:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33580606                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2df97fdfada8ed12ff909f3d89147a9ab25e23d6565779458b2fb689198ff7d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xa5620d997b52aa7ed8ced91bcc49d6c6b9b9f014                         |                                                              |
| categoryId        | VARCHAR   | 1                                                                  |                                                              |

## 81. Table: Pool\_v3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 17:04:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29974015                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc4e1f57262b67c9b67c6d0b15f4227969381ebbbb7f66d209308cc2871334d2e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x152b9d0fdc40c096757f570a51e494bd4b943e50                         |                                                              |
| user              | VARCHAR   | 0x00e39085c877328619fdb2a47d995c516a5fa869                         |                                                              |
| to                | VARCHAR   | 0x00e39085c877328619fdb2a47d995c516a5fa869                         |                                                              |
| amount            | VARCHAR   | 143786917                                                          |                                                              |

## 82. Table: StableDebtToken\_v2\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 83. Table: StableDebtToken\_v2\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-05 22:30:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29643923                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb67e271265736f0d1f63bfb07fb56cca4ec73698988cf1cb66cc389a70d0d72e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x60f6a45006323b97d97cb0a42ac39e2b757ada63                         | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x4a89caae3daf3ec08823479dd2389ce34f0e6c96                         |                                                              |
| toUser            | VARCHAR   | 0x0be615d7084afad855aad40cf3df89b4c440a183                         |                                                              |
| asset             | VARCHAR   | 0x49d5c2bdffac6ce2bfdb6640f4f80f226bc10bab                         |                                                              |
| amount            | VARCHAR   | 1000000                                                            |                                                              |

## 84. Table: StableDebtToken\_v2\_event\_Burn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| currentBalance    | VARCHAR   |                                                              |             |
| balanceIncrease   | VARCHAR   |                                                              |             |
| avgStableRate     | VARCHAR   |                                                              |             |
| newTotalSupply    | VARCHAR   |                                                              |             |

## 85. Table: StableDebtToken\_v2\_event\_Mint\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |
| onBehalfOf        | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| currentBalance    | VARCHAR   |                                                              |             |
| balanceIncrease   | VARCHAR   |                                                              |             |
| newRate           | VARCHAR   |                                                              |             |
| avgStableRate     | VARCHAR   |                                                              |             |
| newTotalSupply    | VARCHAR   |                                                              |             |

## 86. Table: StableDebtToken\_v2\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 87. Table: StableDebtToken\_v3\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 88. Table: StableDebtToken\_v3\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-30 11:25:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17991303                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8bfd099c29991ad09f34cfaa9781ecade878377e190b076945794b953fd1dae8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70effc565db6eef7b927610155602d31b670e802                         | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0xe214fba86beed196aac68934bf4822c1cff6b0b8                         |                                                              |
| toUser            | VARCHAR   | 0xe214fba86beed196aac68934bf4822c1cff6b0b8                         |                                                              |
| asset             | VARCHAR   | 0x9702230a8ea53601f5cd2dc00fdbc13d4df4a8c7                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000                                                |                                                              |

## 89. Table: StableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-25 20:56:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12573310                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x573b55d8e9ed746e16515612915cae62c00330955f66d36411d360c908e8dd83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd94112b5b62d53c9402e7a60289c6810def1dc9b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3441c49613f556c0bf62c788ef2c608ef8fb3899                         |                                                              |
| amount            | VARCHAR   | 249689227343009107252                                              |                                                              |
| currentBalance    | VARCHAR   | 250306643328989095974                                              |                                                              |
| balanceIncrease   | VARCHAR   | 306643328989095974                                                 |                                                              |
| avgStableRate     | VARCHAR   | 69135860291951862581908052                                         |                                                              |
| newTotalSupply    | VARCHAR   | 26132568993117093095015                                            |                                                              |

## 90. Table: StableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-03-11 12:28:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 11972624                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xf5a3c8ef22f7875589974ca3d87f2b02cc20d9f88664a14b386cf28747395c20 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0xb97ef9ef8734c71904d8002f8b6bc66dd9c48a6e                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0xf88807b552aa22c4dd7b00fd1645a63b2fca9f7b                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 6                                                                  |                                                              |
| debtTokenName        | VARCHAR   | Aave Avalanche Stable Debt USDC                                    |                                                              |
| debtTokenSymbol      | VARCHAR   | stableDebtAvaUSDC                                                  |                                                              |
| params               | VARCHAR   | 0x10                                                               |                                                              |

## 91. Table: StableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 07:26:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30381051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0f01ddb6135b9cb01000fd3e5b63bd6ee0711cde08075c50a1a15a562c1a318b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x022ac4cd6291b77ba01ad70f61f5fff60198ed82                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x022ac4cd6291b77ba01ad70f61f5fff60198ed82                         |                                                              |
| amount            | VARCHAR   | 90002548                                                           |                                                              |
| currentBalance    | VARCHAR   | 1007712184                                                         |                                                              |
| balanceIncrease   | VARCHAR   | 2548                                                               |                                                              |
| newRate           | VARCHAR   | 52943123776835401327749132                                         |                                                              |
| avgStableRate     | VARCHAR   | 53005541368579038861631749                                         |                                                              |
| newTotalSupply    | VARCHAR   | 96838711464                                                        |                                                              |

## 92. Table: StableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 21:32:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33456155                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x40209b78e6abe788e24ed50ac4fda32933453247dd404cb01f1607e16de3ea0e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xe6b9bb760e56e3f43b6e839ac3d738039ec0cdeb                         |                                                              |
| value             | VARCHAR   | 200000000                                                          |                                                              |

## 93. Table: VariableDebtToken\_v2\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 94. Table: VariableDebtToken\_v2\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-28 16:11:15+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22955900                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbd56d2089abaf7e704ddd1945805ef9f1876f96765a6eba444513b9939caca06             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x66a0fe52fb629a6cb4d10b8580afdffe888f5fd4                                     | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x92c6f8f00a21a586ffd2b0d0ed473585464724a6                                     |                                                              |
| toUser            | VARCHAR   | 0xc27d4dbefc2c0ce57916a699971b58a3bd9c7d5b                                     |                                                              |
| asset             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564028857584007913129639935 |                                                              |

## 95. Table: VariableDebtToken\_v2\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-26 08:48:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16535025                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x233b5f97b2d9030f4725eda286d3776617c3f3ff25fa5eedd52424f5b6b973ee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1852dc24d1a8956a0b356aa18ede954c7a0ca5ae                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x8b237c171053f081c92928bdb37b17b3794cd922                         |                                                              |
| amount            | VARCHAR   | 371782594738162635314                                              |                                                              |
| index             | VARCHAR   | 1023479687885610937967756086                                       |                                                              |

## 96. Table: VariableDebtToken\_v2\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-31 22:17:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25667854                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbf8b477bff72dd64c453f3249885bba2aebc57f534eda4b4eef43e7157ec5a1f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1852dc24d1a8956a0b356aa18ede954c7a0ca5ae                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xec140f4ae6504b535dde6b1ab25366a764a35d5f                         |                                                              |
| onBehalfOf        | VARCHAR   | 0xec140f4ae6504b535dde6b1ab25366a764a35d5f                         |                                                              |
| value             | VARCHAR   | 300000000000000000                                                 |                                                              |
| index             | VARCHAR   | 1034906522602506618705140196                                       |                                                              |

## 97. Table: VariableDebtToken\_v2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-22 20:17:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20148604                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7303e6424e99d83c5666f5595ff8bde6cef628333ffe786aed7f4631b43b6b11 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1852dc24d1a8956a0b356aa18ede954c7a0ca5ae                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x4e4a1fc674667ab8cbe2039ff79306d57d2dae4c                         |                                                              |
| value             | VARCHAR   | 4302572362586219455206                                             |                                                              |

## 98. Table: VariableDebtToken\_v3\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| owner             | VARCHAR   |                                                              |             |
| spender           | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 99. Table: VariableDebtToken\_v3\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-07 17:47:49+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14395690                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc64deabbfc3835cb28e44f6cbd2a5c589a2e35c72d18f521d8516d1e74bbfeb6             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a1c3ad6ed28a636ee1751c69071f6be75deb8b8                                     | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x2b133847465ce196015044afbe675afdda482e1b                                     |                                                              |
| toUser            | VARCHAR   | 0xa938d8536aeed1bd48f548380394ab30aa11b00e                                     |                                                              |
| asset             | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564034062672952963090770725 |                                                              |

## 100. Table: VariableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 16:58:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33490626                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6ca320457ec90b50917ed53497a4db2172d7c48cc39bacd4ceb0d2de06a5c431 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x4aaee20543e118a5f86d626ed5b98e37b9835ebf                         |                                                              |
| target            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 69794813264144761095                                               |                                                              |
| balanceIncrease   | VARCHAR   | 7068805349883                                                      |                                                              |
| index             | VARCHAR   | 1032402902752871623915905110                                       |                                                              |

## 101. Table: VariableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-05-15 06:31:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 30040333                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xe5fcaff187f210b3f06811d991cfd225614b0cd06b1cae2008f4009e0499fced | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xfb00ac187a8eb5afae4eace434f493eb62672df7                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x9702230a8ea53601f5cd2dc00fdbc13d4df4a8c7                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 6                                                                  |                                                              |
| debtTokenName        | VARCHAR   | Aave Avalanche Variable Debt USDT                                  |                                                              |
| debtTokenSymbol      | VARCHAR   | variableDebtAvaUSDT                                                |                                                              |
| params               | VARCHAR   | 0x30783130                                                         |                                                              |

## 102. Table: VariableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-13 13:17:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13366569                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0b54a6331f15ae204f6b774399ebbed828fd218439be93948d5e8b8ad0460ab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x0a5d485572f17ff99a6ea97d18a07f405befd13d                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x0a5d485572f17ff99a6ea97d18a07f405befd13d                         |                                                              |
| value             | VARCHAR   | 20000000000000000000                                               |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1001292632689630366483971057                                       |                                                              |

## 103. Table: VariableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-19 23:52:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13643654                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcf99b8b8ec479b1f8d58670a5c34cc606fa91cb524fec50516994f54f0085d9a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x1aff351a742297513402635b72e252d05fd3fee1                         |                                                              |
| value             | VARCHAR   | 7000000000000000000                                                |                                                              |
