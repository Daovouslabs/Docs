# multichain

## 1. Table: AnyswapV4Router2\_event\_LogAnySwapIn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 14:26:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24659241                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29835ad4955eadb1111908992ebbbe37ce9e4c75bcfa1abf06d880f9cfeb4a99 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 114                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6ff0609046a38d76bd40c5863b4d1a2dce687f73                         | Address of the contract that produced the log                |
| txhash            | VARCHAR   | 0x957ca790f8707b7761fd8f7e0c33affa2c30c40e8ffca08b557e352910a1b3c5 |                                                              |
| token             | VARCHAR   | 0x05f024c6f5a94990d32191d6f36211e3ee33504e                         |                                                              |
| to                | VARCHAR   | 0xb94c6c822d728e77dbc4c4e77cf4811e04f39c1b                         |                                                              |
| amount            | VARCHAR   | 4804980000000000000000                                             |                                                              |
| fromChainID       | VARCHAR   | 1                                                                  |                                                              |
| toChainID         | VARCHAR   | 137                                                                |                                                              |

## 2. Table: AnyswapV4Router2\_event\_LogAnySwapOut\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 08:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38696936                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe96916306fc874928b46d62cfaf5f5fb57fc8f6e0fc0b5496226bdd5ae0bf9af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6ff0609046a38d76bd40c5863b4d1a2dce687f73                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x3fb256cfefedb6a54de7465c0ee86dc574ae464d                         |                                                              |
| from              | VARCHAR   | 0x121edad46b92b9388f721a9b29afbb4721c3116c                         |                                                              |
| to                | VARCHAR   | 0x121edad46b92b9388f721a9b29afbb4721c3116c                         |                                                              |
| amount            | VARCHAR   | 173540456536989763620956                                           |                                                              |
| fromChainID       | VARCHAR   | 137                                                                |                                                              |
| toChainID         | VARCHAR   | 1                                                                  |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2022-04-28 08:20:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27669913                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe859e67896a9fb9f480cf04ece2b50e37758d9407cebbdc7c99e718098af89f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f3aff3a747fcade12598081e80c6605a8be192f                         | Address of the contract that produced the log                |
| txhash            | VARCHAR   | 0x1077f0c9907532c7bc586d2abc745c2ee9fd99f60bb066a71363755a0cda49cf |                                                              |
| token             | VARCHAR   | 0x161de8f0b9a59c8197e152da422b9031d3eaf338                         |                                                              |
| to                | VARCHAR   | 0xb153773debb997d9a630541f83d40c01f037d337                         |                                                              |
| amount            | VARCHAR   | 29390000                                                           |                                                              |
| fromChainID       | VARCHAR   | 1                                                                  |                                                              |
| toChainID         | VARCHAR   | 137                                                                |                                                              |

## 8. Table: AnyswapV4Router\_event\_LogAnySwapOut\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-19 09:15:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15894057                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x388fdf493ddcc8a9cd9daac387c33da5db4dfa419d1fc1cab50b139a88e3d268 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 643                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f3aff3a747fcade12598081e80c6605a8be192f                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x9610b01aaa57ec026001f7ec5cface51bfea0ba6                         |                                                              |
| from              | VARCHAR   | 0x000bc1d6e8e17c21e312fa1ff054608d99334d53                         |                                                              |
| to                | VARCHAR   | 0x000bc1d6e8e17c21e312fa1ff054608d99334d53                         |                                                              |
| amount            | VARCHAR   | 19140000                                                           |                                                              |
| fromChainID       | VARCHAR   | 137                                                                |                                                              |
| toChainID         | VARCHAR   | 56                                                                 |                                                              |

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

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-14 00:12:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25914025                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x757ba3aee960fe5e83d22f341327e83ef7591809c7f5471b06c43134f7eee900 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f3aff3a747fcade12598081e80c6605a8be192f                         | Address of the contract that produced the log                |
| path              | VARCHAR   | 0xd69b31c3225728CC57ddaf9be532a4ee1620Be51                         |                                                              |
| from              | VARCHAR   | 0xff8e30e4c1e676fd152ee5eeba09ba142e842bf1                         |                                                              |
| to                | VARCHAR   | 0xf2719d5f7ec66c38abd64bc5efda6876590b3b30                         |                                                              |
| amountIn          | VARCHAR   | 0                                                                  |                                                              |
| amountOutMin      | VARCHAR   | 50000000000000000000                                               |                                                              |
| fromChainID       | VARCHAR   | 137                                                                |                                                              |
| toChainID         | VARCHAR   | 42161                                                              |                                                              |

## 11. Table: AnyswapV4Router\_event\_LogChangeMPC\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-11 14:53:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16746757                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9886727bbf8f0de4f940c27d83eb1fe07d63bc40cb297c007926a2b1cef57fe5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 428                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f3aff3a747fcade12598081e80c6605a8be192f                         | Address of the contract that produced the log                |
| oldMPC            | VARCHAR   | 0x8b44a687224496276811555efa3f2d0acd667a72                         |                                                              |
| newMPC            | VARCHAR   | 0x2a038e100f8b85df21e4d44121bdbfe0c288a869                         |                                                              |
| effectiveTime     | VARCHAR   | 1626188036                                                         |                                                              |
| chainID           | VARCHAR   | 137                                                                |                                                              |

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
