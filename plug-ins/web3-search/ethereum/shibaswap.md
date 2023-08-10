# shibaswap

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-15 15:24:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13030571                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca1600b3ea801041db3f90795934f1e36d8ff29334c85a3763f4dfd53d594c8f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x115934131916c8b277dd010ee02de363c09d037c                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x95f49ae439537e50ced0374c1b52c42aa899741c                         |                                                              |
| token1            | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| pair              | VARCHAR   | 0x1f58ab9eea614b40a54d5765d871ed4a25b653e0                         |                                                              |
| unnamedField0     | VARCHAR   | 275                                                                |                                                              |

## 2. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 09:13:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16903512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf62dd0997f198bc1b4b654e9323c5e9c6b638d48b210bc586a3aa35f46ea2aaf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x024344da138b76ff2f5ce2386abdb4c97659b181                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x9227a2d1be29de19ce9cb66db6f176b76920bba1                         |                                                              |
| amount0In         | VARCHAR   | 129366632638186030972912018                                        |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 4142673850662909687188795                                          |                                                              |
| to                | VARCHAR   | 0x773dd321873fe70553acc295b1b49a104d968cc8                         |                                                              |
