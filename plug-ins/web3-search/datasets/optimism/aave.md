# aave

## 1. Table: AToken\_v3\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 02:25:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107196967                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ab9c0ee5739fa99f63030a38878ef55ebea1ee7dfdd2e6c38dbea651acc0599 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x625e7708f30ca75bfd92586e17077590c60eb4cd                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x6142e71e92a514e9733bbd199e83b0750a0f77bc                         |                                                              |
| spender           | VARCHAR   | 0x0000000000000000000000000000000000000001                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: AToken\_v3\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-05 09:25:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5351586                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc50e32bfca4a19e5c80bcec738f54bfe145d98d66ee9b61c344dad9393b8e410 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe50fa9b3c56ffb159cb0fca61f5c9d750e8128c8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0e38a4b9b58abd2f4c9b2d5486ba047a47606781                         |                                                              |
| to                | VARCHAR   | 0x86b4d2636ec473ac4a5dd83fc2beda98845249a7                         |                                                              |
| value             | VARCHAR   | 1400013018196173398                                                |                                                              |
| index             | VARCHAR   | 1000022789587035251149743212                                       |                                                              |

## 3. Table: AToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-28 19:15:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4963363                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7fee7ded3ac1f2eed00b55579257ddc98d664e26a68b4940835453ad396b38b2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x625e7708f30ca75bfd92586e17077590c60eb4cd                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x9e864c0e3b49ce521ffaadcc6f99bdeb8cdadc26                         |                                                              |
| target            | VARCHAR   | 0x9e864c0e3b49ce521ffaadcc6f99bdeb8cdadc26                         |                                                              |
| value             | VARCHAR   | 249897867                                                          |                                                              |
| balanceIncrease   | VARCHAR   | 102133                                                             |                                                              |
| index             | VARCHAR   | 1000561833790061872001232645                                       |                                                              |

## 4. Table: AToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-07-20 12:26:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 107128612                                                          | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x1d8b04166d66cedce492cbe38185b6ddd76f7bd059bfe48cae20c137acea0111 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x724dc807b04555b71ed48a6896b6f41593b8c637                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x9bcef72be871e61ed4fbbc7630889bee758eb81d                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| treasury             | VARCHAR   | 0xb2289e329d2f85f1ed31adbb30ea345278f21bcf                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| aTokenDecimals       | VARCHAR   | 18                                                                 |                                                              |
| aTokenName           | VARCHAR   | Aave Optimism rETH                                                 |                                                              |
| aTokenSymbol         | VARCHAR   | aOptrETH                                                           |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 5. Table: AToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 14:51:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 97988892                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2ea5770593c70cf8c320ee24f3a86cacb8753b2e5dfa75e74617e2fd153583d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x82e64f49ed5ec1bc6e43dad4fc8af9bb3a2312ee                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x69dd38645f7457be13571a847ffd905f9acbaf6d                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x95e2b35509b2d6d6384f315cccb9e408e4289aff                         |                                                              |
| value             | VARCHAR   | 1714462013887                                                      |                                                              |
| balanceIncrease   | VARCHAR   | 1714462013887                                                      |                                                              |
| index             | VARCHAR   | 1017519900787416569211863181                                       |                                                              |

## 6. Table: AToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 20:27:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107575024                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8d074f2f60836be416452c48143665ce4a5ff300fc7fd2492f0306cb39b3b431 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xdb7f7eb6776ea3848e50bb60be6ff17b7e893ed3                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 460579                                                             |                                                              |

## 7. Table: PoolConfigurator\_event\_ATokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 22:56:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 105549108                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5814781778e7cd375e8a443542c0da29f1dce538b7f5e7aa7ef7cd952d4b6aab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xdfa46478f9e5ea86d57387849598dbfb2e964b02                         |                                                              |
| proxy             | VARCHAR   | 0x8ffdf2de812095b1d19cb146e4c004587c0a0692                         |                                                              |
| implementation    | VARCHAR   | 0xbcb167bdcf14a8f791d6f4a6edd964aed2f8813b                         |                                                              |

## 8. Table: PoolConfigurator\_event\_BorrowCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 07:26:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107681200                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x589d673b31e46ea94f0c1c3b88224a23e77bb26cfc3d23d3b8f8eb4625abea15 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xdfa46478f9e5ea86d57387849598dbfb2e964b02                         |                                                              |
| oldBorrowCap      | VARCHAR   | 2500000                                                            |                                                              |
| newBorrowCap      | VARCHAR   | 525000                                                             |                                                              |

## 9. Table: PoolConfigurator\_event\_BorrowableInIsolationChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-05 17:22:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 86532283                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x906058ebfd5f8c0ea1b255e8eb441b61b441bb463eabcc544573ab7fcf66f266 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc40f949f8a4e094d1b49a23ea9241d289b7b2819                         |                                                              |
| borrowable        | VARCHAR   | false                                                              |                                                              |

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
| block\_timestamp     | TIMESTAMP | 2023-04-25 17:35:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 94193883                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xb1b95b09bad8a17d0d51fa1d36a29ed7739ce86d8e4ce7fae91cf64237f6ebc3 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0xda10009cbd5d07dd0cecc66161fc93d7c9000da1                         |                                                              |
| ltv                  | VARCHAR   | 7800                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 8300                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10500                                                              |                                                              |

## 12. Table: PoolConfigurator\_event\_DebtCeilingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 07:26:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107681200                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x589d673b31e46ea94f0c1c3b88224a23e77bb26cfc3d23d3b8f8eb4625abea15 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xdfa46478f9e5ea86d57387849598dbfb2e964b02                         |                                                              |
| oldDebtCeiling    | VARCHAR   | 190000000                                                          |                                                              |
| newDebtCeiling    | VARCHAR   | 13000000                                                           |                                                              |

## 13. Table: PoolConfigurator\_event\_EModeAssetCategoryChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 09:37:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 98429188                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x50b7a5757a9501e85ee6c0c6fa46b5462f64b713c7b0f4dd49a432c11efc4e10 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xdfa46478f9e5ea86d57387849598dbfb2e964b02                         |                                                              |
| oldCategoryId     | VARCHAR   | 0                                                                  |                                                              |
| newCategoryId     | VARCHAR   | 0                                                                  |                                                              |

## 14. Table: PoolConfigurator\_event\_EModeCategoryAdded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-03-11 13:51:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 4365830                                                            | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x98ecabe864a921e5ddfe671346b6333c83cebb258d68f4d8e9b63e9949513afe | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| categoryId           | VARCHAR   | 1                                                                  |                                                              |
| ltv                  | VARCHAR   | 9700                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 9750                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10200                                                              |                                                              |
| oracle               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| label                | VARCHAR   | Stablecoins                                                        |                                                              |

## 15. Table: PoolConfigurator\_event\_FlashloanPremiumToProtocolUpdated\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2022-03-11 13:48:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 4365720                                                            | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0xcaf4e2c191aae63dda76e0f02be5a5092e91cc666c277c6e96726b7fc22ba73b | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumToProtocol | VARCHAR   | 0                                                                  |                                                              |
| newFlashloanPremiumToProtocol | VARCHAR   | 4                                                                  |                                                              |

## 16. Table: PoolConfigurator\_event\_FlashloanPremiumTotalUpdated\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2023-05-10 10:23:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 97221914                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xde62532430b5744ad8c633f462cbe12b7ea4173cf0a7e741669c914b9607bdaf | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumTotal | VARCHAR   | 9                                                                  |                                                              |
| newFlashloanPremiumTotal | VARCHAR   | 5                                                                  |                                                              |

## 17. Table: PoolConfigurator\_event\_LiquidationProtocolFeeChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 13:51:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4365841                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaa5b4d7d8e28fdd25a02251b2f4bcc99268caa369b85d0a84918f1a46eab046b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xda10009cbd5d07dd0cecc66161fc93d7c9000da1                         |                                                              |
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
| block\_timestamp  | TIMESTAMP | 2023-07-20 12:26:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107128612                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d8b04166d66cedce492cbe38185b6ddd76f7bd059bfe48cae20c137acea0111 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x9bcef72be871e61ed4fbbc7630889bee758eb81d                         |                                                              |
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
| block\_timestamp  | TIMESTAMP | 2023-04-05 17:22:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 86532283                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x906058ebfd5f8c0ea1b255e8eb441b61b441bb463eabcc544573ab7fcf66f266 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc40f949f8a4e094d1b49a23ea9241d289b7b2819                         |                                                              |
| oldReserveFactor  | VARCHAR   | 0                                                                  |                                                              |
| newReserveFactor  | VARCHAR   | 1000                                                               |                                                              |

## 22. Table: PoolConfigurator\_event\_ReserveFrozen\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| asset             | VARCHAR   |                                                              |             |
| frozen            | VARCHAR   |                                                              |             |

## 23. Table: PoolConfigurator\_event\_ReserveInitialized\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2023-07-20 12:26:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 107128612                                                          | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x1d8b04166d66cedce492cbe38185b6ddd76f7bd059bfe48cae20c137acea0111 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0x9bcef72be871e61ed4fbbc7630889bee758eb81d                         |                                                              |
| aToken                      | VARCHAR   | 0x724dc807b04555b71ed48a6896b6f41593b8c637                         |                                                              |
| stableDebtToken             | VARCHAR   | 0xdc1fad70953bb3918592b6fcc374fe05f5811b6a                         |                                                              |
| variableDebtToken           | VARCHAR   | 0xf611aeb5013fd2c0511c9cd55c7dc5c1140741a6                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0x3b57b081da6af5e2759a57bd3211932cb6176997                         |                                                              |

## 24. Table: PoolConfigurator\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-24 19:31:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 101164106                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce58ab10b8f434082222b8eed425f8fef8b69c4b14dabb2f955aca9e7692060b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x68f180fcce6836688e9084f035309e29bf0a2095                         |                                                              |
| oldStrategy       | VARCHAR   | 0xee1bac9355eaafcd1b68d272d640d870bc9b4b5c                         |                                                              |
| newStrategy       | VARCHAR   | 0x04dabc3c1c052ab94aa2ca80140f2b978d2f6e17                         |                                                              |

## 25. Table: PoolConfigurator\_event\_ReservePaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 06:48:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 105068765                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc4d1b48adcb8904d03c319204b4a56bedd4fab676a028f5cca1c6939dd8a1297 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xdfa46478f9e5ea86d57387849598dbfb2e964b02                         |                                                              |
| paused            | VARCHAR   | true                                                               |                                                              |

## 26. Table: PoolConfigurator\_event\_ReserveStableRateBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 12:26:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107128612                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d8b04166d66cedce492cbe38185b6ddd76f7bd059bfe48cae20c137acea0111 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x9bcef72be871e61ed4fbbc7630889bee758eb81d                         |                                                              |
| enabled           | VARCHAR   | false                                                              |                                                              |

## 27. Table: PoolConfigurator\_event\_SiloedBorrowingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-05 17:22:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 86532283                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x906058ebfd5f8c0ea1b255e8eb441b61b441bb463eabcc544573ab7fcf66f266 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc40f949f8a4e094d1b49a23ea9241d289b7b2819                         |                                                              |
| oldState          | VARCHAR   | false                                                              |                                                              |
| newState          | VARCHAR   | false                                                              |                                                              |

## 28. Table: PoolConfigurator\_event\_StableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-10 10:23:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 97221914                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xde62532430b5744ad8c633f462cbe12b7ea4173cf0a7e741669c914b9607bdaf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 85                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x8c6f28f2f1a3c87f0f938b96d27520d9751ec8d9                         |                                                              |
| proxy             | VARCHAR   | 0xf15f26710c827dde8acba678682f3ce24f2fb56e                         |                                                              |
| implementation    | VARCHAR   | 0x6b4e260b765b3ca1514e618c0215a6b7839ff93e                         |                                                              |

## 29. Table: PoolConfigurator\_event\_SupplyCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-17 01:17:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 68225542                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1bde745a6f116c1d854975fc91c695570a081fac0eaaac02677e9932513819e6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x4200000000000000000000000000000000000042                         |                                                              |
| oldSupplyCap      | VARCHAR   | 0                                                                  |                                                              |
| newSupplyCap      | VARCHAR   | 20000000                                                           |                                                              |

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

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-10 10:23:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 97221914                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xde62532430b5744ad8c633f462cbe12b7ea4173cf0a7e741669c914b9607bdaf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x350a791bfc2c21f9ed5d10980dad2e2638ffa7f6                         |                                                              |
| proxy             | VARCHAR   | 0x953a573793604af8d41f306feb8274190db4ae0e                         |                                                              |
| implementation    | VARCHAR   | 0x04a8d477ee202adce1682f5902e1160455205b12                         |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2022-11-12 14:08:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37500455                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc98c31a5b03a9f20466ee98c57322ae4d355270dbf4c925363106b77818e6609 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x94b008aa00579c1307b0ef2c499ad98a8ce58e58                         |                                                              |
| user              | VARCHAR   | 0xe3a5a349b9434d2b5a6ecfd9af6f5bc22950c999                         |                                                              |
| onBehalfOf        | VARCHAR   | 0xe3a5a349b9434d2b5a6ecfd9af6f5bc22950c999                         |                                                              |
| amount            | VARCHAR   | 100                                                                |                                                              |
| interestRateMode  | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 34303270283796652134887740                                         |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 34. Table: Pool\_v3\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-30 09:18:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13522914                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x41f186adcf08dfd9aa48cdf2b2fb08ec2d0aee236b177a1d4bbb2f9f08e69e62 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x352d4a1622f2dc34c738f542934372855f219f05                         |                                                              |
| initiator         | VARCHAR   | 0x352d4a1622f2dc34c738f542934372855f219f05                         |                                                              |
| asset             | VARCHAR   | 0x4200000000000000000000000000000000000006                         |                                                              |
| amount            | VARCHAR   | 242626781597890867                                                 |                                                              |
| interestRateMode  | VARCHAR   | 0                                                                  |                                                              |
| premium           | VARCHAR   | 121313390798945                                                    |                                                              |
| referralCode      | VARCHAR   | 64                                                                 |                                                              |

## 35. Table: Pool\_v3\_event\_IsolationModeTotalDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 16:25:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28542240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b88d9894fe83e6c4a10dfcbd8b17c23b6ff70445dec61307174b920e398b534 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x94b008aa00579c1307b0ef2c499ad98a8ce58e58                         |                                                              |
| totalDebt         | VARCHAR   | 499999515                                                          |                                                              |

## 36. Table: Pool\_v3\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2022-06-30 06:28:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 13511311                                                           | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0xf359da21404b65ecb9b13af6457ac8fe02c58ec182892b31a1c6b0ba50e4e7c2 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0x68f180fcce6836688e9084f035309e29bf0a2095                         |                                                              |
| debtAsset                  | VARCHAR   | 0xda10009cbd5d07dd0cecc66161fc93d7c9000da1                         |                                                              |
| user                       | VARCHAR   | 0xdceb0bb3311342e3ce9e49f57affce9deac40ba1                         |                                                              |
| debtToCover                | VARCHAR   | 25092155580850122752                                               |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 137605                                                             |                                                              |
| liquidator                 | VARCHAR   | 0x445db0d4b2ca3e24804b6bf24f0b2d3c1e4c667e                         |                                                              |
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

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 19:00:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31227652                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ee7d08757bd13b2d73add88e239f0210463e878cf2ca663861e89b4081dd662 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x7f5c764cbc14f9669b88837ca1490cca17c31607                         |                                                              |
| amountMinted      | VARCHAR   | 15878066590                                                        |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2023-08-04 04:52:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107762998                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6fa4ad55a44cb2f4e1b80ba19ab88a2dc6d4b06bef775be614d34735bd2a64fb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x8c6f28f2f1a3c87f0f938b96d27520d9751ec8d9                         |                                                              |
| user              | VARCHAR   | 0x00b6cc3828bfb458da092675c3a51aa60c7ca194                         |                                                              |
| repayer           | VARCHAR   | 0x00b6cc3828bfb458da092675c3a51aa60c7ca194                         |                                                              |
| amount            | VARCHAR   | 176097075066870742174                                              |                                                              |
| useATokens        | VARCHAR   | false                                                              |                                                              |

## 41. Table: Pool\_v3\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-02-28 22:04:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 77834979                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xe1c2b1b4a35463cce0c9e9f634f5390d7b05eb63a6eea368a759fcb9c219dc91 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x76fb31fb4af56892a25e32cfc43de717950c9278                         |                                                              |
| liquidityRate       | VARCHAR   | 0                                                                  |                                                              |
| stableBorrowRate    | VARCHAR   | 90000000000000000000000000                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 0                                                                  |                                                              |
| liquidityIndex      | VARCHAR   | 1000003319998637070259511189                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1000000000000000000000000000                                       |                                                              |

## 42. Table: Pool\_v3\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 22:00:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7911999                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x782a8a9da5f0e2fc67e0e6e87900b4c01b25fa733a319776b2683d71b9c70e14 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x350a791bfc2c21f9ed5d10980dad2e2638ffa7f6                         |                                                              |
| user              | VARCHAR   | 0x912755d737df814b10f7ad7ff7b5e351b6cb3ff2                         |                                                              |

## 43. Table: Pool\_v3\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 22:40:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107190240                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf72fbdda76c07793a9dbd04a0a8f0ad8e4bf0663ded2b0f557c61c90059940ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x1f32b1c2345538c0c6f582fcb022739c4a194ebb                         |                                                              |
| user              | VARCHAR   | 0x830c5a67a0c95d69da5fb7801ac1773c6fb53857                         |                                                              |

## 44. Table: Pool\_v3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-07 13:29:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28054081                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5408902d2825200abb7f1c776fe8fd1f90fc075f481b3e47625053b354237e57 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x94b008aa00579c1307b0ef2c499ad98a8ce58e58                         |                                                              |
| user              | VARCHAR   | 0xbb269cc63fdac8c03c5c6e1e9a0553d300727ad1                         |                                                              |
| onBehalfOf        | VARCHAR   | 0xbb269cc63fdac8c03c5c6e1e9a0553d300727ad1                         |                                                              |
| amount            | VARCHAR   | 1679045                                                            |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 45. Table: Pool\_v3\_event\_SwapBorrowRateMode\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-19 17:49:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12374088                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9474469f847e6a1160b2193dea3a178feb3ba54394adec04fcfbedf4480516a5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x7f5c764cbc14f9669b88837ca1490cca17c31607                         |                                                              |
| user              | VARCHAR   | 0xd6ab15700f2fc1b31f293a32c502bde51cc532a3                         |                                                              |
| interestRateMode  | VARCHAR   | 2                                                                  |                                                              |

## 46. Table: Pool\_v3\_event\_UserEModeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-01 22:39:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 78047025                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f3ac9873aa7610f0ee3a9b0aa287db469df2e43d1db1a720ef50102bd9e91d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x545f0207c1aa9083e4b38a0e7c69b6d5979071e3                         |                                                              |
| categoryId        | VARCHAR   | 0                                                                  |                                                              |

## 47. Table: Pool\_v3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 06:21:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 77692606                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90865af4b924b7b7d23891d2da1824dca92478868b7570198d5fd69f466b25fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x1f32b1c2345538c0c6f582fcb022739c4a194ebb                         |                                                              |
| user              | VARCHAR   | 0x7dd2325f5cbb1a6e4951fdf0d839eb9b89c502b8                         |                                                              |
| to                | VARCHAR   | 0x92b0525b86badcdfd9543f7eb46e85187c0701ff                         |                                                              |
| amount            | VARCHAR   | 141306494573397734                                                 |                                                              |

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

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-24 17:56:47+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107311315                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82099b05755d8255ffea8ebfe8819ad30f1f6d647be4d6de679d8f0fd405d567             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd8ad37849950903571df17049516a5cd4cbe55f6                                     | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0xd3ab4fa211a0d4f930b68f4d481d556490d6f346                                     |                                                              |
| toUser            | VARCHAR   | 0xc39b8cd0da01d935ea61248a9bbb54b4c5ae0b61                                     |                                                              |
| asset             | VARCHAR   | 0x4200000000000000000000000000000000000006                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639934 |                                                              |

## 50. Table: StableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-18 04:42:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 81815924                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf28a094d2da9514d233caa578ee0f240a0e347e19f3730f07a9c1dd5c20d2fba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70effc565db6eef7b927610155602d31b670e802                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x04f2c60d181d3255968a86a0fc76c524265e200c                         |                                                              |
| amount            | VARCHAR   | 200000000                                                          |                                                              |
| currentBalance    | VARCHAR   | 201358095                                                          |                                                              |
| balanceIncrease   | VARCHAR   | 1358095                                                            |                                                              |
| avgStableRate     | VARCHAR   | 54290669951360813808466657                                         |                                                              |
| newTotalSupply    | VARCHAR   | 31592345685                                                        |                                                              |

## 51. Table: StableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-13 22:56:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 105549108                                                          | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x5814781778e7cd375e8a443542c0da29f1dce538b7f5e7aa7ef7cd952d4b6aab | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xa5e408678469d23efdb7694b1b0a85bb0669e8bd                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0xdfa46478f9e5ea86d57387849598dbfb2e964b02                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 18                                                                 |                                                              |
| debtTokenName        | VARCHAR   | Aave Optimism Stable Debt MAI                                      |                                                              |
| debtTokenSymbol      | VARCHAR   | stableDebtOptMAI                                                   |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 52. Table: StableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 09:44:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 89406158                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1067e9ba34d6562d938c26d63d51b206d43bab3a60ad03dd04c8b17c061c67b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xe908c2d5613d24d49e376f19715c795db8e04f81                         |                                                              |
| onBehalfOf        | VARCHAR   | 0xe908c2d5613d24d49e376f19715c795db8e04f81                         |                                                              |
| amount            | VARCHAR   | 1000000                                                            |                                                              |
| currentBalance    | VARCHAR   | 0                                                                  |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| newRate           | VARCHAR   | 52962302198867000000000000                                         |                                                              |
| avgStableRate     | VARCHAR   | 52706308595195738491392961                                         |                                                              |
| newTotalSupply    | VARCHAR   | 43287947300                                                        |                                                              |

## 53. Table: StableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 01:43:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 106720520                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09798f46ced72e567315b6676bfb34edcc15e0ed6d88a3828d595cc4c222bb52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xbf3c7921ed939a05255bbc31ee61a6c75282b1ba                         |                                                              |
| value             | VARCHAR   | 50000000                                                           |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2022-11-07 22:44:20+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35545107                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19aa1df8b91cdb3133c96013c5a64bff0cdf5ba979ec83266f31fd2d6ff7be05             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                                     | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x04f2c60d181d3255968a86a0fc76c524265e200c                                     |                                                              |
| toUser            | VARCHAR   | 0x76d3030728e52deb8848d5613abade88441cbc59                                     |                                                              |
| asset             | VARCHAR   | 0x4200000000000000000000000000000000000006                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039456774570619114599328 |                                                              |

## 56. Table: VariableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-01 09:36:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33333077                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6cf4db09267f796c36c208da5c7a21137dbfbcde51a4e9da93c0403ea74ea3a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x953a573793604af8d41f306feb8274190db4ae0e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x9ef1e5eea13131065d64e53a0595ea487746324a                         |                                                              |
| target            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 31948442313591284618                                               |                                                              |
| balanceIncrease   | VARCHAR   | 1557686408715382                                                   |                                                              |
| index             | VARCHAR   | 1008985112276900240922250210                                       |                                                              |

## 57. Table: VariableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-05-10 10:23:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 97221914                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xde62532430b5744ad8c633f462cbe12b7ea4173cf0a7e741669c914b9607bdaf | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xfb00ac187a8eb5afae4eace434f493eb62672df7                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x94b008aa00579c1307b0ef2c499ad98a8ce58e58                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 6                                                                  |                                                              |
| debtTokenName        | VARCHAR   | Aave Optimism Variable Debt USDT                                   |                                                              |
| debtTokenSymbol      | VARCHAR   | variableDebtOptUSDT                                                |                                                              |
| params               | VARCHAR   | 0x30783130                                                         |                                                              |

## 58. Table: VariableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 22:58:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7919091                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab698b25f6a5044206b26d311b4d7308f993ddd017611b1ac8d057824f0eda32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a1c3ad6ed28a636ee1751c69071f6be75deb8b8                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x2a4e6c78f12333481a6d932ba526eb56bd64f008                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x2a4e6c78f12333481a6d932ba526eb56bd64f008                         |                                                              |
| value             | VARCHAR   | 2507691050285611692537                                             |                                                              |
| balanceIncrease   | VARCHAR   | 7691050285611692537                                                |                                                              |
| index             | VARCHAR   | 1003557987790924286049505944                                       |                                                              |

## 59. Table: VariableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 21:16:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 106755719                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08dd9171bae4396c40e731c83601c3af9a03157cb86d30238a6ceda25a649258 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x49bf093277bf4dde49c48c6aa55a3bda3eedef68                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 111958345879867114                                                 |                                                              |
