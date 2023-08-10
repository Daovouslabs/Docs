# clipper

## 1. Table: ClipperCaravelExchange\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-23 09:22:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15198092                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b16fc6a2c4a1b713861d4a9936cfe87c7398a2064cccc8d50e958f06188ee25 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc12532e95c2a6a4c53af153b9b739a3cc9218a7                         | Address of the contract that produced the log                |
| inAsset           | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| outAsset          | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| recipient         | VARCHAR   | 0xaa9b6cf6fd0d96e6d3555be923014cd026608c8c                         |                                                              |
| inAmount          | VARCHAR   | 127380                                                             |                                                              |
| outAmount         | VARCHAR   | 28758412                                                           |                                                              |
| auxiliaryData     | VARCHAR   | 0x436c697070657200000000000000000000000000000000000000000000000000 |                                                              |

## 2. Table: ClipperExchangeInterface\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-19 14:10:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14615951                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe71edfbb129545959d6507924d68ccbba09a07e2a4ee3b31867c5a9e954be7d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e9c6dcdca22a5952a88c4b18edb5b54c5155bc9                         | Address of the contract that produced the log                |
| inAsset           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| outAsset          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| recipient         | VARCHAR   | 0x220bda5c8994804ac96ebe4df184d25e5c2196d4                         |                                                              |
| inAmount          | VARCHAR   | 3000000000                                                         |                                                              |
| outAmount         | VARCHAR   | 965472154517928098                                                 |                                                              |
| auxiliaryData     | VARCHAR   | 0x31494e4348000000000000000000000000000000000000000000000000000000 |                                                              |

## 3. Table: ClipperVerifiedCaravelExchange\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 11:08:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16139596                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf01a5805d0317c54b49e1229125d136266dbe9b61bdfe8c317fc7330b99c193b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 197                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7b0ce0526fbe3969035a145c9e9691d4d9d216c                         | Address of the contract that produced the log                |
| inAsset           | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| outAsset          | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| recipient         | VARCHAR   | 0xffff3b186df95a1272b404d1c8715ac210f00311                         |                                                              |
| inAmount          | VARCHAR   | 1000000000                                                         |                                                              |
| outAmount         | VARCHAR   | 810967524805469184                                                 |                                                              |
| auxiliaryData     | VARCHAR   | 0x31494e4348                                                       |                                                              |
