# aave

## 1. Table: AToken\_v3\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-19 14:22:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 64345964                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x52cebdd28bf388d591c4c022e133edf8ba7f8cd06edc68549bce0d63c2cb7422 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x625e7708f30ca75bfd92586e17077590c60eb4cd                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x3058a0d5e8e1a7b15dbf13eb3d411ee3efea70d9                         |                                                              |
| spender           | VARCHAR   | 0x1408401b2a7e28cb747b3e258d0831fc926bac51                         |                                                              |
| value             | VARCHAR   | 5041216                                                            |                                                              |

## 2. Table: AToken\_v3\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-21 05:02:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33990000                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xff1199848f4a8131b984c6686a9723b895fc7ca781fb9bb28dd74dc83454803a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d80113e533a2c0fe82eabd35f1875dcea89ea97                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x5853ed4f26a3fcea565b3fbc698bb19cdf6deb85                         |                                                              |
| to                | VARCHAR   | 0x17d013c19fe25cf4d911ce85ed5f40fe8880f46f                         |                                                              |
| value             | VARCHAR   | 100031776383226922                                                 |                                                              |
| index             | VARCHAR   | 1000347126377501206845126409                                       |                                                              |

## 3. Table: AToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-01 03:51:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 51694210                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e9d5e66e95274d784fa0c693643bc476751ce8a044b03c19949fc95bb1513f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x82e64f49ed5ec1bc6e43dad4fc8af9bb3a2312ee                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x1408401b2a7e28cb747b3e258d0831fc926bac51                         |                                                              |
| target            | VARCHAR   | 0x1408401b2a7e28cb747b3e258d0831fc926bac51                         |                                                              |
| value             | VARCHAR   | 531386181948448508036                                              |                                                              |
| balanceIncrease   | VARCHAR   | 10737945984994390412                                               |                                                              |
| index             | VARCHAR   | 1041248478667929898990053654                                       |                                                              |

## 4. Table: AToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-03-11 14:16:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 33143853                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x27c89a7c8bfcc9944f05502b577d7e23c7b692bfae79e617adee62de538f7d5a | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x321162cd933e2be498cd2267a90534a804051b11                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| treasury             | VARCHAR   | 0xbe85413851d195fc6341619cd68bfdc26a25b928                         |                                                              |
| incentivesController | VARCHAR   | 0x6a83d738fcbab0c3973234ac7b7b4f7dda2ad248                         |                                                              |
| aTokenDecimals       | VARCHAR   | 8                                                                  |                                                              |
| aTokenName           | VARCHAR   | Aave Fantom WBTC                                                   |                                                              |
| aTokenSymbol         | VARCHAR   | aFanWBTC                                                           |                                                              |
| params               | VARCHAR   | 0x10                                                               |                                                              |

## 5. Table: AToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-27 08:27:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37058400                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e67586942767a3b28b2f04b51312cb04e5d54225abbb1c50571e44ae7b809e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x0e2d3866bf45d8044892a52239c6c897c8ec4934                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x0e2d3866bf45d8044892a52239c6c897c8ec4934                         |                                                              |
| value             | VARCHAR   | 2371                                                               |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1000001556328145558654652431                                       |                                                              |

## 6. Table: AToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-05 09:44:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 50486401                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3af8be0a821fb31aad2b454a313304b8a5198e343e83eb824fc8f58559dd029 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa7a7e108a88e137ff754306a9501e65c980a65e6                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 58562167                                                           |                                                              |

## 7. Table: PoolConfigurator\_event\_ATokenUpgraded\_history

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

## 8. Table: PoolConfigurator\_event\_BorrowCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 14:17:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33143911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51d142f7e8682f779b6af14098e06405575e8e9965d7c24a953a461eea8d526c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xb3654dc3d10ea7645f8319668e8f54d2574fbdc8                         |                                                              |
| oldBorrowCap      | VARCHAR   | 0                                                                  |                                                              |
| newBorrowCap      | VARCHAR   | 0                                                                  |                                                              |

## 9. Table: PoolConfigurator\_event\_BorrowableInIsolationChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 14:19:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33144038                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1835845746d8718624f35a609bebd4d0161b71805b8a7b1b0845aa7101f6effd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x8d11ec38a3eb5e956b052f67da8bdc9bef8abf3e                         |                                                              |
| borrowable        | VARCHAR   | true                                                               |                                                              |

## 10. Table: PoolConfigurator\_event\_BridgeProtocolFeeUpdated\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| oldBridgeProtocolFee | VARCHAR   |                                                              |             |
| newBridgeProtocolFee | VARCHAR   |                                                              |             |

## 11. Table: PoolConfigurator\_event\_CollateralConfigurationChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-03-11 14:17:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 33143911                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x51d142f7e8682f779b6af14098e06405575e8e9965d7c24a953a461eea8d526c | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0xae75a438b2e0cb8bb01ec1e1e376de11d44477cc                         |                                                              |
| ltv                  | VARCHAR   | 2000                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 4500                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 11000                                                              |                                                              |

## 12. Table: PoolConfigurator\_event\_DebtCeilingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 14:19:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33144017                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbfc31e0ae7111cca8b11bbd4005f15ccb604af29d8cf9e2bb17ba4d27a994074 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x049d68029688eabf473097a2fc38ef61633a3c7a                         |                                                              |
| oldDebtCeiling    | VARCHAR   | 0                                                                  |                                                              |
| newDebtCeiling    | VARCHAR   | 5000000                                                            |                                                              |

## 13. Table: PoolConfigurator\_event\_EModeAssetCategoryChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 14:20:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33144084                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac236dd9d64b4917963dd61603fe3ce0a9a3471252400df3178f42eb8bf3a4aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| oldCategoryId     | VARCHAR   | 0                                                                  |                                                              |
| newCategoryId     | VARCHAR   | 1                                                                  |                                                              |

## 14. Table: PoolConfigurator\_event\_EModeCategoryAdded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-04-04 15:58:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 35223674                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xb5857fab1d3a8e7563c1b00d770add989156c7d8a368be7a33a4a38fea452063 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| categoryId           | VARCHAR   | 1                                                                  |                                                              |
| ltv                  | VARCHAR   | 9700                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 9750                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10100                                                              |                                                              |
| oracle               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| label                | VARCHAR   | Stablecoins                                                        |                                                              |

## 15. Table: PoolConfigurator\_event\_FlashloanPremiumToProtocolUpdated\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2022-03-11 13:59:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 33142726                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0x6943ef4dd2e09193121957756522d0d8741264d65fa6f6b4b6fae4314e5aa728 | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumToProtocol | VARCHAR   | 0                                                                  |                                                              |
| newFlashloanPremiumToProtocol | VARCHAR   | 4                                                                  |                                                              |

## 16. Table: PoolConfigurator\_event\_FlashloanPremiumTotalUpdated\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2022-03-11 13:59:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 33142714                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xb5f47f68a146272ef2d9177892c66064573fcefa015ce1a38b9678dc3b445910 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumTotal | VARCHAR   | 9                                                                  |                                                              |
| newFlashloanPremiumTotal | VARCHAR   | 5                                                                  |                                                              |

## 17. Table: PoolConfigurator\_event\_LiquidationProtocolFeeChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 14:21:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33144179                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3dc1f47ef69ac13623a61d38a3d9f054e84bb43bdb89f4318b8cbca44932d6a4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x1e4f97b9f9f913c46f1632781732927b9019c68b                         |                                                              |
| oldFee            | VARCHAR   | 0                                                                  |                                                              |
| newFee            | VARCHAR   | 1000                                                               |                                                              |

## 18. Table: PoolConfigurator\_event\_ReserveActive\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| active            | VARCHAR   |                                                              |             |

## 19. Table: PoolConfigurator\_event\_ReserveBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 14:17:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33143911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51d142f7e8682f779b6af14098e06405575e8e9965d7c24a953a461eea8d526c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x21be370d5312f44cb42ce377bc9b8a0cef1a4c83                         |                                                              |
| enabled           | VARCHAR   | true                                                               |                                                              |

## 20. Table: PoolConfigurator\_event\_ReserveDropped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |

## 21. Table: PoolConfigurator\_event\_ReserveFactorChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 14:17:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33143911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51d142f7e8682f779b6af14098e06405575e8e9965d7c24a953a461eea8d526c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 91                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x6a07a792ab2965c72a5b8088d3a069a7ac3a993b                         |                                                              |
| oldReserveFactor  | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactor  | VARCHAR   | 0                                                                  |                                                              |

## 22. Table: PoolConfigurator\_event\_ReserveFrozen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-16 10:12:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 47043683                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5696e74a649ae3f777f3472f064fa163754eb1592e77ca2a0bae44849f0dda5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x6a07a792ab2965c72a5b8088d3a069a7ac3a993b                         |                                                              |
| frozen            | VARCHAR   | true                                                               |                                                              |

## 23. Table: PoolConfigurator\_event\_ReserveInitialized\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2022-03-11 14:15:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 33143826                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0xf8a501012d33edbdd41a34cd1c299e44e7b0f49d77388384f3b0d0fb4d925337 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| aToken                      | VARCHAR   | 0x625e7708f30ca75bfd92586e17077590c60eb4cd                         |                                                              |
| stableDebtToken             | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         |                                                              |
| variableDebtToken           | VARCHAR   | 0xfccf3cabbe80101232d343252614b6a3ee81c989                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0xee1bac9355eaafcd1b68d272d640d870bc9b4b5c                         |                                                              |

## 24. Table: PoolConfigurator\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-22 18:59:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34129291                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e19f13fb648d09e6184c0f6fe8ec1a765d5d7880ee5dde0b5a11580210377a4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| oldStrategy       | VARCHAR   | 0x41b66b4b6b4c9dab039d96528d1b88f7baf8c5a4                         |                                                              |
| newStrategy       | VARCHAR   | 0xf4a0039f2d4a2ead5216abb6ae4c4c3aa2db9b82                         |                                                              |

## 25. Table: PoolConfigurator\_event\_ReservePaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-14 19:20:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33425335                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa21c4d4ca0704f06b6b358e607ed546a79ad57a8be9a1bfe966634d68ae54497 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x321162cd933e2be498cd2267a90534a804051b11                         |                                                              |
| paused            | VARCHAR   | true                                                               |                                                              |

## 26. Table: PoolConfigurator\_event\_ReserveStableRateBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-01 08:38:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34947424                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e7dc6d36dd48610968f755795d419ab852dbe2d2a31cb9760179013bf0e53f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x74b23882a30290451a17c44f4f05243b6b58c76d                         |                                                              |
| enabled           | VARCHAR   | false                                                              |                                                              |

## 27. Table: PoolConfigurator\_event\_SiloedBorrowingChanged\_history

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

## 28. Table: PoolConfigurator\_event\_StableDebtTokenUpgraded\_history

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

## 29. Table: PoolConfigurator\_event\_SupplyCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 14:17:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33143911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51d142f7e8682f779b6af14098e06405575e8e9965d7c24a953a461eea8d526c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x321162cd933e2be498cd2267a90534a804051b11                         |                                                              |
| oldSupplyCap      | VARCHAR   | 0                                                                  |                                                              |
| newSupplyCap      | VARCHAR   | 0                                                                  |                                                              |

## 30. Table: PoolConfigurator\_event\_UnbackedMintCapChanged\_history

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

## 31. Table: PoolConfigurator\_event\_VariableDebtTokenUpgraded\_history

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

## 32. Table: Pool\_v3\_event\_BackUnbacked\_history

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

## 33. Table: Pool\_v3\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-03 21:06:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41945191                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x794e36dae1b4d549a7626725631a3871894d44b63c65bc53bcbe3826173be91f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| user              | VARCHAR   | 0x3e7df87720c9a7dbc14a54ba5b04900e16942f5c                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x3e7df87720c9a7dbc14a54ba5b04900e16942f5c                         |                                                              |
| amount            | VARCHAR   | 9000000                                                            |                                                              |
| interestRateMode  | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 10284458936569301626412711                                         |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 34. Table: Pool\_v3\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 15:05:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 66451710                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24e288d03f0f4e63fb3653909e04004efcce6a116805ac9c58e4d31a58785839 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x454701b026df196457895054dcd4f3be12cefdbc                         |                                                              |
| initiator         | VARCHAR   | 0x454701b026df196457895054dcd4f3be12cefdbc                         |                                                              |
| asset             | VARCHAR   | 0x21be370d5312f44cb42ce377bc9b8a0cef1a4c83                         |                                                              |
| amount            | VARCHAR   | 597487870819352940375                                              |                                                              |
| interestRateMode  | VARCHAR   | 0                                                                  |                                                              |
| premium           | VARCHAR   | 298743935409676470                                                 |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 35. Table: Pool\_v3\_event\_IsolationModeTotalDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-28 02:45:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41506325                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85f9c68a3e22c9bf9c40863aa1225710d178820419560cae6e100434814b40c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x049d68029688eabf473097a2fc38ef61633a3c7a                         |                                                              |
| totalDebt         | VARCHAR   | 1525714                                                            |                                                              |

## 36. Table: Pool\_v3\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-07-21 09:25:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 66140580                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0xec3abc10479f5f7446a077fce697635fe52495ccf1e338fd5e7c6e368be115ed | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0x1e4f97b9f9f913c46f1632781732927b9019c68b                         |                                                              |
| debtAsset                  | VARCHAR   | 0x8d11ec38a3eb5e956b052f67da8bdc9bef8abf3e                         |                                                              |
| user                       | VARCHAR   | 0x9e6449f245cd587aa081f3357733e35982279f50                         |                                                              |
| debtToCover                | VARCHAR   | 145805780004550715                                                 |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 192508671811332982                                                 |                                                              |
| liquidator                 | VARCHAR   | 0x2690fc60d311ff0a94d1fab74e659316ae4b6cf8                         |                                                              |
| receiveAToken              | VARCHAR   | false                                                              |                                                              |

## 37. Table: Pool\_v3\_event\_MintUnbacked\_history

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

## 38. Table: Pool\_v3\_event\_MintedToTreasury\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| amountMinted      | VARCHAR   |                                                              |             |

## 39. Table: Pool\_v3\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reserve           | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |

## 40. Table: Pool\_v3\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-17 17:50:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33682381                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd765da7aff632993dfe88692dd1f073f98bd58cacdc66e0407610ef26a081145 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| user              | VARCHAR   | 0xbff51fbc1e25d644a8a2947b0ca4e281448a761c                         |                                                              |
| repayer           | VARCHAR   | 0xbff51fbc1e25d644a8a2947b0ca4e281448a761c                         |                                                              |
| amount            | VARCHAR   | 350000387                                                          |                                                              |
| useATokens        | VARCHAR   | false                                                              |                                                              |

## 41. Table: Pool\_v3\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-04-25 01:09:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 36894851                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xb77240a2f9ae29eb24d9e1dffe00a52f6ad94734a79816fe4608d3ee53830fb4 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x321162cd933e2be498cd2267a90534a804051b11                         |                                                              |
| liquidityRate       | VARCHAR   | 130504512944528525433564                                           |                                                              |
| stableBorrowRate    | VARCHAR   | 90000000000000000000000000                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 5037447520023573496878162                                          |                                                              |
| liquidityIndex      | VARCHAR   | 1000001440044495961980107112                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1000057700322694350739739867                                       |                                                              |

## 42. Table: Pool\_v3\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-06 01:42:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44310524                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4211964c0c722b8edae8457b2c692ad5b73ef4eba2d7ffe271c3104d71d55b00 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| user              | VARCHAR   | 0x1408401b2a7e28cb747b3e258d0831fc926bac51                         |                                                              |

## 43. Table: Pool\_v3\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-18 03:38:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36345067                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8f019ec388700b658319ff2bf0b93f6fbcb7d8a760f9c3e5984c3d1bfca90ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| user              | VARCHAR   | 0x7ac810aadc2e6dbcc61a9bd50935c7ccdaeaa364                         |                                                              |

## 44. Table: Pool\_v3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-17 06:43:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40699090                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbf5d15e8bcc54b167ac86a0d9006a705962fc27147e8c954e8d6c6b8eae37bcf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| user              | VARCHAR   | 0x0bd27fac898a59680b9dc92bb7378df610825e8d                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x0bd27fac898a59680b9dc92bb7378df610825e8d                         |                                                              |
| amount            | VARCHAR   | 7000000000                                                         |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 45. Table: Pool\_v3\_event\_SwapBorrowRateMode\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-28 19:24:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34642970                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xddf66249906740e167e5ea5cc275ab0c2d77df9f67a6ed7b059d50e2bc03f1b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| user              | VARCHAR   | 0x559c5f3c50a48aa68824830fa176870cc2d7f0d3                         |                                                              |
| interestRateMode  | VARCHAR   | 2                                                                  |                                                              |

## 46. Table: Pool\_v3\_event\_UserEModeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-10 05:24:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40187866                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3788936d6bba74165cb9e6ac5fa43864690e43903da9484129ae215a72deecfd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x59fa204f4d7a117845f0215079c31125d1b8236f                         |                                                              |
| categoryId        | VARCHAR   | 0                                                                  |                                                              |

## 47. Table: Pool\_v3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-06 03:31:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39887189                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0924a965d4a116f5689381493ef6d957751cce44a0d86e111d9f8cd5088cd688 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| user              | VARCHAR   | 0x1f2066839072a339e3f2e15b4c445ab494f34e9e                         |                                                              |
| to                | VARCHAR   | 0x1f2066839072a339e3f2e15b4c445ab494f34e9e                         |                                                              |
| amount            | VARCHAR   | 500000000                                                          |                                                              |

## 48. Table: StableDebtToken\_v3\_event\_Approval\_history

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

## 49. Table: StableDebtToken\_v3\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| fromUser          | VARCHAR   |                                                              |             |
| toUser            | VARCHAR   |                                                              |             |
| asset             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 50. Table: StableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 07:25:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38349916                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6902cb6d93a63bee4dcacae2cde77a92aac59a80c22de34577a65d44d95b0e3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa11cba2199d349c35f4c4ef6a4760406c69f9f79                         |                                                              |
| amount            | VARCHAR   | 16449692788                                                        |                                                              |
| currentBalance    | VARCHAR   | 25787031190                                                        |                                                              |
| balanceIncrease   | VARCHAR   | 160090092                                                          |                                                              |
| avgStableRate     | VARCHAR   | 55225228824329785391685455                                         |                                                              |
| newTotalSupply    | VARCHAR   | 165450165737                                                       |                                                              |

## 51. Table: StableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-03-11 14:15:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 33143826                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xf8a501012d33edbdd41a34cd1c299e44e7b0f49d77388384f3b0d0fb4d925337 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x04068da6c83afcfa0e13ba15a6696662335d5b75                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x6a83d738fcbab0c3973234ac7b7b4f7dda2ad248                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 6                                                                  |                                                              |
| debtTokenName        | VARCHAR   | Aave Fantom Stable Debt USDC                                       |                                                              |
| debtTokenSymbol      | VARCHAR   | stableDebtFanUSDC                                                  |                                                              |
| params               | VARCHAR   | 0x10                                                               |                                                              |

## 52. Table: StableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-14 08:25:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38210565                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf85a5b61cf811a38c635ff6be0305ed17daf58f08ef636ed5f19eeb9a222809d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1a0cdc1a4bdd49986205f18ff7297e21f048993f                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x1a0cdc1a4bdd49986205f18ff7297e21f048993f                         |                                                              |
| amount            | VARCHAR   | 2600000000                                                         |                                                              |
| currentBalance    | VARCHAR   | 0                                                                  |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| newRate           | VARCHAR   | 52345989677747982692307692                                         |                                                              |
| avgStableRate     | VARCHAR   | 55230678312895007055274442                                         |                                                              |
| newTotalSupply    | VARCHAR   | 186591728751                                                       |                                                              |

## 53. Table: StableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-10 16:51:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 53541260                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x139c0cc41ba399d63d0b34da9421a36638d5304e34e7162829757234b99cf45d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0dc23021bee290609fe97060aa3caed6411bce60                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 12200419                                                           |                                                              |

## 54. Table: VariableDebtToken\_v3\_event\_Approval\_history

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

## 55. Table: VariableDebtToken\_v3\_event\_BorrowAllowanceDelegated\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-26 09:53:22+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34437843                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ab28101c48ed993f1df553ea5041e645d339b40f0481123709af70f81ef6ae1             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a1c3ad6ed28a636ee1751c69071f6be75deb8b8                                     | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x32277a348d42105557a8a3d9176713a9bf2483ce                                     |                                                              |
| toUser            | VARCHAR   | 0x17d013c19fe25cf4d911ce85ed5f40fe8880f46f                                     |                                                              |
| asset             | VARCHAR   | 0x21be370d5312f44cb42ce377bc9b8a0cef1a4c83                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564024587584007913129639935 |                                                              |

## 56. Table: VariableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-13 21:13:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 59843479                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x189f2ac6da6f5b45a3ccf279b15f5759bb1c99750fff9a70483b8c8f79ee536f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a1c3ad6ed28a636ee1751c69071f6be75deb8b8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xf7063913ae1797e2a2b8fb7bf633386c45362463                         |                                                              |
| target            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 1030512005884080891917                                             |                                                              |
| balanceIncrease   | VARCHAR   | 617049327538534681                                                 |                                                              |
| index             | VARCHAR   | 1078991657783942462161414134                                       |                                                              |

## 57. Table: VariableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-03-11 14:16:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 33143853                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x27c89a7c8bfcc9944f05502b577d7e23c7b692bfae79e617adee62de538f7d5a | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x92b42c66840c7ad907b4bf74879ff3ef7c529473                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x321162cd933e2be498cd2267a90534a804051b11                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x6a83d738fcbab0c3973234ac7b7b4f7dda2ad248                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 8                                                                  |                                                              |
| debtTokenName        | VARCHAR   | Aave Fantom Variable Debt WBTC                                     |                                                              |
| debtTokenSymbol      | VARCHAR   | variableDebtFanWBTC                                                |                                                              |
| params               | VARCHAR   | 0x10                                                               |                                                              |

## 58. Table: VariableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-02 10:58:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35038837                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf04de9643c09a5766fe1add07e639dfe17ed7d67f3e6bb3db98ea96410c0080a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x0aa2ac7f8e89aae67ab58583b1a95676db4e73f3                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x0aa2ac7f8e89aae67ab58583b1a95676db4e73f3                         |                                                              |
| value             | VARCHAR   | 530000000000000000                                                 |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1000039023873443934665279658                                       |                                                              |

## 59. Table: VariableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-13 18:11:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35974265                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x395fbc3a6dffd5a21eff6c599e7d0c77fc5efdef03b88289ee0c71a89bd09977 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0a3c0977912cdc485adb3731f0d6011a7af66896                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 18000000000000000                                                  |                                                              |
