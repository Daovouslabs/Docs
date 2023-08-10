# spiritswap

## 1. Table: PancakePair\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-02 22:02:18+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8672240                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2532f780eafe151a6685fa9c357879c7d789c886c1c0d768e2833baae7eb2208             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xca78e7c058951d1e50ee74b8e9fbb4c9523e9e5a                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0097b628ff756496f7aa95401b333aae0c61f961                                     |                                                              |
| spender           | VARCHAR   | 0x28e1a7fc0e9aa9eed933282fafbab1297aa81ab5                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: PancakePair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-26 05:57:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43568008                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae19eaa7e294460648a28eaf0b8a6ec5f3f6446d9f626fe0edf429b60abb352e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0133660d0578bf9d085033ea753a27f5aa2b9de1                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x16327e3fbdaca3bcf7e38f5af2599d2ddc33ae52                         |                                                              |
| amount0           | VARCHAR   | 4740491486008500326                                                |                                                              |
| amount1           | VARCHAR   | 179665511613879                                                    |                                                              |
| to                | VARCHAR   | 0x16327e3fbdaca3bcf7e38f5af2599d2ddc33ae52                         |                                                              |

## 3. Table: PancakePair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 18:30:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 66293185                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ee0c685379e9989c8e94a2b319ff836bd209bb3fb7865a87717f3052dd548a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1e886febc93a5ad833e683d044c6b08d622af8a7                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x16327e3fbdaca3bcf7e38f5af2599d2ddc33ae52                         |                                                              |
| amount0           | VARCHAR   | 74697856662823522654                                               |                                                              |
| amount1           | VARCHAR   | 9636715765769932027                                                |                                                              |

## 4. Table: PancakePair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-29 18:07:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 63295269                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9ff80d853e4b9b3b1b619c34a55bf0eeb983f58c8f12e73d8e27223ad8096a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7e90f5a767406eff87fdad7eb07ef407922ec1d                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0f8004045ffae25b06b3aa16148ff438341da989                         |                                                              |
| amount0In         | VARCHAR   | 200000000                                                          |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 594697861535499951420                                              |                                                              |
| to                | VARCHAR   | 0x00b542676b68f68b820ae5c18b6e183ab7f64dde                         |                                                              |

## 5. Table: PancakePair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-22 23:11:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 47516409                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb4f727ebf5458845fce6583e0a179de120568889f2b3e471767c75b70f5c2e68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8cb1c60b27c93dcc9e9310fadd94cd8b3013b1eb                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 887664636                                                          |                                                              |
| reserve1          | VARCHAR   | 46177104139278545880                                               |                                                              |

## 6. Table: PancakePair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-13 14:19:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 55705701                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0209414cfbbd58e1480135da05244b5ae6d16f6992c7dc8d233238f2026d8e60 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ec0e1629e776272fa3e55548d4a656be0eedcf4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x48ba4c352d2486d0803f08ca11e35fc4c5ccb007                         |                                                              |
| to                | VARCHAR   | 0x9083ea3756bde6ee6f27a6e996806fbd37f6f093                         |                                                              |
| value             | VARCHAR   | 18583615061782219771                                               |                                                              |

## 7. Table: SpiritFactory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 13:04:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 47192976                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x49f5f4ccc3cf23742d7e87116c1df0c3c70a4e23de7435e3db5a1dff108d765b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xef45d134b73241eda7703fa787148d9c9f4950b0                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x21be370d5312f44cb42ce377bc9b8a0cef1a4c83                         |                                                              |
| token1            | VARCHAR   | 0xfbcf7535dc3f04a622091e97d79697f23ef7f236                         |                                                              |
| pair              | VARCHAR   | 0xe0aec40405acdacbd81d8271abba5d26f493ed16                         |                                                              |
| \_uint            | VARCHAR   | 2190                                                               |                                                              |
