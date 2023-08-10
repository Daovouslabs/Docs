# biswap

## 1. Table: BiswapFactory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 17:57:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21445931                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x062b6eb395397251220c732b86f0546aab6525fcf03b882e39c159333a95e767 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x858e3312ed3a876947ea49d572a7c42de08af7ee                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         |                                                              |
| token1            | VARCHAR   | 0xf9401ac58a7e19ae12ba6b6ae8b71bb00f295171                         |                                                              |
| pair              | VARCHAR   | 0x1cd799235fe6d65e3217bbfcff948bf54733a493                         |                                                              |
| \_uint            | VARCHAR   | 1980                                                               |                                                              |

## 2. Table: BiswapPair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 23:45:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29366069                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7868502305137c8a9c483a22eab6aa6a8f3a732cf585818f444503a1e53b041d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x46492b26639df0cda9b2769429845cb991591e0a                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x044602764810dec578eb00a05b18e7c4de13cf01                         |                                                              |
| spender           | VARCHAR   | 0x15e0e37e72d52d399d57296487808379f48df91c                         |                                                              |
| value             | VARCHAR   | 900000000000000000000000000                                        |                                                              |

## 3. Table: BiswapPair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-16 16:07:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24840234                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc64b5981a6bd749b1964fe8512710966f082cdabbabe6ea3d769168a83add270 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b30c317cedfb554ec525f85e79538d59970beb0                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x3a6d8ca21d1cf76f653a67577fa0d27453350dd8                         |                                                              |
| amount0           | VARCHAR   | 59345462239738237                                                  |                                                              |
| amount1           | VARCHAR   | 312333753719059976                                                 |                                                              |
| to                | VARCHAR   | 0x04f2ddf4fa327323202a9b8714a173d7af0fe6a0                         |                                                              |

## 4. Table: BiswapPair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 17:23:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20353567                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb09ff89943241218c9ab3cfb035a497b8765cb4a7aa9f92b181cfb83cb4bcd80 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 301                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06cd679121ec37b0a2fd673d4976b09d81791856                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x3a6d8ca21d1cf76f653a67577fa0d27453350dd8                         |                                                              |
| amount0           | VARCHAR   | 250000000000000000000                                              |                                                              |
| amount1           | VARCHAR   | 764534205603543296                                                 |                                                              |

## 5. Table: BiswapPair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 13:23:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21411892                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba710490ec867d98697e7d4a1b4a9e7411a0ba17232366e8001ade1fdeab0c9a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 289                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfbbd096a99e95d6808b918a5c0863ed9989ebd41                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000008afdacc486225455281f614843e7                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 22013090059124824173687                                            |                                                              |
| amount0Out        | VARCHAR   | 467023757869553252                                                 |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x0000000000008afdacc486225455281f614843e7                         |                                                              |

## 6. Table: BiswapPair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 13:54:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29469207                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa10852003e7379ef59fc31608bb609018f9b3280ca29bf3d75ddb00b96297d60 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 359                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x03fd46c8ce0232ab21d4198e149c2990abb9bc38                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 11681853489858982094814                                            |                                                              |
| reserve1          | VARCHAR   | 557550180928538595401                                              |                                                              |

## 7. Table: BiswapPair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-02 12:46:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27858413                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7d335e530aed392ce391142d96fee5354886bfb514f4b68abb31d740b1f55ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 575                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06cd679121ec37b0a2fd673d4976b09d81791856                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x612e072e433a8a08496ee0714930b357426c12ce                         |                                                              |
| value             | VARCHAR   | 168638527889712340                                                 |                                                              |
