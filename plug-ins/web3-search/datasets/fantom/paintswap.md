# paintswap

## 1. Table: PaintFactory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-13 19:02:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11998228                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3612f95af59ccd64ca99d6ea36bd048a457e7010beade3890f46bdd3b1fbf79 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x733a9d1585f2d14c77b49d39bc7d7dd14cda4aa5                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x7ec94c4327dc757601b4273cd67014d7760be97e                         |                                                              |
| token1            | VARCHAR   | 0xcce93540b80abf71b66e0a44fd71e322ce9c4d9e                         |                                                              |
| pair              | VARCHAR   | 0x6680b936216e770605e43e7214e5838e2803f514                         |                                                              |
| anonymous         | VARCHAR   | 89                                                                 |                                                              |
