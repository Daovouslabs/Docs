# multichain

## 1. Table: AnyswapV4Router\_event\_LogAnySwapIn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-28 01:33:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17141389                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x778fa2f85efe0b1ccf0ce234d2ef823c6c7d6b202a807e29db7f7500e0d4e127 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 101                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b7a87899490ece95443e979ca9485cbe7e71522                         | Address of the contract that produced the log                |
| txhash            | VARCHAR   | 0xfd60d4bd14b2c09d17dbfca691c53571b740b0153d381dd0f272eddb1e0e1029 |                                                              |
| token             | VARCHAR   | 0x22648c12acd87912ea1710357b1302c6a4154ebc                         |                                                              |
| to                | VARCHAR   | 0x9a3bf39506de3fd281cebbab9dd52fbab37e696a                         |                                                              |
| amount            | VARCHAR   | 47990172234                                                        |                                                              |
| fromChainID       | VARCHAR   | 10                                                                 |                                                              |
| toChainID         | VARCHAR   | 1                                                                  |                                                              |

## 2. Table: AnyswapV4Router\_event\_LogAnySwapOut\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 21:03:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17665803                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe90aebaa0c0ae6d5e820bee7c67a1023bffc1816f462b5a6dd87a3a40896c3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 502                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b7a87899490ece95443e979ca9485cbe7e71522                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x22648c12acd87912ea1710357b1302c6a4154ebc                         |                                                              |
| from              | VARCHAR   | 0x7acbec12e34c7d3ebd3406e4a00884437486f9b6                         |                                                              |
| to                | VARCHAR   | 0x7acbec12e34c7d3ebd3406e4a00884437486f9b6                         |                                                              |
| amount            | VARCHAR   | 400000000                                                          |                                                              |
| fromChainID       | VARCHAR   | 1                                                                  |                                                              |
| toChainID         | VARCHAR   | 43114                                                              |                                                              |

## 3. Table: AnyswapV4Router\_event\_LogAnySwapTradeTokensForNative\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| path              | VARCHAR   |                                                              |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amountIn          | VARCHAR   |                                                              |             |
| amountOutMin      | VARCHAR   |                                                              |             |
| fromChainID       | VARCHAR   |                                                              |             |
| toChainID         | VARCHAR   |                                                              |             |

## 4. Table: AnyswapV4Router\_event\_LogAnySwapTradeTokensForTokens\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| path              | VARCHAR   |                                                              |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amountIn          | VARCHAR   |                                                              |             |
| amountOutMin      | VARCHAR   |                                                              |             |
| fromChainID       | VARCHAR   |                                                              |             |
| toChainID         | VARCHAR   |                                                              |             |

## 5. Table: AnyswapV4Router\_event\_LogChangeMPC\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-11 14:56:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12806663                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65651a6ba929fcb12ddcacd9a92fc131e1893dd0d0787f3c7cc787e4dad91ec6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b7a87899490ece95443e979ca9485cbe7e71522                         | Address of the contract that produced the log                |
| oldMPC            | VARCHAR   | 0x8b44a687224496276811555efa3f2d0acd667a72                         |                                                              |
| newMPC            | VARCHAR   | 0x2a038e100f8b85df21e4d44121bdbfe0c288a869                         |                                                              |
| effectiveTime     | VARCHAR   | 1626188176                                                         |                                                              |
| chainID           | VARCHAR   | 1                                                                  |                                                              |

## 6. Table: AnyswapV4Router\_event\_LogChangeRouter\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldRouter         | VARCHAR   |                                                              |             |
| newRouter         | VARCHAR   |                                                              |             |
| chainID           | VARCHAR   |                                                              |             |

## 7. Table: AnyswapV6Router\_event\_LogAnySwapIn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-18 11:09:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17286043                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd628ac39b096901c114a0a707327f121cb4d933af64d28334c4b41812e4da2a5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 273                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba8da9dcf11b50b03fd5284f164ef5cdef910705                         | Address of the contract that produced the log                |
| txhash            | VARCHAR   | 0x5e2b4ddc6a38cea3b98445a2dfea6251ac869a0a5147e2c3c3db9edc477babf6 |                                                              |
| token             | VARCHAR   | 0x0615dbba33fe61a31c7ed131bda6655ed76748b1                         |                                                              |
| to                | VARCHAR   | 0x4eb62e5e90a2a7e3dd081ffc31ef6f4c4e5964b1                         |                                                              |
| amount            | VARCHAR   | 21373000000000000000                                               |                                                              |
| fromChainID       | VARCHAR   | 10                                                                 |                                                              |
| toChainID         | VARCHAR   | 1                                                                  |                                                              |

## 8. Table: AnyswapV6Router\_event\_LogAnySwapOut\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 14:42:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17429159                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e888b4d5cc3f1a3dd799bc2697e09b08b04f80d108dbd79d4286f616aff2a5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 278                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba8da9dcf11b50b03fd5284f164ef5cdef910705                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0615dbba33fe61a31c7ed131bda6655ed76748b1                         |                                                              |
| from              | VARCHAR   | 0x0cdc8f4815910b7e7527676d8ae9b8d09b46883d                         |                                                              |
| to                | VARCHAR   | 0xD2453c80d962BAe6d3810243123085Cb60519cf0                         |                                                              |
| amount            | VARCHAR   | 10000000000000000                                                  |                                                              |
| fromChainID       | VARCHAR   | 1                                                                  |                                                              |
| toChainID         | VARCHAR   | 137                                                                |                                                              |

## 9. Table: AnyswapV6Router\_event\_LogAnySwapTradeTokensForNative\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| path              | VARCHAR   |                                                              |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amountIn          | VARCHAR   |                                                              |             |
| amountOutMin      | VARCHAR   |                                                              |             |
| fromChainID       | VARCHAR   |                                                              |             |
| toChainID         | VARCHAR   |                                                              |             |

## 10. Table: AnyswapV6Router\_event\_LogAnySwapTradeTokensForTokens\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| path              | VARCHAR   |                                                              |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amountIn          | VARCHAR   |                                                              |             |
| amountOutMin      | VARCHAR   |                                                              |             |
| fromChainID       | VARCHAR   |                                                              |             |
| toChainID         | VARCHAR   |                                                              |             |
