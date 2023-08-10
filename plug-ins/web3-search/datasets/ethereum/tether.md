# tether

## 1. Table: EuroTether\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-31 15:01:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13913794                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf825e67c02256706814cf713c6367f25861713c67dac252c724e8fbf417dabdc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc581b735a1688071a1746c968e0798d642ede491                         | Address of the contract that produced the log                |
| \_destination     | VARCHAR   | 0x5754284f345afc66a98fbb0a0afe71e0f007b949                         |                                                              |
| \_amount          | VARCHAR   | 250000000000000                                                    |                                                              |

## 2. Table: EuroTether\_event\_Redeem\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_amount          | VARCHAR   |                                                              |             |

## 3. Table: EuroTether\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-25 16:40:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15212823                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebb4a0711ce57dd9728754df650a9f4f3bb4f104b1678fdf5635dcc082133546 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc581b735a1688071a1746c968e0798d642ede491                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x876eabf441b2ee5b5b0554fd502a8e0600950cfa                         |                                                              |
| to                | VARCHAR   | 0x03ae1a796dfe0400439211133d065bda774b9d3e                         |                                                              |
| value             | VARCHAR   | 100000000                                                          |                                                              |

## 4. Table: TetherCNH\_event\_Issue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-14 05:34:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7564258                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2fef4d6c5c30dae19173f1213b4a780f1ba484d269b2acbd3752e2f793e6b293 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6e109e9dd7fa1a58bc3eff667e8e41fc3cc07aef                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 9990000000000                                                      |                                                              |

## 5. Table: TetherCNH\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-09 14:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8516323                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf35c9a6ab843715e9fc318be866a6b8fa56f9e70829490424a6273367625daa2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6e109e9dd7fa1a58bc3eff667e8e41fc3cc07aef                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 10000000000000                                                     |                                                              |

## 6. Table: TetherCNH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-24 18:52:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8613474                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa53eb370cd4991f91dfb3b8de8d955cd8942002fe6a693407ee882a739609af7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6e109e9dd7fa1a58bc3eff667e8e41fc3cc07aef                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x876eabf441b2ee5b5b0554fd502a8e0600950cfa                         |                                                              |
| to                | VARCHAR   | 0x378a5050fa2149fc549163011887c6c39eb576ff                         |                                                              |
| value             | VARCHAR   | 2000000                                                            |                                                              |

## 7. Table: TetherToken\_call\_transferOwnership\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-24 01:42:07+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15400068                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf170fe27b8ea50f4c5486385a8881d912eb1959ac34fcbdd0fcf874337f39fe5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 185                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newOwner           | VARCHAR   | 0xb5b35f1328beba2e2ab7e98841d4ee79dcd47947                         |                                                                                                                        |

## 8. Table: TetherToken\_event\_AddedBlackList\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-14 07:51:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17256761                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3331576d271f39ee303c7cfc05b35d4736e1a109d2de7ad8c3c9206cd70c1621 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0xca48f98a3864f9703cf44438aff40db38e14288c                         |                                                              |

## 9. Table: TetherToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 21:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17253597                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9f64b9fbad8c17ec716a75ce7e895a4d07a8fba58ab45adc7f4651c32a3e6ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 410                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x9710eb69a3eaa5ccd8308b7a7cc19d2c415f955d                         |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                         |                                                              |
| value             | VARCHAR   | 4986999600                                                         |                                                              |

## 10. Table: TetherToken\_event\_Deprecate\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newAddress        | VARCHAR   |                                                              |             |

## 11. Table: TetherToken\_event\_DestroyedBlackFunds\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-31 17:08:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9391275                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x034ff633fa37881d3e138cbd03e75062af78e6948a41a4496ee086f21c3742ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         | Address of the contract that produced the log                |
| \_blackListedUser | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| \_balance         | VARCHAR   | 4513336556                                                         |                                                              |

## 12. Table: TetherToken\_event\_Issue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-09-03 20:17:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8479323                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x79595df1a5d8b96c017cd78bbd844fb68c94c19edb554a729006eb1db0caf2c4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 15000000000000                                                     |                                                              |

## 13. Table: TetherToken\_event\_Params\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| feeBasisPoints    | VARCHAR   |                                                              |             |
| maxFee            | VARCHAR   |                                                              |             |

## 14. Table: TetherToken\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 15. Table: TetherToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-07 10:55:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16576442                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdd6aeebe6c3e5c05ea641ed931bf413cb851b91dd447941d5c787622e3962d91 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 2000000000000000                                                   |                                                              |

## 16. Table: TetherToken\_event\_RemovedBlackList\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-07 14:29:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10412852                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ff009ab203590cd32b30c1683e307b3fe0c5f84fb98b4a4f13662b977f635f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x087a39ecd3e12db24b76025efaf077a2fd6e44c2                         |                                                              |

## 17. Table: TetherToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-04-16 10:10:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5450322                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5598381c87d23b8363c29a956a75484ed73f27e0c7ef21087479aaeb7014e20 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x00799bbc833d5b168f0410312d2a8fd9e0e3079c                         |                                                              |
| to                | VARCHAR   | 0xfe2589686a29eeba112abc477be49658d17e4a34                         |                                                              |
| value             | VARCHAR   | 657420000                                                          |                                                              |

## 18. Table: TetherToken\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 19. Table: XAUt\_TetherToken\_event\_AddedBlackList\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_user            | VARCHAR   |                                                              |             |

## 20. Table: XAUt\_TetherToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-16 12:03:11+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11066820                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x49f482f3e60c3157718208b5ebb8feb5bebeea2654607184f3af0f751ce1689a             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 231                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4922a015c4407f87432b179bb209e125432e4a2a                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xb088740b8868bd063135821299dc9d34b0dd6988                                     |                                                              |
| spender           | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 21. Table: XAUt\_TetherToken\_event\_Deprecate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-08 13:17:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13576002                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2dd695ab2c85c1fb725f36bf0860f3e417069d3553d1a2b94d7d4421a02baed9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4922a015c4407f87432b179bb209e125432e4a2a                         | Address of the contract that produced the log                |
| newAddress        | VARCHAR   | 0x000000000000000000000000000000000000dead                         |                                                              |

## 22. Table: XAUt\_TetherToken\_event\_DestroyedBlackFunds\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_blackListedUser | VARCHAR   |                                                              |             |
| \_balance         | VARCHAR   |                                                              |             |

## 23. Table: XAUt\_TetherToken\_event\_Issue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-24 17:03:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9735353                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd4b94bed9198b54c7ed9375b2cdd0f8f1012ade78f3694a4336e52a3a424539 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4922a015c4407f87432b179bb209e125432e4a2a                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 4384281000                                                         |                                                              |

## 24. Table: XAUt\_TetherToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:23:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9241022                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65d2a8fd82c7bc46856d13546187e2cb650c7a529d0d7e62ab8ce38acf1857e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4922a015c4407f87432b179bb209e125432e4a2a                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x14d06788090769f669427b6aea1c0240d2321f34                         |                                                              |

## 25. Table: XAUt\_TetherToken\_event\_Params\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| feeBasisPoints    | VARCHAR   |                                                              |             |
| maxFee            | VARCHAR   |                                                              |             |

## 26. Table: XAUt\_TetherToken\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 27. Table: XAUt\_TetherToken\_event\_PauserAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-08 16:23:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9241022                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65d2a8fd82c7bc46856d13546187e2cb650c7a529d0d7e62ab8ce38acf1857e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4922a015c4407f87432b179bb209e125432e4a2a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x14d06788090769f669427b6aea1c0240d2321f34                         |                                                              |

## 28. Table: XAUt\_TetherToken\_event\_PauserRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 29. Table: XAUt\_TetherToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-31 10:31:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11561376                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf822af6b422271634a64675e8964e8bf1d71702754267d87984552da130fca83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4922a015c4407f87432b179bb209e125432e4a2a                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 796786000                                                          |                                                              |

## 30. Table: XAUt\_TetherToken\_event\_RemovedBlackList\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_user            | VARCHAR   |                                                              |             |

## 31. Table: XAUt\_TetherToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-11 15:29:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12018090                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x54c6722c88d3a2bc7f4fdc766a96f47cd670fb8670860ad31114246ae40e9364 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 174                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4922a015c4407f87432b179bb209e125432e4a2a                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x8b0e81d1629f231c3a8d613c2baf5e1af406cc64                         |                                                              |
| to                | VARCHAR   | 0x4f6742badb049791cd9a37ea913f2bac38d01279                         |                                                              |
| value             | VARCHAR   | 74470                                                              |                                                              |

## 32. Table: XAUt\_TetherToken\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 33. Table: XAUt\_v2\_TetherToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-12 20:58:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13603586                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2bbd0704e8df2d96b0928842a7228d418360c135bbc267697115add89a86abc5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68749665ff8d2d112fa859aa293f07a622782f38                         | Address of the contract that produced the log                |
| \_destination     | VARCHAR   | 0x5754284f345afc66a98fbb0a0afe71e0f007b949                         |                                                              |
| \_amount          | VARCHAR   | 20131765000                                                        |                                                              |

## 34. Table: XAUt\_v2\_TetherToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-08 17:13:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13577024                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x16599422bc6996bd45d1a8024a2a39bcb7f1a2206e43adf851392c1b33e67f76 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68749665ff8d2d112fa859aa293f07a622782f38                         | Address of the contract that produced the log                |
| \_amount          | VARCHAR   | 1000000                                                            |                                                              |

## 35. Table: XAUt\_v2\_TetherToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-17 09:05:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16647434                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa5777f2ee55b9ca56d1389bacbf90a8050d4bdf2cc07d4446501b96aabda987d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68749665ff8d2d112fa859aa293f07a622782f38                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x74de5d4fcbf63e00296fd95d33236b9794016631                         |                                                              |
| to                | VARCHAR   | 0x502e5174332239cee9915ab22764cd7684d27da1                         |                                                              |
| value             | VARCHAR   | 27260                                                              |                                                              |
