# camelot

## 1. Table: AlgebraFactory\_event\_DefaultCommunityFee\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-06-19 20:04:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 102858569                                                          | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xb5aaf7974d54ee896e5c0cf258804ef5a046d2af99242e30d14b6cb45fff7b66 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x1a3c9b1d2f0529d97f2afc5136cc23e58f1fd35b                         | Address of the contract that produced the log                |
| newDefaultCommunityFee | VARCHAR   | 150                                                                |                                                              |

## 2. Table: AlgebraFactory\_event\_FarmingAddress\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newFarmingAddress | VARCHAR   |                                                              |             |

## 3. Table: AlgebraFactory\_event\_FeeConfiguration\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-19 20:04:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 102858569                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5aaf7974d54ee896e5c0cf258804ef5a046d2af99242e30d14b6cb45fff7b66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a3c9b1d2f0529d97f2afc5136cc23e58f1fd35b                         | Address of the contract that produced the log                |
| alpha1            | VARCHAR   | 2900                                                               |                                                              |
| alpha2            | VARCHAR   | 9100                                                               |                                                              |
| beta1             | VARCHAR   | 360                                                                |                                                              |
| beta2             | VARCHAR   | 60000                                                              |                                                              |
| gamma1            | VARCHAR   | 59                                                                 |                                                              |
| gamma2            | VARCHAR   | 8500                                                               |                                                              |
| volumeBeta        | VARCHAR   | 0                                                                  |                                                              |
| volumeGamma       | VARCHAR   | 10                                                                 |                                                              |
| baseFee           | VARCHAR   | 3000                                                               |                                                              |

## 4. Table: AlgebraFactory\_event\_Owner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-14 18:35:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 101163738                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2420d9fe941f8ff2d9ac39a05f8d97535b7dbfa8a31830ddf3b1fd34c6d13ea7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a3c9b1d2f0529d97f2afc5136cc23e58f1fd35b                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0x6c0db7c063dd28bbf6c4bad43a21169f4565bc41                         |                                                              |

## 5. Table: AlgebraFactory\_event\_Pool\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-31 07:31:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 116682702                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1691300eb7672dcb8ab4d4f99f9458cb75640eb48c7dbed7948b0920950d4284 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a3c9b1d2f0529d97f2afc5136cc23e58f1fd35b                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x7a5d193fe4ed9098f7eadc99797087c96b002907                         |                                                              |
| token1            | VARCHAR   | 0x912ce59144191c1204e64559fe8253a0e49e6548                         |                                                              |
| pool              | VARCHAR   | 0x47a52b2bee1a0cc9a34bb9ee34c357c054112c3e                         |                                                              |

## 6. Table: AlgebraFactory\_event\_VaultAddress\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-19 20:04:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 102858569                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5aaf7974d54ee896e5c0cf258804ef5a046d2af99242e30d14b6cb45fff7b66 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1a3c9b1d2f0529d97f2afc5136cc23e58f1fd35b                         | Address of the contract that produced the log                |
| newVaultAddress   | VARCHAR   | 0x58095979b412a366687ca05cbe85ff56241be21f                         |                                                              |

## 7. Table: AlgebraPool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-12 05:33:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 110348588                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x21efa690748e303c93ba20f1353e60ff6d7cc44813ed3546fb00a9a198d490d8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa17afcab059f3c6751f5b64347b5a503c3291868                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x00c7f3082833e796a5b3e4bd59f6642ff44dcd15                         |                                                              |
| bottomTick        | VARCHAR   | -180                                                               |                                                              |
| topTick           | VARCHAR   | 180                                                                |                                                              |
| liquidityAmount   | VARCHAR   | 47672663134                                                        |                                                              |
| amount0           | VARCHAR   | 462749065                                                          |                                                              |
| amount1           | VARCHAR   | 391493051                                                          |                                                              |

## 8. Table: AlgebraPool\_event\_Collect\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 02:13:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 109965915                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1e05de6e11e542baaa133c1e5ffd8dd13d1892df06690d945975afa97755b76b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4045aa470d92fe2f2445eba8e1ad472e711e0af3                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x00c7f3082833e796a5b3e4bd59f6642ff44dcd15                         |                                                              |
| recipient         | VARCHAR   | 0x00c7f3082833e796a5b3e4bd59f6642ff44dcd15                         |                                                              |
| bottomTick        | VARCHAR   | 88020                                                              |                                                              |
| topTick           | VARCHAR   | 90360                                                              |                                                              |
| amount0           | VARCHAR   | 11271004100395                                                     |                                                              |
| amount1           | VARCHAR   | 36609212446344263708                                               |                                                              |

## 9. Table: AlgebraPool\_event\_CommunityFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-19 20:06:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 102859157                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x346ea45ed91f235b7a988f976736cbfd42455b498e18bbbdc2a4dd9db269aa9d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd845f7d4f4deb9ff5bcf09d140ef13718f6f6c71                         | Address of the contract that produced the log                |
| communityFee0New  | VARCHAR   | 150                                                                |                                                              |
| communityFee1New  | VARCHAR   | 150                                                                |                                                              |

## 10. Table: AlgebraPool\_event\_Fee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-04 19:14:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107885861                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa5b7c404abf5f6c070f2f7c9fb5ba1832d09cf727b3ed493a2bfa5312f8d5840 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ab5dd69950a948c55d1fbfb7500bf92b4bd4c48                         | Address of the contract that produced the log                |
| feeZto            | VARCHAR   | 100                                                                |                                                              |
| feeOtz            | VARCHAR   | 100                                                                |                                                              |

## 11. Table: AlgebraPool\_event\_Flash\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| recipient         | VARCHAR   |                                                              |             |
| amount0           | VARCHAR   |                                                              |             |
| amount1           | VARCHAR   |                                                              |             |
| paid0             | VARCHAR   |                                                              |             |
| paid1             | VARCHAR   |                                                              |             |

## 12. Table: AlgebraPool\_event\_Incentive\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| virtualPoolAddress | VARCHAR   |                                                              |             |

## 13. Table: AlgebraPool\_event\_Initialize\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 02:04:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 112986913                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x518b98f393ebf3162d0c08723f1dc8567fc311db958b569623d2c2061e9328d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdcbc534c5e976b4cf4e5a8d4baf8d78ce805ca8b                         | Address of the contract that produced the log                |
| price             | VARCHAR   | 6136842645893819031257990                                          |                                                              |
| tick              | VARCHAR   | -189325                                                            |                                                              |

## 14. Table: AlgebraPool\_event\_LiquidityCooldown\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| liquidityCooldown | VARCHAR   |                                                              |             |

## 15. Table: AlgebraPool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 00:23:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 117901674                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x460d7b5a7b6da926d74e1fddf0949ca4fd16058bd9d30b60b969bfb570e075bc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3ab5dd69950a948c55d1fbfb7500bf92b4bd4c48                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x00c7f3082833e796a5b3e4bd59f6642ff44dcd15                         |                                                              |
| owner             | VARCHAR   | 0x00c7f3082833e796a5b3e4bd59f6642ff44dcd15                         |                                                              |
| bottomTick        | VARCHAR   | -13                                                                |                                                              |
| topTick           | VARCHAR   | -3                                                                 |                                                              |
| liquidityAmount   | VARCHAR   | 16062437463754                                                     |                                                              |
| amount0           | VARCHAR   | 3341067086                                                         |                                                              |
| amount1           | VARCHAR   | 4688235293                                                         |                                                              |

## 16. Table: AlgebraPool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 11:13:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 118381634                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf10cae282ccb5fd3a9fed1997d2360afc43b809d643d76cd3f528dda9e0323b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe461f84c3fe6bcdd1162eb0ef4284f3bb6e4cad3                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x454c8b4dc6a2affe669a3db1633133f7d305e305                         |                                                              |
| recipient         | VARCHAR   | 0x00cabe722790e27ca6154e8fc34281384aa7052c                         |                                                              |
| amount0           | VARCHAR   | 32925956049784405318                                               |                                                              |
| amount1           | VARCHAR   | -12560362847420036                                                 |                                                              |
| price             | VARCHAR   | 1548805868151251759600872318                                       |                                                              |
| liquidity         | VARCHAR   | 509905009191646429360                                              |                                                              |
| tick              | VARCHAR   | -78701                                                             |                                                              |

## 17. Table: AlgebraPool\_event\_TickSpacing\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 01:46:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 111644789                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7f3aa46d18db55fe712cd3a602797b3353f84451f975e0247a91c9b52a9ebf32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2af21aecb00e89e2003174960bdce08c42851cfd                         | Address of the contract that produced the log                |
| newTickSpacing    | VARCHAR   | 1                                                                  |                                                              |

## 18. Table: CamelotFactory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-21 05:39:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 62995200                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf87d93fc12bd607551cb6342572cbdd1b6bd92cab7adc50c3790ce4baaab2965 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6eccab422d763ac031210895c81787e87b43a652                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x50f27afb3c5ec089f26c63e72bc97898dafe2907                         |                                                              |
| token1            | VARCHAR   | 0x82af49447d8a07e3bd95bd0d56f35241523fbab1                         |                                                              |
| pair              | VARCHAR   | 0x2ec11f0690c6c948a6ecab91df04e5a3869f9951                         |                                                              |
| length            | VARCHAR   | 206                                                                |                                                              |

## 19. Table: CamelotPair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-11 00:10:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 59838728                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3429e6585f0a06d8e63e8c1fae82b836e45c625741592d004687ca6bff21fccc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x035d9815ae5af78d568721fa118bb93428c91f51                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xe458018ad4283c90fb7f5460e24c4016f81b8175                         |                                                              |
| spender           | VARCHAR   | 0x0f07c3d5dcadc6194a5ec2f9c4106ff5b0db3c18                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 20. Table: CamelotPair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-28 09:41:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 74521395                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x91d1bf4fd95133d6ba570fc20067c95e214b46d3e5623361a301f3e17a1ef10a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1c31fb3359357f6436565ccb3e982bc6bf4189ae                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc873fecbd354f5a56e00e710b90ef4201db2448d                         |                                                              |
| amount0           | VARCHAR   | 944962223                                                          |                                                              |
| amount1           | VARCHAR   | 1049226312                                                         |                                                              |
| to                | VARCHAR   | 0x8e7e0f86469a8aa52a773d5685a9d5d733df62fd                         |                                                              |

## 21. Table: CamelotPair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-13 00:56:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 52667373                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa1b1523aceb21805d7a0b5e1ab7f11ccbab77ea54f8f3773df8f2e482964c6fe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x74656efe9b164d82d0bc32b6cf6888f3f22f871f                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc873fecbd354f5a56e00e710b90ef4201db2448d                         |                                                              |
| amount0           | VARCHAR   | 93655593355821849077                                               |                                                              |
| amount1           | VARCHAR   | 4927982                                                            |                                                              |

## 22. Table: CamelotPair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 00:45:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 118560100                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0236bf40c0868684e89ba7d156179b5955bc22eef7c51c808386b55c0dfc9f10 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01efed58b534d7a7464359a6f8d14d986125816b                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc873fecbd354f5a56e00e710b90ef4201db2448d                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 681799                                                             |                                                              |
| amount0Out        | VARCHAR   | 681649303270603233                                                 |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x06cb331c76e74e6a6524581761132aa9520609a8                         |                                                              |

## 23. Table: CamelotPair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-04 15:18:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43572754                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4b3c9dc2cf35bd242269a8d816a3d8516b9efc601269890a872d1d558192705 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01efed58b534d7a7464359a6f8d14d986125816b                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 979897867855541306075495                                           |                                                              |
| reserve1          | VARCHAR   | 1073296939595                                                      |                                                              |

## 24. Table: CamelotPair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 10:51:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 116398358                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe44da6489a4a61c5c9ada35c16f7ab3ec1207ea6d401421f49b237301197715e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x01efed58b534d7a7464359a6f8d14d986125816b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xe458018ad4283c90fb7f5460e24c4016f81b8175                         |                                                              |
| value             | VARCHAR   | 52816476274328545                                                  |                                                              |
