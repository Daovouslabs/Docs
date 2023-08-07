# traderjoe

## 1. Table: LBFactory\_event\_LBPairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-24 10:30:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30429028                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe923166fa78c8d7e0a529cef426725113a8c525848c3de1285cedd24c1068c83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e42f2f4101563bf679975178e880fd87d3efd4e                         | Address of the contract that produced the log                |
| tokenX            | VARCHAR   | 0x01f73863edd62770bdbbbfe065a59a723df99b39                         |                                                              |
| tokenY            | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         |                                                              |
| binStep           | VARCHAR   | 25                                                                 |                                                              |
| LBPair            | VARCHAR   | 0x557a53b5611f139e96a902c38eb667ac737944b9                         |                                                              |
| pid               | VARCHAR   | 212                                                                |                                                              |

## 2. Table: LBPair\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 23:41:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33460004                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02d1d15b37e286605f0753fbad9d20f2fee72322c73faa9ed88a26f10ad0d758 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x39bd85c7120fd00adc5e4c710d811cdbc3d86ff5                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x31d8c2f657ffe182330a854b69360f60f73ea1fa                         |                                                              |
| sender            | VARCHAR   | 0xb4315e873dbcf96ffd0acd8ea43f689d8c20fb30                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 3. Table: LBPair\_event\_CollectedProtocolFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 14:45:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32466875                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3579cd906bbdad6fc577b9b231788efcd3585148261f7e56e81931c6ac5defd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4224f6f4c9280509724db2dbac314621e4465c29                         | Address of the contract that produced the log                |
| feeRecipient      | VARCHAR   | 0x60233142befce7d4ed73e7793ead2d6190fccaab                         |                                                              |
| protocolFees      | VARCHAR   | 0x00000000000000000000000020dff9730000000000000000000000000019e9e0 |                                                              |

## 4. Table: LBPair\_event\_CompositionFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-26 17:17:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33110970                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1fb202ff75008e3a602097ae288670e44f5c02641f8b9022e40a1c4be39e7fba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd446eb1660f766d533beceef890df7a69d26f7d1                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0ddba20fa3b247fb3381cde1a1fae35c032e33fc                         |                                                              |
| id                | VARCHAR   | 8376067                                                            |                                                              |
| totalFees         | VARCHAR   | 0x00000000000000000000000000000000000000000000000000231f5ae52b727e |                                                              |
| protocolFees      | VARCHAR   | 0x00000000000000000000000000000000000000000000000000038322b084583f |                                                              |

## 5. Table: LBPair\_event\_DepositedToBins\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 16:19:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33192500                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5be89c29505e5995a9cf2ea36c46d28b3d2cf63aab777f106d2ff0244fc3a8af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16396b65d5e0794c44447396f94665d3b9f576a0                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xb4315e873dbcf96ffd0acd8ea43f689d8c20fb30                         |                                                              |
| to                | VARCHAR   | 0xa4762425c8164ad1ff136f5ea07bd5f5b51fecb6                         |                                                              |
| ids               | VARCHAR   | 8362817                                                            |                                                              |
| amounts           | VARCHAR   | 0x00000000000000000000000000000000000000000000000000f8b0a10e470000 |                                                              |

## 6. Table: LBPair\_event\_FlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 02:03:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33549697                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa5d97339b0345fd8c7ab6d322be5fbf5f3b57ef219aeff93444f0812466e0e83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd446eb1660f766d533beceef890df7a69d26f7d1                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x43d6b8562d8761cd1ed5f14b280921c0f4699c0c                         |                                                              |
| receiver          | VARCHAR   | 0x43d6b8562d8761cd1ed5f14b280921c0f4699c0c                         |                                                              |
| activeId          | VARCHAR   | 8376042                                                            |                                                              |
| amounts           | VARCHAR   | 0x000000000000000000000001f0643e2400000000000000000000000000000000 |                                                              |
| totalFees         | VARCHAR   | 0x0000000000000000000000000000a2a900000000000000000000000000000000 |                                                              |
| protocolFees      | VARCHAR   | 0x0000000000000000000000000000104400000000000000000000000000000000 |                                                              |

## 7. Table: LBPair\_event\_ForcedDecay\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| sender              | VARCHAR   |                                                              |             |
| idReference         | VARCHAR   |                                                              |             |
| volatilityReference | VARCHAR   |                                                              |             |

## 8. Table: LBPair\_event\_OracleLengthIncreased\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| oracleLength      | VARCHAR   |                                                              |             |

## 9. Table: LBPair\_event\_StaticFeeParametersSet\_history

| Column                   | Type      | Example                                                            | Description                                                  |
| ------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP | 2023-06-24 22:06:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER   | 31759051                                                           | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR   | 0x1aaa1c0a6146952895a4d62d3c1468bab563978b7158c9f78c3417a763ca9db6 | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR   | 0x254e0aad86cfc05ddd2816162fe78b767532ef68                         | Address of the contract that produced the log                |
| sender                   | VARCHAR   | 0x8e42f2f4101563bf679975178e880fd87d3efd4e                         |                                                              |
| baseFactor               | VARCHAR   | 8000                                                               |                                                              |
| filterPeriod             | VARCHAR   | 300                                                                |                                                              |
| decayPeriod              | VARCHAR   | 1200                                                               |                                                              |
| reductionFactor          | VARCHAR   | 5000                                                               |                                                              |
| variableFeeControl       | VARCHAR   | 7500                                                               |                                                              |
| protocolShare            | VARCHAR   | 2500                                                               |                                                              |
| maxVolatilityAccumulator | VARCHAR   | 150000                                                             |                                                              |

## 10. Table: LBPair\_event\_Swap\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2023-04-11 02:57:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 28589432                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x8e2fa47a36ba65fa3944bc0b3cdd4f3004ac52d1f586ca621db35ee30adf8273 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x2f1da4bafd5f2508ec2e2e425036063a374993b6                         | Address of the contract that produced the log                |
| sender                | VARCHAR   | 0xb4315e873dbcf96ffd0acd8ea43f689d8c20fb30                         |                                                              |
| to                    | VARCHAR   | 0xb2848525fd6dfdce65fbcbd4ae69060892877480                         |                                                              |
| id                    | VARCHAR   | 8112281                                                            |                                                              |
| amountsIn             | VARCHAR   | 0x00000000000000000000000003e653c900000000000000000000000000000000 |                                                              |
| amountsOut            | VARCHAR   | 0x0000000000000000000000000000000000000000000000038c1220605324012f |                                                              |
| volatilityAccumulator | VARCHAR   | 0                                                                  |                                                              |
| totalFees             | VARCHAR   | 0x0000000000000000000000000000331e00000000000000000000000000000000 |                                                              |
| protocolFees          | VARCHAR   | 0x0000000000000000000000000000028e00000000000000000000000000000000 |                                                              |

## 11. Table: LBPair\_event\_TransferBatch\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 03:12:29+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30966047                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3764cd5f9d461bacbba0916674339a6fc0f9f55e3dc58e33e7fc6ee4d2e625e5                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c1ad4dfbe5a53e2689d5abccc82e1fb8eb34980                                                           | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xb4315e873dbcf96ffd0acd8ea43f689d8c20fb30                                                           |                                                              |
| from              | VARCHAR   | 0xbffe4f1724b8e3b44dc86e395801374f88769ed6                                                           |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| ids               | VARCHAR   | 8388163,8388164,8388165,8388166,8388167,8388168,8388169,8388170,8388171,8388172,8388173,8388174,8388 |                                                              |
| amounts           | VARCHAR   | 46133874237163351370471501421126343356213219821961224235,4781006756449983379605084855845826463515563 |                                                              |

## 12. Table: LBPair\_event\_WithdrawnFromBins\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-24 11:31:08+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33015256                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0affc5443a84b1579f8f00f4ddd8eb40f03591ae5b9d1f595fdbc89d446ef90c                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c1ad4dfbe5a53e2689d5abccc82e1fb8eb34980                                                           | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xb4315e873dbcf96ffd0acd8ea43f689d8c20fb30                                                           |                                                              |
| to                | VARCHAR   | 0xb4315e873dbcf96ffd0acd8ea43f689d8c20fb30                                                           |                                                              |
| ids               | VARCHAR   | 8388102,8388103,8388104,8388105,8388106                                                              |                                                              |
| amounts           | VARCHAR   | 0x0000000000000000063101338e70156700000000000000000000000000000000,0x00000000000000000753b0c921f02e7 |                                                              |

## 13. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-18 13:04:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12264908                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x727c9fd9af988a03fe04cfc412d6e5dc9a9727c1be1f9573a26ea2188ac15235 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ad6c38be94206ca50bb0d90783181662f0cfa10                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x130966628846bfd36ff31a822705796e8cb8c18d                         |                                                              |
| token1            | VARCHAR   | 0x885efa0adfdb93466136fb1cca7713035ac28808                         |                                                              |
| pair              | VARCHAR   | 0x7aed5203fc4d4aa84c7e80adb73d12cfe335140b                         |                                                              |
| \_uint            | VARCHAR   | 14400                                                              |                                                              |

## 14. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-16 19:12:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28832911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5ac8644bed1e31f4a90818bf26a3692824396b90345a18ce4ec73ec6b2c47c4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0512ab7ccf96af5512dbc2d4c93048f3f6a16608                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc3a5b60d1d985e99de292125b8e75164b417b41a                         |                                                              |
| spender           | VARCHAR   | 0x188bed1968b795d5c9022f6a0bb5931ac4c18f00                         |                                                              |
| value             | VARCHAR   | 30635554233424                                                     |                                                              |

## 15. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 08:09:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2896512                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x50a9bc28da265729e7eea5ddf4f1188c0b0022c2a29ed7f6d75d2a7284d6a1cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x29e0120de4406e9b2e28b15937b67eae5e50c510                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x60ae616a2155ee3d9a68541ba4544862310933d4                         |                                                              |
| amount0           | VARCHAR   | 21916770396074498915001                                            |                                                              |
| amount1           | VARCHAR   | 986407936                                                          |                                                              |
| to                | VARCHAR   | 0xd863f699b49f0a1d62142a2e5914f08b1620583f                         |                                                              |

## 16. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-12 16:38:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24851857                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x536637ced65f219db900ce8cf059931be1c632800e0656115c6438762399348f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4514c70a27a2e6035859d477b86c4e21b6209bf6                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x60ae616a2155ee3d9a68541ba4544862310933d4                         |                                                              |
| amount0           | VARCHAR   | 1520080548040369305641                                             |                                                              |
| amount1           | VARCHAR   | 14121500                                                           |                                                              |

## 17. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 04:30:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24242509                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x156544717e5a509672257ea9d214ed060d71a45688e98d098042363e33a77d89 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x565d20bd591b00ead0c927e4b6d7dd8a33b0b319                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000818a698e43cc84443654e31de25a764f4                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 130845662017098543370071                                           |                                                              |
| amount0Out        | VARCHAR   | 690415168232638454                                                 |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x0000000818a698e43cc84443654e31de25a764f4                         |                                                              |

## 18. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 18:01:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30738592                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d8db94fff426513dfe9e9b89131d2d42703a61efb62adba3254024d57eb289f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00979bd14bd5eb5c456c5478d3bf4b6e9212ba7d                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 2231388547222822262747463                                          |                                                              |
| reserve1          | VARCHAR   | 197241565027519869626                                              |                                                              |

## 19. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 19:36:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33452705                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5dccb7ac4df55c5c8298eb16ceee0f6ec4457276955d5916ce515e01fd13ef31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf45719fa196b37027d31a5509f84f7bd7096ea72                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x81c1c3af601f5b632f30fcc842b1582acf203c70                         |                                                              |
| value             | VARCHAR   | 147346188270523                                                    |                                                              |
