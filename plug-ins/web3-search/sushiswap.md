# sushiswap

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 16:06:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36053941                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfdc63f303a128680e684f01e501b701855e97ee19e260ab4695ef135695cf643 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc35dadb65012ec5796536bd9864ed8773abc74c4                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x41bb16c88687a633cf236c8a79a4d38f8f7344fa                         |                                                              |
| token1            | VARCHAR   | 0x82af49447d8a07e3bd95bd0d56f35241523fbab1                         |                                                              |
| pair              | VARCHAR   | 0xd3652a4aa9837cb91194115ac6674cdbef2e05e7                         |                                                              |
| \_uint            | VARCHAR   | 1599                                                               |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 12:28:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32198983                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4494f7e5c8e50a7b3f1c151dde928a6c79918a5696cd78b62e233543b8786f1a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x905dfcd5649217c42684f23958568e533c711aa3                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x39bda5095ed65f1ad5b9d6ece617ca0ec09f6c33                         |                                                              |
| spender           | VARCHAR   | 0x07db98358d58ba9be90cd0a18cd86af807ac3b4e                         |                                                              |
| value             | VARCHAR   | 8000000000000000000000000000                                       |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 18:06:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 98791976                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b788ffa9806f1bb6989961f6f71a7124a4e4d0dd6c0d16e3182ccebafc58553 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x62fefb4e0e2e226fbd9bdcfc2ec33c8bcc998efc                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0           | VARCHAR   | 999620059290579497818219225                                        |                                                              |
| amount1           | VARCHAR   | 2003468281851887                                                   |                                                              |
| to                | VARCHAR   | 0x05ebfc78af161f72b7a129e710c3527ab1c1c954                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-14 09:03:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30040487                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1fb416ccefa3d69330e405d15688a930b80ad61d59e0c2244939bbfbb98c4d0d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x037a2f2b12ec405849a35542e3944dbdbb44c519                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0           | VARCHAR   | 139232024014580                                                    |                                                              |
| amount1           | VARCHAR   | 999999999999999999                                                 |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 04:16:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 109994186                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb751e1c486285d5a65e6c601695c589ba2807835568b3bd8e2b61dc38ef0bcae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00f958f6e68a260459ab45fcefd73b1b12c06666                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 66000000000000000                                                  |                                                              |
| amount0Out        | VARCHAR   | 24251731250127335399993                                            |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x0f64a0b638ddad96a497b06ebc777b49e4ca640e                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-29 05:44:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 116006545                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b86bf3e9d5c1417478aade0fbe5ed81a07f8e78d4cf8a1810392f57975b703e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57b85fef094e10b5eecdf350af688299e9553378                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 32846312019935572                                                  |                                                              |
| reserve1          | VARCHAR   | 60077534                                                           |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-19 04:42:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 92162917                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1138186f82ce4039919bb342749bd9c855cc16a59af55b2d15ba78d3244ede07 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00468cd187492080c66a96f28581881fc306f851                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa5b87370a79e1a38871a3779ed91581ae735211a                         |                                                              |
| to                | VARCHAR   | 0x1b1eb8ccc251deb3abd971b12bd8f34ac2a9a608                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |
