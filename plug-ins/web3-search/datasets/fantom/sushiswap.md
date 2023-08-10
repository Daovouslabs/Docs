# sushiswap

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 02:11:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29935079                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbdba7907dcba7e1f7d3b9f6382f9d9c401f19bd7b9a25d702546ed2e1ae2980d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc35dadb65012ec5796536bd9864ed8773abc74c4                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x21be370d5312f44cb42ce377bc9b8a0cef1a4c83                         |                                                              |
| token1            | VARCHAR   | 0x504d321a9f3586f5e78fbe3476ed10110bf39412                         |                                                              |
| pair              | VARCHAR   | 0x94f251e8688f4083a1a462458e95c7b58188c014                         |                                                              |
| \_uint            | VARCHAR   | 1053                                                               |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-08 21:49:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 59433184                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbd558f44ed6ba77177708b6313fce7d5c77268d2140ec7ee89d5c7a1a979a262 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ca86e57103564f47ffcea7259a6ce8cc1301549                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc92fbccadb15876ad8a95b8971ca409377c4caf8                         |                                                              |
| spender           | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| value             | VARCHAR   | 3187970836285866621443                                             |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-28 07:50:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34602529                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa491561fa2f1211e40f88202f2e78f57cf63413c4a81d37ca23acd14b00d5e7f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d0bd54c48c2c433ea6fed609cc3d5fb7a77622b                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0           | VARCHAR   | 12647518218417653229                                               |                                                              |
| amount1           | VARCHAR   | 5549266373755272                                                   |                                                              |
| to                | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 11:23:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45230584                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e70ac5965acd44079ee54b5ee6c66a0433eb59a6b78fe99a6e90450e226bbad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa9ce31b75ae5ba31e451c1792c4f33127e1c97e3                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0           | VARCHAR   | 5000000000000000000                                                |                                                              |
| amount1           | VARCHAR   | 16000000000000000000                                               |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-03 15:35:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16255172                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x167a07deccd73f575d9a7d46ef67485b11049c40b08bb3f22f48f14424ee33eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0103715fd20a3f2e11fd7b3e646a5f6f6703d245                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x7efc47d92c90908ef3d82bc52e71235fef23cc02                         |                                                              |
| amount0In         | VARCHAR   | 268938437651320                                                    |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 1257070221031019725                                                |                                                              |
| to                | VARCHAR   | 0x34bf23e2f08bfe00cae2adc15d4b47cf8b9ee7bf                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 18:51:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22439859                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdfcd90b906531fb20300fd18fd78a5c438b896afed1b81653f2a8434608441f4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbfa5bd514eb78113508fd3955258ce07f56ff9c9                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 50544370                                                           |                                                              |
| reserve1          | VARCHAR   | 519                                                                |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 11:50:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23182744                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65b388cbb1475861b1f4cbc02daf369807172885cc6c4a6305497751d83dc22a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0dcb7f634b87b3a40750ef3c5e47b5e42e473104                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x8a6bb58fbafd782d45ca6572d2a0bff4ae17f21e                         |                                                              |
| value             | VARCHAR   | 71021574496638607162                                               |                                                              |
