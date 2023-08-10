# multichain

## 1. Table: AnyswapV4Router2\_event\_LogAnySwapIn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-06 10:58:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35373410                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x50a956eea333faac51d66d99072d3ea3633e38305e358052cfe8fe7a467946dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ccca1ce62c62f7be95d4a67722a8fdbed6eecb4                         | Address of the contract that produced the log                |
| txhash            | VARCHAR   | 0x1bdc738562517b7a3d7dc7cab20f22c896d2b71ca7d67ab1ea797624c20f7c99 |                                                              |
| token             | VARCHAR   | 0x95bf7e307bc1ab0ba38ae10fc27084bc36fcd605                         |                                                              |
| to                | VARCHAR   | 0x321614602ff49b672287e670ee361ab94865ebcb                         |                                                              |
| amount            | VARCHAR   | 1262015030                                                         |                                                              |
| fromChainID       | VARCHAR   | 1                                                                  |                                                              |
| toChainID         | VARCHAR   | 250                                                                |                                                              |

## 2. Table: AnyswapV4Router2\_event\_LogAnySwapOut\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-01 16:50:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 61228062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa6ab75dedfa2ff0ac8229ec264fe69f134681b89482b487da1bb63d7931b9f7c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ccca1ce62c62f7be95d4a67722a8fdbed6eecb4                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x2406dce4da5ab125a18295f4fb9fd36a0f7879a2                         |                                                              |
| from              | VARCHAR   | 0xc45d05cdc809d20c7b14959e8cd4a1199e3e966f                         |                                                              |
| to                | VARCHAR   | 0xc45d05cdc809d20c7b14959e8cd4a1199e3e966f                         |                                                              |
| amount            | VARCHAR   | 12946700                                                           |                                                              |
| fromChainID       | VARCHAR   | 250                                                                |                                                              |
| toChainID         | VARCHAR   | 10                                                                 |                                                              |

## 3. Table: AnyswapV4Router2\_event\_LogAnySwapTradeTokensForNative\_history

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

## 4. Table: AnyswapV4Router2\_event\_LogAnySwapTradeTokensForTokens\_history

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

## 5. Table: AnyswapV4Router2\_event\_LogChangeMPC\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-11 14:52:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11825326                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdc0105ac05db2e690e28794f0275c5fba5a93e79bb5d774f718548c93bf8c393 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ccca1ce62c62f7be95d4a67722a8fdbed6eecb4                         | Address of the contract that produced the log                |
| oldMPC            | VARCHAR   | 0x8b44a687224496276811555efa3f2d0acd667a72                         |                                                              |
| newMPC            | VARCHAR   | 0x2a038e100f8b85df21e4d44121bdbfe0c288a869                         |                                                              |
| effectiveTime     | VARCHAR   | 1626187932                                                         |                                                              |
| chainID           | VARCHAR   | 250                                                                |                                                              |

## 6. Table: AnyswapV4Router2\_event\_LogChangeRouter\_history

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

## 7. Table: AnyswapV4Router\_event\_LogAnySwapIn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-20 09:45:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19578374                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0c74d4247eb9fbb5f62a457604d801f355fe7527100c1237c4f6bdf2843c52b2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb576c9403f39829565bd6051695e2ac7ecf850e2                         | Address of the contract that produced the log                |
| txhash            | VARCHAR   | 0x515e196d79cf2c7fbfc408e5eec5901be18652a598a1daebf6f56bdd4a9f16df |                                                              |
| token             | VARCHAR   | 0x468003b688943977e6130f4f68f23aad939a1040                         |                                                              |
| to                | VARCHAR   | 0xd976cb5e971a349e6633e4e84aeb28120ca7bb1c                         |                                                              |
| amount            | VARCHAR   | 9733200000000000000000                                             |                                                              |
| fromChainID       | VARCHAR   | 1                                                                  |                                                              |
| toChainID         | VARCHAR   | 250                                                                |                                                              |

## 8. Table: AnyswapV4Router\_event\_LogAnySwapOut\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 07:38:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 53317735                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x900f57caa8ef493d153bd4a30b240cc0a292b1df2f60d62ad0ad45c2ae9212ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb576c9403f39829565bd6051695e2ac7ecf850e2                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x5a33869045db8a6a16c9f351293501cfd92cf7ed                         |                                                              |
| from              | VARCHAR   | 0xc982b9495667bc2f2018efab5969a395fe8bbe89                         |                                                              |
| to                | VARCHAR   | 0xc982b9495667bc2f2018efab5969a395fe8bbe89                         |                                                              |
| amount            | VARCHAR   | 13477000000000000000000                                            |                                                              |
| fromChainID       | VARCHAR   | 250                                                                |                                                              |
| toChainID         | VARCHAR   | 1                                                                  |                                                              |

## 9. Table: AnyswapV4Router\_event\_LogAnySwapTradeTokensForNative\_history

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

## 10. Table: AnyswapV4Router\_event\_LogAnySwapTradeTokensForTokens\_history

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

## 11. Table: AnyswapV4Router\_event\_LogChangeMPC\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldMPC            | VARCHAR   |                                                              |             |
| newMPC            | VARCHAR   |                                                              |             |
| effectiveTime     | VARCHAR   |                                                              |             |
| chainID           | VARCHAR   |                                                              |             |

## 12. Table: AnyswapV4Router\_event\_LogChangeRouter\_history

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
