# raft

## 1. Table: RaftMarket\_OneStopLeverage\_event\_LeveragedPositionAdjusted\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2023-08-06 19:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 17857967                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x60dbe4d045b662bdeb0a2c36ceda0020ecb3b6b39d487921666efa8c63dc302a | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 435                                                                | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0xb2bf4de5a63b2225338cdfdbad045ea62f158b67                         | Address of the contract that produced the log                |
| position                    | VARCHAR   | 0x0b17837db96070fc89baa37cf07ba20d34265d3f                         |                                                              |
| principalCollateralChange   | VARCHAR   | 0                                                                  |                                                              |
| principalCollateralIncrease | VARCHAR   | false                                                              |                                                              |
| debtChange                  | VARCHAR   | 3532020415260366587922                                             |                                                              |
| isDebtIncrease              | VARCHAR   | false                                                              |                                                              |
| leveragedCollateralChange   | VARCHAR   | 1700847615780123521                                                |                                                              |

## 2. Table: RaftMarket\_OneStopLeverage\_event\_StETHLeveragedPositionChange\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-07-13 10:05:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17683877                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x9cbee23dbe5c9a846408c9e044244dc55fae85cebadacfda284b35c6e899dc74 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xb2bf4de5a63b2225338cdfdbad045ea62f158b67                         | Address of the contract that produced the log                |
| position             | VARCHAR   | 0x920f5b48920b10f79517a760b50b0e9cfd2c77b9                         |                                                              |
| collateralChange     | VARCHAR   | 800000000000000000                                                 |                                                              |
| isCollateralIncrease | VARCHAR   | true                                                               |                                                              |
| debtChange           | VARCHAR   | 5292374177432609791761                                             |                                                              |
| isDebtIncrease       | VARCHAR   | true                                                               |                                                              |

## 3. Table: RaftMarket\_WrETH\_event\_WrappedCollateralTokenPositionChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-07-31 11:57:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17812837                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x16d60107638551dda10b765e4231579c105220920adc0cd7a805fac95a232119 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x29f8abb4cab4bbb56f617d9a3c0f62d33758e74e                         | Address of the contract that produced the log                |
| position             | VARCHAR   | 0x4a47dc0db886942c77fb3c86bf7f118818e8d3fb                         |                                                              |
| collateralAmount     | VARCHAR   | 2793400000000000000                                                |                                                              |
| isCollateralIncrease | VARCHAR   | true                                                               |                                                              |
| debtAmount           | VARCHAR   | 3000000000000000000000                                             |                                                              |
| isDebtIncrease       | VARCHAR   | true                                                               |                                                              |

## 4. Table: RaftMarket\_WstETH\_event\_ETHPositionChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| position          | VARCHAR   |                                                              |             |
| collateralAmount  | VARCHAR   |                                                              |             |
| debtAmount        | VARCHAR   |                                                              |             |
| isDebtIncrease    | VARCHAR   |                                                              |             |

## 5. Table: RaftMarket\_WstETH\_event\_StETHPositionChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-07-01 17:16:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17600627                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x6043955dd8a46b1b51ba54813acdfd54ec72387bb2c5ed0b596b17703354e044 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 366                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x839d6833cee34ffab6fa9057b39f02bd3091a1d6                         | Address of the contract that produced the log                |
| position             | VARCHAR   | 0xc4ed448e7d7bdd954e943954459017be63584f69                         |                                                              |
| collateralAmount     | VARCHAR   | 1000000000000000000                                                |                                                              |
| isCollateralIncrease | VARCHAR   | false                                                              |                                                              |
| debtAmount           | VARCHAR   | 0                                                                  |                                                              |
| isDebtIncrease       | VARCHAR   | false                                                              |                                                              |

## 6. Table: RaftMarket\_event\_CollateralChanged\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-20 03:10:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17518146                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xd3a0694c83414d95b18c147ed3036457789ea64d7b0371132b7585cc8368ed8b | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| position             | VARCHAR   | 0x0a66a105ea8a4fc5a0475b37cd4be050621b95d4                         |                                                              |
| collateralToken      | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         |                                                              |
| collateralAmount     | VARCHAR   | 3499371853570040503                                                |                                                              |
| isCollateralIncrease | VARCHAR   | true                                                               |                                                              |

## 7. Table: RaftMarket\_event\_CollateralTokenAdded\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-06-27 10:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 17570081                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x033a9d946544ebfec6b3095e26cda8529d0c5673ecc5eb132f595e98b16c4978 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| collateralToken     | VARCHAR   | 0xb69e35fb4a157028b92f42655090b984609ae598                         |                                                              |
| raftCollateralToken | VARCHAR   | 0xc38a040fac5769bded5dda8dea1aef609e755363                         |                                                              |
| raftDebtToken       | VARCHAR   | 0xf22cd22b5cf439825c6b75c816a4daf8fb44375b                         |                                                              |
| priceFeed           | VARCHAR   | 0x62ac8d1ebf61636e17d92ec3b24e8e03fb853cda                         |                                                              |

## 8. Table: RaftMarket\_event\_CollateralTokenModified\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| collateralToken   | VARCHAR   |                                                              |             |
| isEnabled         | VARCHAR   |                                                              |             |

## 9. Table: RaftMarket\_event\_DebtChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 17:37:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17472604                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9bc3652a23d38cc2839cb1ff4b8c991b3c7b1d984f5e4c17a4ba91b8f8dd74ab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 114                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| position          | VARCHAR   | 0x5d47e5d242a8f66a6286b0a2353868875f5d6068                         |                                                              |
| collateralToken   | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         |                                                              |
| debtAmount        | VARCHAR   | 1500000000000000000000                                             |                                                              |
| isDebtIncrease    | VARCHAR   | true                                                               |                                                              |

## 10. Table: RaftMarket\_event\_DelegateWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 10:43:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17669852                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82ab5677dd0fa1122a7b5a07487bbceb2c8b6fd81a00704fd151252d65891ee8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| position          | VARCHAR   | 0x7bde0285a9a8ec214192f0a2850c72d352eddafb                         |                                                              |
| delegate          | VARCHAR   | 0x29f8abb4cab4bbb56f617d9a3c0f62d33758e74e                         |                                                              |
| whitelisted       | VARCHAR   | true                                                               |                                                              |

## 11. Table: RaftMarket\_event\_Liquidation\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2023-06-28 02:32:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 17574870                                                           | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0x6a8ab210e862853757c4f01e781ba9fd8c815c4ba081e907848afbaffa1f1a67 | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| liquidator                   | VARCHAR   | 0xb0301424299128c9eab56cde6068c657b2195fe6                         |                                                              |
| position                     | VARCHAR   | 0xafd0659e7993bd4d820f17a2bb2e79205feaf9b9                         |                                                              |
| collateralToken              | VARCHAR   | 0xb69e35fb4a157028b92f42655090b984609ae598                         |                                                              |
| debtLiquidated               | VARCHAR   | 3030000073579969566000                                             |                                                              |
| collateralLiquidated         | VARCHAR   | 1788070000000000000                                                |                                                              |
| collateralSentToLiquidator   | VARCHAR   | 1788070000000000000                                                |                                                              |
| collateralLiquidationFeePaid | VARCHAR   | 0                                                                  |                                                              |
| isRedistribution             | VARCHAR   | false                                                              |                                                              |

## 12. Table: RaftMarket\_event\_PositionClosed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-14 20:35:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17480589                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7dc5ce1dd591aa7c76befff57c92459bc106dfd8d16fa04238c0c81b8c5f7da8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 439                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| position          | VARCHAR   | 0x40f29f239ee969f6dbb7697acf2241c8ee52e781                         |                                                              |

## 13. Table: RaftMarket\_event\_PositionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 11:18:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17470725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c4e3639e9b923735c0dcf769eb2a8f4b1d1062920fb48a7894590eb5156765e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| position          | VARCHAR   | 0x093d4c33391c15dc2d941be2937ada9926996113                         |                                                              |
| collateralToken   | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         |                                                              |

## 14. Table: RaftMarket\_event\_RBorrowingFeePaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 04:45:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17767817                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x61d706dc3dba8f78729bfb053cf01ac104bd26142281b290199127a0bcec8fbe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| collateralToken   | VARCHAR   | 0x7f39c581f595b53c5cb19bd0b3f8da6c935e2ca0                         |                                                              |
| position          | VARCHAR   | 0x03e33332db76774351b61ec88e2296e69f829518                         |                                                              |
| feeAmount         | VARCHAR   | 19080138545036501744                                               |                                                              |

## 15. Table: RaftMarket\_event\_Redemption\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 14:57:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17571423                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x319d665a47143367d74658d000118dd6c0f64e6d3cde8522ba79a6ca880f5ebe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 184                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x29f8abb4cab4bbb56f617d9a3c0f62d33758e74e                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000                                                |                                                              |
| collateralSent    | VARCHAR   | 493563863704561                                                    |                                                              |
| fee               | VARCHAR   | 9871289579310                                                      |                                                              |
| rebate            | VARCHAR   | 4935644789655                                                      |                                                              |

## 16. Table: RaftMarket\_event\_SplitLiquidationCollateralChanged\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2023-06-27 10:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 17570081                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0x033a9d946544ebfec6b3095e26cda8529d0c5673ecc5eb132f595e98b16c4978 | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 62                                                                 | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         | Address of the contract that produced the log                |
| collateralToken               | VARCHAR   | 0xb69e35fb4a157028b92f42655090b984609ae598                         |                                                              |
| newSplitLiquidationCollateral | VARCHAR   | 0xa63fb635a97ecb7c73dbca1529a821c175c6de57                         |                                                              |

## 17. Table: RaftMarket\_r\_event\_OwnershipTransferStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-22 22:48:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17317900                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x269e57c59df67dc684a07eaac090adce1608c45cb7b4b6ffe79e3499a898f20c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x183015a9ba6ff60230fdeadc3f43b3d788b13e21                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         |                                                              |
| newOwner          | VARCHAR   | 0x603d50bad151da8becf405e51a8c4abc8ba1c95e                         |                                                              |

## 18. Table: RaftMarket\_r\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-22 22:48:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17317900                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x269e57c59df67dc684a07eaac090adce1608c45cb7b4b6ffe79e3499a898f20c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x183015a9ba6ff60230fdeadc3f43b3d788b13e21                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         |                                                              |

## 19. Table: RaftMarket\_r\_event\_RDeployed\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-05-22 22:48:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 17317900                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x269e57c59df67dc684a07eaac090adce1608c45cb7b4b6ffe79e3499a898f20c | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x183015a9ba6ff60230fdeadc3f43b3d788b13e21                         | Address of the contract that produced the log                |
| positionManager       | VARCHAR   | 0x5f59b322eb3e16a0c78846195af1f588b77403fc                         |                                                              |
| flashMintFeeRecipient | VARCHAR   | 0x603d50bad151da8becf405e51a8c4abc8ba1c95e                         |                                                              |

## 20. Table: RaftMarket\_r\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-21 15:43:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17529004                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12e7e8dbf850a21823f30bba2c4a38e1251657080ce1fcee7d079aa136cf1ceb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 281                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x183015a9ba6ff60230fdeadc3f43b3d788b13e21                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xac1aa53108712d7f38093a67d380ad54b562a650                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 420690000000000000                                                 |                                                              |
