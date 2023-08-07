# aave

## 1. Table: AToken\_v3\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-19 07:45:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 47264260                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a47b232705055a56f1026383a64dc385bff33a5f447b70dd21e008aa991c29a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x625e7708f30ca75bfd92586e17077590c60eb4cd                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x777777773fdd8b28bb03377d10fcea75ad9768da                         |                                                              |
| spender           | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                         |                                                              |
| value             | VARCHAR   | 10001620583                                                        |                                                              |

## 2. Table: AToken\_v3\_event\_BalanceTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-03 06:45:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9223734                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfece10eb0892a279e2f349fbea5af5db23382182fef57cf51de0789946cb574c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe50fa9b3c56ffb159cb0fca61f5c9d750e8128c8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x8caa7ebe5c6ae6087fb65315d1b5aa7acd33b854                         |                                                              |
| to                | VARCHAR   | 0xc09e69e79106861df5d289da88349f10e2dc6b5c                         |                                                              |
| value             | VARCHAR   | 1125000000000000000                                                |                                                              |
| index             | VARCHAR   | 1000038328129931096229436952                                       |                                                              |

## 3. Table: AToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 07:09:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45241100                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf46a398a8ccdd22813d05d4f314d4fdca54e3a88dbf68f310395f93bff2e971e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x625e7708f30ca75bfd92586e17077590c60eb4cd                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x1c6ad3a22a8f40a00a106ad81b885519bbf43ced                         |                                                              |
| target            | VARCHAR   | 0x1c6ad3a22a8f40a00a106ad81b885519bbf43ced                         |                                                              |
| value             | VARCHAR   | 1000                                                               |                                                              |
| balanceIncrease   | VARCHAR   | 1                                                                  |                                                              |
| index             | VARCHAR   | 1008764371413072787507062865                                       |                                                              |

## 4. Table: AToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-13 23:04:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 100888218                                                          | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x079404ec130ee442d4e185f757a8960cfa89a676f3f99cf4e0a57f59f4b2a158 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xc45a479877e1e9dfe9fcd4056c699575a1045daa                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x3f56e0c36d275367b8c502090edf38289b3dea0d                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| treasury             | VARCHAR   | 0x053d55f9b5af8694c503eb288a1b7e552f590710                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| aTokenDecimals       | VARCHAR   | 18                                                                 |                                                              |
| aTokenName           | VARCHAR   | Aave Arbitrum MAI                                                  |                                                              |
| aTokenSymbol         | VARCHAR   | aArbMAI                                                            |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 5. Table: AToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-11 00:18:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17395662                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5eac84909fbcfc625edd290946cf302b01d1c5d45150fbc3fb72188c0d0749b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x82e64f49ed5ec1bc6e43dad4fc8af9bb3a2312ee                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x08e6d8dc4cac4680da1b77ce20471ee05696581e                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x08e6d8dc4cac4680da1b77ce20471ee05696581e                         |                                                              |
| value             | VARCHAR   | 139099170000000000                                                 |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1004333754622852370906494789                                       |                                                              |

## 6. Table: AToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-02 15:06:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34727434                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31d20e8b2fb341fbb0f2f10ca43ff66a40ac3ae4fa8c7c6dd466fb30362e1100 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x078f358208685046a11c85e8ad32895ded33a249                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xdd94018f54e565dbfc939f7c44a16e163faab331                         |                                                              |
| value             | VARCHAR   | 76333                                                              |                                                              |

## 7. Table: PoolConfigurator\_event\_ATokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-10 13:10:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 89267099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28196e923a50ce9ea72908d8a5c02818b4303adb3e26d37465124fc1d5e97e3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x5979d7b546e38e414f7e9822514be443a4800529                         |                                                              |
| proxy             | VARCHAR   | 0x513c7e3a9c69ca3e22550ef58ac1c0088e918fff                         |                                                              |
| implementation    | VARCHAR   | 0x1be1798b70aee431c2986f7ff48d9d1fa350786a                         |                                                              |

## 8. Table: PoolConfigurator\_event\_BorrowCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 15:10:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 89631631                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x37473745937ae602fc5fa61a7e5d1725029abd8425b28c1df39ff30563bedf82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xd22a58f79e9481d1a88e00c343885a588b34b68b                         |                                                              |
| oldBorrowCap      | VARCHAR   | 45000                                                              |                                                              |
| newBorrowCap      | VARCHAR   | 65000                                                              |                                                              |

## 9. Table: PoolConfigurator\_event\_BorrowableInIsolationChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-11 15:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7742655                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfe01742071ad2770550ef354fcc9a1c9e51ba905a6aee75dff04aca19b69500f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xda10009cbd5d07dd0cecc66161fc93d7c9000da1                         |                                                              |
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
| block\_timestamp     | TIMESTAMP | 2023-08-02 07:29:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 117342680                                                          | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x7a571088851bb4dfc27c3c4fea4449bb764145bc664a3d4d326628d728f10ba9 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                | VARCHAR   | 0x3f56e0c36d275367b8c502090edf38289b3dea0d                         |                                                              |
| ltv                  | VARCHAR   | 7500                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 8000                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10500                                                              |                                                              |

## 12. Table: PoolConfigurator\_event\_DebtCeilingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-28 10:09:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 105740626                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x904364beeab39ba08a36254891516f94de49af3e0c7272c516a90a678a2a8cc0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xaf88d065e77c8cc2239327c5edb3a432268e5831                         |                                                              |
| oldDebtCeiling    | VARCHAR   | 0                                                                  |                                                              |
| newDebtCeiling    | VARCHAR   | 0                                                                  |                                                              |

## 13. Table: PoolConfigurator\_event\_EModeAssetCategoryChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-28 10:09:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 105740626                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x904364beeab39ba08a36254891516f94de49af3e0c7272c516a90a678a2a8cc0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xaf88d065e77c8cc2239327c5edb3a432268e5831                         |                                                              |
| oldCategoryId     | VARCHAR   | 0                                                                  |                                                              |
| newCategoryId     | VARCHAR   | 1                                                                  |                                                              |

## 14. Table: PoolConfigurator\_event\_EModeCategoryAdded\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-05-29 19:00:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 95752233                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x62124c8c75643d3d65cc7001628ee29eb13c5e8d3b25b51b79d9601b423224d3 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| categoryId           | VARCHAR   | 1                                                                  |                                                              |
| ltv                  | VARCHAR   | 9300                                                               |                                                              |
| liquidationThreshold | VARCHAR   | 9500                                                               |                                                              |
| liquidationBonus     | VARCHAR   | 10100                                                              |                                                              |
| oracle               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| label                | VARCHAR   | Stablecoins                                                        |                                                              |

## 15. Table: PoolConfigurator\_event\_FlashloanPremiumToProtocolUpdated\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2023-05-10 13:10:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 89267099                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0x28196e923a50ce9ea72908d8a5c02818b4303adb3e26d37465124fc1d5e97e3e | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumToProtocol | VARCHAR   | 0                                                                  |                                                              |
| newFlashloanPremiumToProtocol | VARCHAR   | 4                                                                  |                                                              |

## 16. Table: PoolConfigurator\_event\_FlashloanPremiumTotalUpdated\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2022-03-11 15:02:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 7742446                                                            | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0xea0e1798dd709afcd1f825566836ab6fe0d19072c01c5328a7a404b92eb2d91d | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| oldFlashloanPremiumTotal | VARCHAR   | 9                                                                  |                                                              |
| newFlashloanPremiumTotal | VARCHAR   | 5                                                                  |                                                              |

## 17. Table: PoolConfigurator\_event\_LiquidationProtocolFeeChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-06 19:58:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 108543860                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xddbd0f35650f09bf8381790a6ffe80ee76f228153c1e6e9615a8f7de7b91ba63 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
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
| block\_timestamp  | TIMESTAMP | 2023-07-06 19:58:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 108543860                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xddbd0f35650f09bf8381790a6ffe80ee76f228153c1e6e9615a8f7de7b91ba63 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
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
| block\_timestamp  | TIMESTAMP | 2023-06-28 10:09:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 105740626                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x904364beeab39ba08a36254891516f94de49af3e0c7272c516a90a678a2a8cc0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xaf88d065e77c8cc2239327c5edb3a432268e5831                         |                                                              |
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
| block\_timestamp            | TIMESTAMP | 2023-06-28 10:09:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 105740626                                                          | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x904364beeab39ba08a36254891516f94de49af3e0c7272c516a90a678a2a8cc0 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset                       | VARCHAR   | 0xaf88d065e77c8cc2239327c5edb3a432268e5831                         |                                                              |
| aToken                      | VARCHAR   | 0x724dc807b04555b71ed48a6896b6f41593b8c637                         |                                                              |
| stableDebtToken             | VARCHAR   | 0xdc1fad70953bb3918592b6fcc374fe05f5811b6a                         |                                                              |
| variableDebtToken           | VARCHAR   | 0xf611aeb5013fd2c0511c9cd55c7dc5c1140741a6                         |                                                              |
| interestRateStrategyAddress | VARCHAR   | 0xf6733b9842883bfe0e0a940ea2f572676af31bde                         |                                                              |

## 24. Table: PoolConfigurator\_event\_ReserveInterestRateStrategyChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-24 19:26:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 94042943                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd32ce416928c33009e516ca7660d893370299d4a50d5558cf4da15da4c9acf41 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xff970a61a04b1ca14834a43f5de4533ebddb5cc8                         |                                                              |
| oldStrategy       | VARCHAR   | 0x41b66b4b6b4c9dab039d96528d1b88f7baf8c5a4                         |                                                              |
| newStrategy       | VARCHAR   | 0xd9d85499449f26d2a2c240defd75314f23920089                         |                                                              |

## 25. Table: PoolConfigurator\_event\_ReservePaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 23:04:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 100888218                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x079404ec130ee442d4e185f757a8960cfa89a676f3f99cf4e0a57f59f4b2a158 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x3f56e0c36d275367b8c502090edf38289b3dea0d                         |                                                              |
| paused            | VARCHAR   | false                                                              |                                                              |

## 26. Table: PoolConfigurator\_event\_ReserveStableRateBorrowing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 21:28:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 113260138                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x793ecdf0b56b1b94ec81a6c16466ad9ae2cf9b16eb9baebbb903109d0a79d2d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x912ce59144191c1204e64559fe8253a0e49e6548                         |                                                              |
| enabled           | VARCHAR   | false                                                              |                                                              |

## 27. Table: PoolConfigurator\_event\_SiloedBorrowingChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-28 10:09:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 105740626                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x904364beeab39ba08a36254891516f94de49af3e0c7272c516a90a678a2a8cc0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xaf88d065e77c8cc2239327c5edb3a432268e5831                         |                                                              |
| oldState          | VARCHAR   | false                                                              |                                                              |
| newState          | VARCHAR   | false                                                              |                                                              |

## 28. Table: PoolConfigurator\_event\_StableDebtTokenUpgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 23:04:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 100888218                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x079404ec130ee442d4e185f757a8960cfa89a676f3f99cf4e0a57f59f4b2a158 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x3f56e0c36d275367b8c502090edf38289b3dea0d                         |                                                              |
| proxy             | VARCHAR   | 0x78246294a4c6fbf614ed73ccc9f8b875ca8ee841                         |                                                              |
| implementation    | VARCHAR   | 0x0c2c95b24529664fe55d4437d7a31175cfe6c4f7                         |                                                              |

## 29. Table: PoolConfigurator\_event\_SupplyCapChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-17 11:14:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 91593222                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa50be41f24a91038ff57742191f740c9279b3ded3dcd424cbd22380f499a6b75 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| oldSupplyCap      | VARCHAR   | 2100                                                               |                                                              |
| newSupplyCap      | VARCHAR   | 4200                                                               |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2023-05-10 13:10:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 89267099                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x28196e923a50ce9ea72908d8a5c02818b4303adb3e26d37465124fc1d5e97e3e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8145edddf43f50276641b55bd3ad95944510021e                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xff970a61a04b1ca14834a43f5de4533ebddb5cc8                         |                                                              |
| proxy             | VARCHAR   | 0xfccf3cabbe80101232d343252614b6a3ee81c989                         |                                                              |
| implementation    | VARCHAR   | 0x5e76e98e0963ecdc6a065d1435f84065b7523f39                         |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2022-10-14 15:15:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30099647                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0e4f23986f21f6de3c050c629606575f684ffbb44fa06d2992a31e53b7ea394 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| user              | VARCHAR   | 0x2a16a27bfbfc3d2e2fec846768f8b59e5341af6a                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x2a16a27bfbfc3d2e2fec846768f8b59e5341af6a                         |                                                              |
| amount            | VARCHAR   | 12136065                                                           |                                                              |
| interestRateMode  | VARCHAR   | 2                                                                  |                                                              |
| borrowRate        | VARCHAR   | 30787278818137836330801389                                         |                                                              |
| referralCode      | VARCHAR   | 3228                                                               |                                                              |

## 34. Table: Pool\_v3\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 05:49:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 89841776                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93ef500e8e0260d0a22b6f7b7eee71e023d2e997bf0375b4978bb7685f966f56 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0xb20bd14259089e63d1f49d8d887aba783ce5dac2                         |                                                              |
| initiator         | VARCHAR   | 0xdb16bb1e9208c46fa0cd1d64fd290d017958f476                         |                                                              |
| asset             | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| amount            | VARCHAR   | 324000000                                                          |                                                              |
| interestRateMode  | VARCHAR   | 0                                                                  |                                                              |
| premium           | VARCHAR   | 162000                                                             |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 35. Table: Pool\_v3\_event\_IsolationModeTotalDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 00:53:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 115623099                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7875e65c597fd5485ac2d28837ed49edefec4e936dfd525acdf60027e74835d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0x912ce59144191c1204e64559fe8253a0e49e6548                         |                                                              |
| totalDebt         | VARCHAR   | 204359682                                                          |                                                              |

## 36. Table: Pool\_v3\_event\_LiquidationCall\_history

| Column                     | Type      | Example                                                            | Description                                                  |
| -------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP | 2023-06-15 06:45:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER   | 101334081                                                          | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR   | 0x718761d79360d121394c84d490d8d074ad56865d25c7f5ce559893304c95ca11 | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| collateralAsset            | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| debtAsset                  | VARCHAR   | 0xfd086bc7cd5c481dcc9c85ebe478a1c0b69fcbb9                         |                                                              |
| user                       | VARCHAR   | 0xbfef6ccb683adf274397343e1de18f9a837734b9                         |                                                              |
| debtToCover                | VARCHAR   | 50501163                                                           |                                                              |
| liquidatedCollateralAmount | VARCHAR   | 215065                                                             |                                                              |
| liquidator                 | VARCHAR   | 0x7007494e769e69e8a085d8215dfaa1b3723588d5                         |                                                              |
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
| block\_timestamp  | TIMESTAMP | 2023-06-20 06:10:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 102995161                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b6e9c3582d3ceaebf393d535020410fc37a361dd735afd7184566f88bc2daf1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xf97f4df75117a78c1a5a0dbb814af92458539fb4                         |                                                              |
| amountMinted      | VARCHAR   | 5035773750154887636                                                |                                                              |

## 39. Table: Pool\_v3\_event\_RebalanceStableBorrowRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-21 09:48:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 72079396                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb08eda6fed5f39c3186cd5f311f8ee06d69d7865671a2ce08ed08b924eefe65a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xfd086bc7cd5c481dcc9c85ebe478a1c0b69fcbb9                         |                                                              |
| user              | VARCHAR   | 0xd35db3b19c8c2a60b8613e5b30aadcd290c99e75                         |                                                              |

## 40. Table: Pool\_v3\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 10:08:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 90240331                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x34c09ffe3d41a791bb9849ce0db2c82b889b7c9ed42a47e7fdfc7bbd95518e2e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| user              | VARCHAR   | 0x0081772fd29e4838372cbccdd020f53954f5ecde                         |                                                              |
| repayer           | VARCHAR   | 0x0081772fd29e4838372cbccdd020f53954f5ecde                         |                                                              |
| amount            | VARCHAR   | 580161                                                             |                                                              |
| useATokens        | VARCHAR   | false                                                              |                                                              |

## 41. Table: Pool\_v3\_event\_ReserveDataUpdated\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-05-15 18:12:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 91025381                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x14ccdebda8c477a34cc9b77599877f45fa91fbf0a4eb8f98cfbd05d5d7a5d338 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve             | VARCHAR   | 0x5979d7b546e38e414f7e9822514be443a4800529                         |                                                              |
| liquidityRate       | VARCHAR   | 73366223959353691699056                                            |                                                              |
| stableBorrowRate    | VARCHAR   | 55000000000000000000000000                                         |                                                              |
| variableBorrowRate  | VARCHAR   | 4442776294356733767823124                                          |                                                              |
| liquidityIndex      | VARCHAR   | 1000071179410091111671659327                                       |                                                              |
| variableBorrowIndex | VARCHAR   | 1001245192590644332931117375                                       |                                                              |

## 42. Table: Pool\_v3\_event\_ReserveUsedAsCollateralDisabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 23:10:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 116568732                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf752926dbcffc4ef32c25dea3fbd4bbab6b6e7980404faac24f0e27b642504fc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| user              | VARCHAR   | 0x584378bd63092f6e8ee02d1f2b8c52fdade65451                         |                                                              |

## 43. Table: Pool\_v3\_event\_ReserveUsedAsCollateralEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 00:00:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 117565715                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x722b656feb23fb2aeec7c8580e40561ae4acfc383b06d0cb596b1ef4d4566baf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| user              | VARCHAR   | 0xc631d53c85c3c4653fbb709f6435013423d8d50c                         |                                                              |

## 44. Table: Pool\_v3\_event\_Supply\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 00:25:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 112295058                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb74cd54ac395d8581558585f228564c5b1a3e70c08d0ac7b5ff161f7ccc5f3f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| user              | VARCHAR   | 0x0e61dae710688c22d8f6d0c3fdd1735d27ddff8f                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x0e61dae710688c22d8f6d0c3fdd1735d27ddff8f                         |                                                              |
| amount            | VARCHAR   | 251118726                                                          |                                                              |
| referralCode      | VARCHAR   | 0                                                                  |                                                              |

## 45. Table: Pool\_v3\_event\_SwapBorrowRateMode\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 13:26:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 104114079                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf4ad158ab3051e05934305afd06a8e9ee118d4b4b8207a803ead7f179bb50619 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0xda10009cbd5d07dd0cecc66161fc93d7c9000da1                         |                                                              |
| user              | VARCHAR   | 0xb7fb2b774eb5e2dad9c060fb367acbdc7fa7099b                         |                                                              |
| interestRateMode  | VARCHAR   | 1                                                                  |                                                              |

## 46. Table: Pool\_v3\_event\_UserEModeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-17 09:35:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 91569315                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc07edf8e4ebee5312eed7200de54fdb09d88bbb5db5cfab03ff00c9931be493a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x105b512f095dd2bd22bd95b52c634beac2707a56                         |                                                              |
| categoryId        | VARCHAR   | 0                                                                  |                                                              |

## 47. Table: Pool\_v3\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 20:07:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 90045602                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4beb535d41f362a6065d15c931470a9cb2d2dc4dde13ede401691232f22ae035 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         | Address of the contract that produced the log                |
| reserve           | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| user              | VARCHAR   | 0x2148b6995cce174c9e70d77890882ade9d19c5b5                         |                                                              |
| to                | VARCHAR   | 0x2148b6995cce174c9e70d77890882ade9d19c5b5                         |                                                              |
| amount            | VARCHAR   | 50294894                                                           |                                                              |

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

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-14 07:58:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37964812                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2936254995a5a0978df24ed335405d0f47ecb3de2292917da1c3bbaf559ffeb8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf15f26710c827dde8acba678682f3ce24f2fb56e                         | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x856b63349fb6c818ea7cd7305483ae0ef6956f6c                         |                                                              |
| toUser            | VARCHAR   | 0xd2d63812c72d2455a9613efdf41feb4b0b58a7a9                         |                                                              |
| asset             | VARCHAR   | 0xd22a58f79e9481d1a88e00c343885a588b34b68b                         |                                                              |
| amount            | VARCHAR   | 11100                                                              |                                                              |

## 50. Table: StableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-19 22:11:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31111855                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b3ad2cb6a460a1a9584eaefccfb377603bf0e13ebbeb3fb4b3d3d8e6fc3a2a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x69c688b1886bf8c4a46a6be210da7f3ee66a3270                         |                                                              |
| amount            | VARCHAR   | 232011447                                                          |                                                              |
| currentBalance    | VARCHAR   | 900598553                                                          |                                                              |
| balanceIncrease   | VARCHAR   | 598553                                                             |                                                              |
| avgStableRate     | VARCHAR   | 53215220300845426365044714                                         |                                                              |
| newTotalSupply    | VARCHAR   | 144475369648                                                       |                                                              |

## 51. Table: StableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-07-20 21:28:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 113260138                                                          | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x793ecdf0b56b1b94ec81a6c16466ad9ae2cf9b16eb9baebbb903109d0a79d2d5 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x6b4b37618d85db2a7b469983c888040f7f05ea3d                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0x912ce59144191c1204e64559fe8253a0e49e6548                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 18                                                                 |                                                              |
| debtTokenName        | VARCHAR   | Aave Arbitrum Stable Debt ARB                                      |                                                              |
| debtTokenSymbol      | VARCHAR   | stableDebtArbARB                                                   |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 52. Table: StableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-16 23:57:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 53574426                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b225837f1a9c522da359ae5010a32ab4c5ed8d02603ad12ca8d5cdc8db127f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x8fc45d41d38e892552951c0cad384359e9d60496                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x8fc45d41d38e892552951c0cad384359e9d60496                         |                                                              |
| amount            | VARCHAR   | 300385614                                                          |                                                              |
| currentBalance    | VARCHAR   | 700385614                                                          |                                                              |
| balanceIncrease   | VARCHAR   | 385614                                                             |                                                              |
| newRate           | VARCHAR   | 52105869179785220302058442                                         |                                                              |
| avgStableRate     | VARCHAR   | 52032020440045878899934863                                         |                                                              |
| newTotalSupply    | VARCHAR   | 234923144524                                                       |                                                              |

## 53. Table: StableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-11 17:33:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45353451                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3c58097132271eeed2f1ef5762b7b097cffd500ca725703481b8c59886fab66b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x307ffe186f84a3bc2613d1ea417a5737d69a7007                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x4fdc572d236eb6b2aff21fd660f533094b4cdcbb                         |                                                              |
| value             | VARCHAR   | 100000                                                             |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2022-04-13 01:59:00+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9717928                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba7947dbc2b76f928e1f4f580fe5ae9050a9b6c429619da2464482e599a659c5             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                                     | Address of the contract that produced the log                |
| fromUser          | VARCHAR   | 0x9bcf5d66a7755307de85bd2b0e9edb80f885e9a4                                     |                                                              |
| toUser            | VARCHAR   | 0xc09e69e79106861df5d289da88349f10e2dc6b5c                                     |                                                              |
| asset             | VARCHAR   | 0x82af49447d8a07e3bd95bd0d56f35241523fbab1                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039455584007913129639935 |                                                              |

## 56. Table: VariableDebtToken\_v3\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 04:08:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24965882                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae942095d726f6432635cdbabf5650f7010f9d6f5588d2151aa2ae59c8d29d34 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xba1bfd85432905ff4a2e7f516b56b7485dbdc5f6                         |                                                              |
| target            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 130305468505546580829                                              |                                                              |
| balanceIncrease   | VARCHAR   | 856139453419171                                                    |                                                              |
| index             | VARCHAR   | 1006987591738648456375907224                                       |                                                              |

## 57. Table: VariableDebtToken\_v3\_event\_Initialized\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-19 16:14:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 102803975                                                          | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x978e9aa898eaaab8daecde4985f89c4d51cd1c9880552a9356446a2ca0376b2d | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xce186f6cccb0c955445bb9d10c59cae488fea559                         | Address of the contract that produced the log                |
| underlyingAsset      | VARCHAR   | 0xec70dcb4a1efa46b8f2d97c310c9c4790ba5ffa8                         |                                                              |
| pool                 | VARCHAR   | 0x794a61358d6845594f94dc1db02a252b5b4814ad                         |                                                              |
| incentivesController | VARCHAR   | 0x929ec64c34a17401f460460d4b9390518e5b473e                         |                                                              |
| debtTokenDecimals    | VARCHAR   | 18                                                                 |                                                              |
| debtTokenName        | VARCHAR   | Aave Arbitrum Variable Debt rETH                                   |                                                              |
| debtTokenSymbol      | VARCHAR   | variableDebtArbrETH                                                |                                                              |
| params               | VARCHAR   | 0x                                                                 |                                                              |

## 58. Table: VariableDebtToken\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-02 12:29:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22484016                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b01b7fcfe96574ce16075db08d9ee92f5b18402ef10781efaeb21a858674f6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfccf3cabbe80101232d343252614b6a3ee81c989                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x414ad172bc61073f9e16361369b188ce1216c12e                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x414ad172bc61073f9e16361369b188ce1216c12e                         |                                                              |
| value             | VARCHAR   | 600000                                                             |                                                              |
| balanceIncrease   | VARCHAR   | 0                                                                  |                                                              |
| index             | VARCHAR   | 1011816476772891122272998416                                       |                                                              |

## 59. Table: VariableDebtToken\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 06:20:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 115697404                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93497b0ffd7f98af8c4f9441d5e2e3a28d278107729a72d73a9cea9edefc58ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c84331e39d6658cd6e6b9ba04736cc4c4734351                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xe408d65d495c567ab246e7c90f11d15d96c1738d                         |                                                              |
| value             | VARCHAR   | 10302800880491536                                                  |                                                              |
