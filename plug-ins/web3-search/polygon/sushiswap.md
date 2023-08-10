# sushiswap

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-19 11:38:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17032139                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6bb29939fef2fb875bf66d2988d5411d0bfa147e906d33e96a37e1d8ab6187e3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 333                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc35dadb65012ec5796536bd9864ed8773abc74c4                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x049f12f5a27132d06de128d48a914f6d82d33d23                         |                                                              |
| token1            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| pair              | VARCHAR   | 0x82fffb9ea753dc701920558f61c04da824b24578                         |                                                              |
| \_uint            | VARCHAR   | 1652                                                               |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 06:48:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44900877                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90c81d386a556b1012c8557b72ac1b5e339e562bae05a24a72b76e1d6af8bc34 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 172                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4b1f1e2435a9c96f7330faea190ef6a7c8d70001                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x6b1dba4494147bbfcf3575bbf509b8000d31fecb                         |                                                              |
| spender           | VARCHAR   | 0x0000000000000000000000000000000000000001                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 05:41:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19161044                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb37b3831a76268f97613e19be0684c0c1190482ea25bdd44de53a79a698ac4ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 551                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x095fc71521668d5bcc0fc3e3a9848e8911af21d9                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0           | VARCHAR   | 13210443422123044950267                                            |                                                              |
| amount1           | VARCHAR   | 16954477063084232664                                               |                                                              |
| to                | VARCHAR   | 0x2f5e08ef5a99a98336519e54f58d503f550bd9ac                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 11:52:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45897697                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65dac8aceadfec48985988b6ae97ba6d03c303cac45b0555c5c9281390eb6113 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 360                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x014ac2a53aa6fba4dcd93fde6d3c787b79a1a6e6                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0           | VARCHAR   | 44000000000000000000                                               |                                                              |
| amount1           | VARCHAR   | 117852014064882824402                                              |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-07 05:54:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34032897                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x75687d7a43132acb247eb39c557e9455aba588f86df738a482e922d2cf11adba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcbf6f78981e63ef813cb71852d72a060b583eecf                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0In         | VARCHAR   | 2320515638919912                                                   |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 10463575575520466                                                  |                                                              |
| to                | VARCHAR   | 0x000000000000000000000000000000000000dead                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 15:59:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42579886                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x463922dc27ab7302417df4561a011e4b9efbda87d8481b1cee89c1276eacfd59 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa34ec05da1e4287fa351c74469189345990a3f0c                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 790358225055                                                       |                                                              |
| reserve1          | VARCHAR   | 1262708274624277396718782                                          |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-29 14:33:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42100600                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3afbcaf5a8f94629418935971adf2f969bd2cc0b4b4a3a3d09d03ec4c3debc30 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x014ac2a53aa6fba4dcd93fde6d3c787b79a1a6e6                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xd7c015290cca4fbd43580ff61667cc0761774758                         |                                                              |
| value             | VARCHAR   | 3569690855340285927238                                             |                                                              |
