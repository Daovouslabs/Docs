# spookyswap

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-19 15:19:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14988653                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0eb4af4aedf096b407efa8206588aec8f4f32f173b885cbf2cfd844837e8837 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x152ee697f2e276fa89e96742e9bb9ab1f2e61be3                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x071bc76a2f40c874e3e5c013fb7c3a490f9b2243                         |                                                              |
| token1            | VARCHAR   | 0x21be370d5312f44cb42ce377bc9b8a0cef1a4c83                         |                                                              |
| pair              | VARCHAR   | 0x8af4ab8b8c63a891ae99ed6ea16a434ec1a407cd                         |                                                              |
| \_uint            | VARCHAR   | 1349                                                               |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 08:00:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 46520987                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x143b3bc1404b01b2c6c42cf2423639cfa4f458b765ce5d522478988985e2dcda | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x89d9bc2f2d091cfbfc31e333d6dc555ddbc2fd29                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0258bf0b67002c0aa687937e75343fc730e5523b                         |                                                              |
| spender           | VARCHAR   | 0x18b4f774fdc7bf685daeef66c2990b1ddd9ea6ad                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 00:34:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36161996                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0043d7db336cb26fe4b748f61f6112d024d4dc189ee9fcde454edea48e423e3b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0298c5fd8e69f54a45b2d486959098354f33ec37                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xf491e7b69e4244ad4002bc14e878a34207e38c29                         |                                                              |
| amount0           | VARCHAR   | 13535805357448190848                                               |                                                              |
| amount1           | VARCHAR   | 690537875999978983                                                 |                                                              |
| to                | VARCHAR   | 0xf60e8da60b699902d1ac4aaf89c249b02f1123e1                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 15:32:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7759087                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf9a02588a6e14d47b428c7a301e92b1ea8c88756d42f42c3c8feba25108df863 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06d173628be105fe81f1c82c9979ba79ebcafcb7                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xf491e7b69e4244ad4002bc14e878a34207e38c29                         |                                                              |
| amount0           | VARCHAR   | 18840050280133038463066                                            |                                                              |
| amount1           | VARCHAR   | 481767664967036174557                                              |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 21:54:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 65546716                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5b6cc3689c7643dc58a916a97ae78e97e12d96d60e69161c1f04890ebf0c0350 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0090dff94480017691745dd4199596365fcd3627                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc3da629c518404860c8893a66ce3bb2e16bea6ec                         |                                                              |
| amount0In         | VARCHAR   | 5917907584273996268                                                |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 6577686161844890                                                   |                                                              |
| to                | VARCHAR   | 0x21e93724a11870ab65857373bc38dbd1effc3738                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 09:53:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 66381615                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2c46e12553ed9c3e607bdff1b90990c7426fc614bf7c4b479a6f97f53b8639cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa196c7754f4ec79de55bb5db82187bbe82275f7f                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 1221320810065                                                      |                                                              |
| reserve1          | VARCHAR   | 4994092630716741775339884                                          |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 04:13:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44519743                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2d0049e9fb8a45634e22f470af0c969c3f7156e88179b383d12fc6b0f29a8959 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x011732f65e2f28c50f528e32420a2f69937b9e68                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3b3fdc40582a957206aed119842f2313de9ee21b                         |                                                              |
| to                | VARCHAR   | 0x011732f65e2f28c50f528e32420a2f69937b9e68                         |                                                              |
| value             | VARCHAR   | 1011560678763356919                                                |                                                              |

## 8. Table: UniswapV2Pair\_event\_Transfer\_temp0\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-05 13:25:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 61536170                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe64453407a6392697df9f9335e9b846ee1ae4e8579aafb431adfd857b43ad122 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x03d3b0fdd94844258185660a909ac5e83bbb8288                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xa1adfe820129493dada96cdca1d41dc27b634e89                         |                                                              |
| value             | VARCHAR   | 2485265666259708093                                                |                                                              |
