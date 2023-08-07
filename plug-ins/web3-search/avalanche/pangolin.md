# pangolin

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-26 22:17:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10098165                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05a2e64f7ed92d61e030ecc4ba118ff472de7bd35206266ab2628a02a564f52d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefa94de7a4656d787667c749f7e1223d71e9fd88                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x2130347de53a6c7fc6a036d2308f5c033852df37                         |                                                              |
| token1            | VARCHAR   | 0x60781c2586d68229fde47564546784ab3faca982                         |                                                              |
| pair              | VARCHAR   | 0x05ec0de00f1cb02e908c9eee1a6ede0443202bb8                         |                                                              |
| \_uint            | VARCHAR   | 2590                                                               |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-29 05:13:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33214565                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab73284a61e545bd6b05696ddf7f3c51fb9cca4b67cc61827b9203877b1b092f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5a615108e682d71e9726c7c1567f7df968f54ba0                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x9d204ca4725c2061e14602e3439942b2bef57239                         |                                                              |
| spender           | VARCHAR   | 0x02941a0ffa0bb0e41d9d96314488d2e7652edea6                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 06:16:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31858509                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x295816316a4eae75915df5951831dcaa75182b76117ccd016724ae9972e2c476 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8461681211b49c15e20b3cfd4c63be258878b7d9                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x7f62af30081178f502c3d4da17825e58d240d737                         |                                                              |
| amount0           | VARCHAR   | 523823800490430652955                                              |                                                              |
| amount1           | VARCHAR   | 1011666568983566022                                                |                                                              |
| to                | VARCHAR   | 0x7f62af30081178f502c3d4da17825e58d240d737                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 00:00:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29308527                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9446a5c23ee74bd7fe651323505d30f6b88f159d278af9fc906ae2ec5c55fe55 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc013f541f55461cc039bcdba9c4dc3bdded6c828                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0d84f6d810d1aacd2e6526e642f9ad78844d7da1                         |                                                              |
| amount0           | VARCHAR   | 189091762219983342332                                              |                                                              |
| amount1           | VARCHAR   | 173869738581341284                                                 |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-11 01:38:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27279369                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x62c410184793ebee2d056310b3f5efa10cbd650fcc7e38436d383d6388499f5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9d86243ae7008ec1f9cce83c49d76f7a557b80cf                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x55f2018be367388056fa90cb6dc170508e2cfca1                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 314135864                                                          |                                                              |
| amount0Out        | VARCHAR   | 1514850                                                            |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x000000c0f624da031e44661f23c2e5bdacc6dcf4                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-03 17:05:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 935759                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ccf71f311e2878041e9ca535b06c145305410566c1b04cedecc466e7a7013be | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0025cebd8289bbe0a51a5c85464da68cbc2ec0c4                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 13264645795757185377821                                            |                                                              |
| reserve1          | VARCHAR   | 73956250630752618333                                               |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 09:27:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30553135                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d4e2eea044f773b435b6ab2b17db3c167e329669eb629c29adb91713e1fab12 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e0100ab771e9288e0aa97e11557e6654c3a9665                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3f2918f1099d85ac89d6bb54016129eb4d56577f                         |                                                              |
| to                | VARCHAR   | 0x1f806f7c8ded893fd3cae279191ad7aa3798e928                         |                                                              |
| value             | VARCHAR   | 28197680988766                                                     |                                                              |
