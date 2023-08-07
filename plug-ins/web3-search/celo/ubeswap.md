# ubeswap

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-13 15:36:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11437593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c3fbed3b7816827585c9963484751200b761e9fc8648e07b1c458147546adee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x62d5b84be28a183abb507e125b384122d2c25fae                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x301a61d01a63c8d670c2b8a43f37d12ef181f997                         |                                                              |
| token1            | VARCHAR   | 0x73a210637f6f6b7005512677ba6b3c96bb4aa44b                         |                                                              |
| pair              | VARCHAR   | 0xe86b220dbbaee12f4888ed2647e7c0e50830b055                         |                                                              |
| \_uint            | VARCHAR   | 548                                                                |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 18:46:32+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6895629                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80811f653f1aa13629026e3031c079766cc6e02fb6512dc906c4fbb5e1c9e195             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x27616d3dba43f55279726c422daf644bc60128a8                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x777bf6c85f3916c5ee3d12343acdfabf18392d64                                     |                                                              |
| spender           | VARCHAR   | 0xaf13437122cd537c5d8942f17787cbdbd787fe94                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-24 18:37:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17383482                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6023bdb330aeffa5cee12294a1f2f0400d57322a47ee830a60dddf8bc1d63215 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0448e99ab5f8230713a9f5d7e64ec2ab6e5952a3                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xe3d8bd6aed4f159bc8000a9cd47cffdb95f96121                         |                                                              |
| amount0           | VARCHAR   | 1262914884304881286897                                             |                                                              |
| amount1           | VARCHAR   | 5643057                                                            |                                                              |
| to                | VARCHAR   | 0x28bacb0151f3b934ea22e55a23b97709d0cb615c                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 23:30:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19598793                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf623fcdfa61def27120bfe43aa54fa1a1bd8de029c427b81023c28338482acf2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0b81cf47c8f97275d14c006e537d5101b6c87300                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xe3d8bd6aed4f159bc8000a9cd47cffdb95f96121                         |                                                              |
| amount0           | VARCHAR   | 5887390000000000000                                                |                                                              |
| amount1           | VARCHAR   | 142396013486323793763558                                           |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-01 06:14:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16977128                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb03e4918e08e6db9ede15b44ada5fc69f0feaa937ce77e79d2cd0da260548784 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb460f9ae1fea4f77107146c1960bb1c978118816                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1a1fb7fa51eb6d20cd3c714663ac25e553d3a6b4                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 732262157683727                                                    |                                                              |
| amount0Out        | VARCHAR   | 1560590047967709                                                   |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x77778f85137689747fbc7eb600d71f4eb79318a1                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-07 01:55:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8144896                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc97c35ba6f32599e8190a897389e982c6e81566bbde484172f14b1af6d38e1c4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x58fff7110e39c733fd37742b8850f9205fbc351b                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 4517209504956103375465458655                                       |                                                              |
| reserve1          | VARCHAR   | 68708933500430636046569                                            |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 02:04:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20551015                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82af89cd624556da5deaa43d15428109870b6ad84f84a20a41ccafa80d3e45c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e593f1fe7b61c53874b54ec0c59fd0d5eb8621e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xebf6caf61daf53dc92b6a9b030cf642fd4c1103c                         |                                                              |
| to                | VARCHAR   | 0x1e593f1fe7b61c53874b54ec0c59fd0d5eb8621e                         |                                                              |
| value             | VARCHAR   | 1422186980501431372                                                |                                                              |
