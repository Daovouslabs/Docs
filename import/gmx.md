# gmx

## 1. Table: Router\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 02:18:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 98567637                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x053e5e01ac2144ed71c24f8b1e0ec58a6b1afa0005dce3681e0327caeebf6cd0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xabbc5f99639c9b6bcb58544ddf04efa6802f4064                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xf7946c8c89691e453e00f078c7c70c4da2c99e67                         |                                                              |
| tokenIn           | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| tokenOut          | VARCHAR   | 0x82af49447d8a07e3bd95bd0d56f35241523fbab1                         |                                                              |
| amountIn          | VARCHAR   | 32867975057343053                                                  |                                                              |
| amountOut         | VARCHAR   | 17448041143802                                                     |                                                              |

## 2. Table: Vault\_event\_BuyUSDG\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-15 16:09:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7945021                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x84e83aa474cc08cd9d2a6744d36b500ab87e8891030593b56a21f757544306b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x321f653eed006ad1c29d174e17d96351bde22649                         |                                                              |
| token             | VARCHAR   | 0xf97f4df75117a78c1a5a0dbb814af92458539fb4                         |                                                              |
| tokenAmount       | VARCHAR   | 750000000000000000000                                              |                                                              |
| usdgAmount        | VARCHAR   | 9968017500000000000000                                             |                                                              |
| feeBasisPoints    | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: Vault\_event\_ClosePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 03:22:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 93472467                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe1bf48f9c854d8fce3c76c5eab9e2d12df7fbfdde77770b1841d0a9786ed555e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0x2724f240569231985d06634ec28a0ec3ddf2239e1dbd42c969a81363e15132d0 |                                                              |
| size              | VARCHAR   | 8941474726554102885787414909010400                                 |                                                              |
| collateral        | VARCHAR   | 0                                                                  |                                                              |
| averagePrice      | VARCHAR   | 1809405600050796533117835367045194                                 |                                                              |
| entryFundingRate  | VARCHAR   | 352503                                                             |                                                              |
| reserveAmount     | VARCHAR   | 0                                                                  |                                                              |
| realisedPnl       | VARCHAR   | -270479020184953321364565590285528                                 |                                                              |

## 4. Table: Vault\_event\_CollectMarginFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-18 09:55:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39018430                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd55cf1648eca3b015774e901cc0034a0b8af68f492683623c3121c50c882a5e1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| feeUsd            | VARCHAR   | 1153521249523809523751680000000                                    |                                                              |
| feeTokens         | VARCHAR   | 1153521249523809523                                                |                                                              |

## 5. Table: Vault\_event\_CollectSwapFees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-09 16:37:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 99440032                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85cf10f5a268d7c5dcbecc2a2403894ad8063ff47357ff923608547c383f07ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| feeUsd            | VARCHAR   | 77310660000000000                                                  |                                                              |
| feeTokens         | VARCHAR   | 77310660000000000000000000000                                      |                                                              |

## 6. Table: Vault\_event\_DecreaseGuaranteedUsd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 02:37:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 98572011                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8260b1c4d0af1fbef5568a266545fe9b6cbabc352d3748eee4d51c3827aebb63 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| amount            | VARCHAR   | 464100166932142308960000000000000                                  |                                                              |

## 7. Table: Vault\_event\_DecreasePoolAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-01 00:02:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 57013309                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc2dced104a3fea1b64732dd8dfd37354a47c74d299a3cbae879b9685c232425 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| amount            | VARCHAR   | 14921177597471971431                                               |                                                              |

## 8. Table: Vault\_event\_DecreasePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-13 09:10:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20143822                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d567d5bc3a1f44fe589e695526cfa3d5d18a14e8ae06c52c8d356fbf1304e92 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0x2ae8b5c92a939afbac57178cdd4ebd63fab23a5d23d0c7563a0e6f00ffc3996b |                                                              |
| account           | VARCHAR   | 0xb9581d8311cc3b9e677af6b0c55f1b93b69ad6f6                         |                                                              |
| collateralToken   | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| indexToken        | VARCHAR   | 0x82af49447d8a07e3bd95bd0d56f35241523fbab1                         |                                                              |
| collateralDelta   | VARCHAR   | 0                                                                  |                                                              |
| sizeDelta         | VARCHAR   | 4074827586206896550788370000000000                                 |                                                              |
| isLong            | VARCHAR   | false                                                              |                                                              |
| price             | VARCHAR   | 1990384000000000000000000000000000                                 |                                                              |
| fee               | VARCHAR   | 4144099655172413792151772290000                                    |                                                              |

## 9. Table: Vault\_event\_DecreaseReservedAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-29 23:27:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4165724                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0e0a140cae96553b981948a2bf5d73bc40c5bd81db142d661b2b6c04d8db6e5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| amount            | VARCHAR   | 81571450                                                           |                                                              |

## 10. Table: Vault\_event\_DecreaseUsdgAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 12:42:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 93606103                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x192c114af204ea5b70ce9441f24a3e7ec5c18b7b328e77dcc70a157519846b4e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| amount            | VARCHAR   | 4543000000000000000000                                             |                                                              |

## 11. Table: Vault\_event\_DirectPoolDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-31 08:08:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 227150                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4851b859655156895b97f8485ef53e08084f8c662eb33a892a53c18a30b11f91 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| amount            | VARCHAR   | 7000000                                                            |                                                              |

## 12. Table: Vault\_event\_IncreaseGuaranteedUsd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-26 16:38:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 105159047                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb86fd2c1377687d61f90e661cf5a0c3da8be51e52faf41581808793f23971919 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| amount            | VARCHAR   | 77821777145249847413958596000000000                                |                                                              |

## 13. Table: Vault\_event\_IncreasePoolAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 11:44:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 96331178                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd795ff106f6717971986dfbac72844034237fef8a9b5d02f98611839b9a59fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| amount            | VARCHAR   | 20001250000000000000000                                            |                                                              |

## 14. Table: Vault\_event\_IncreasePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-27 21:40:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10690878                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09e2f3059bca32f4b0dcf137f4da667cc700a30cdc3c9b89b98e7b1c884e3e55 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0xe3eada60848a355e7090f6299e9b88d7c9444edbcecaf4106489bc5769aaab91 |                                                              |
| account           | VARCHAR   | 0x1e2fce2e2a821c254fc4e53b373586af07ed0008                         |                                                              |
| collateralToken   | VARCHAR   | 0xff970a61a04b1ca14834a43f5de4533ebddb5cc8                         |                                                              |
| indexToken        | VARCHAR   | 0x82af49447d8a07e3bd95bd0d56f35241523fbab1                         |                                                              |
| collateralDelta   | VARCHAR   | 500000000000000000000000000000000                                  |                                                              |
| sizeDelta         | VARCHAR   | 998003992015968062433000000000000                                  |                                                              |
| isLong            | VARCHAR   | false                                                              |                                                              |
| price             | VARCHAR   | 2895000000000000000000000000000000                                 |                                                              |
| fee               | VARCHAR   | 998003992015968062433000000000                                     |                                                              |

## 15. Table: Vault\_event\_IncreaseReservedAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 09:04:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 93553669                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x623fada1892068c407dfa45ac5d00febf97d65241a79a462e654b51b8f9aa917 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| amount            | VARCHAR   | 7389162561576354678859                                             |                                                              |

## 16. Table: Vault\_event\_IncreaseUsdgAmount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-17 01:41:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 91458056                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa003d91f94c9e1ffe6febbdc0318d076a2f670491d946a5b45c8b21079522f77 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x17fc002b466eec40dae837fc4be5c67993ddbd6f                         |                                                              |
| amount            | VARCHAR   | 29228519246339087127                                               |                                                              |

## 17. Table: Vault\_event\_LiquidatePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 14:59:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 117773597                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd8e50de22357a5915f2840b494c1b3ed21c51bc7cfbe1b659c54277f333b70da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0x9c37108d1154d0f0ec6df51684b12463400ce20183730d9cf00e3e3c295386e7 |                                                              |
| account           | VARCHAR   | 0x2c89da62861ef124143d85ca2c4db35d9611a037                         |                                                              |
| collateralToken   | VARCHAR   | 0xff970a61a04b1ca14834a43f5de4533ebddb5cc8                         |                                                              |
| indexToken        | VARCHAR   | 0x2f2a2543b76a4166549f7aab2e75bef0aefc5b0f                         |                                                              |
| isLong            | VARCHAR   | false                                                              |                                                              |
| size              | VARCHAR   | 582524124121116672000000000000000                                  |                                                              |
| collateral        | VARCHAR   | 9417475875878883328000000000000                                    |                                                              |
| reserveAmount     | VARCHAR   | 582524124                                                          |                                                              |
| realisedPnl       | VARCHAR   | 0                                                                  |                                                              |
| markPrice         | VARCHAR   | 29388169000000000000000000000000000                                |                                                              |

## 18. Table: Vault\_event\_SellUSDG\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-17 05:49:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20471569                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa75a8bdcc6a1784e62c987ed9c26f06a522271318d9e4ca7d715d853fea6106c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xd9928103ae80cd7b233285e5c7fb6b6e21c2e531                         |                                                              |
| token             | VARCHAR   | 0xf97f4df75117a78c1a5a0dbb814af92458539fb4                         |                                                              |
| usdgAmount        | VARCHAR   | 14675830915095031273956                                            |                                                              |
| tokenAmount       | VARCHAR   | 1687466160892517461857                                             |                                                              |
| feeBasisPoints    | VARCHAR   | 3                                                                  |                                                              |

## 19. Table: Vault\_event\_Swap\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-01-25 16:48:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 5032736                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xb9da51ac5465bafb6fdffc64881c3defd7599302c43dd84acf70832b9b009d55 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| account            | VARCHAR   | 0x3f3720ba8218163243ad8fc21d2e952549dbc610                         |                                                              |
| tokenIn            | VARCHAR   | 0xff970a61a04b1ca14834a43f5de4533ebddb5cc8                         |                                                              |
| tokenOut           | VARCHAR   | 0xda10009cbd5d07dd0cecc66161fc93d7c9000da1                         |                                                              |
| amountIn           | VARCHAR   | 299594623                                                          |                                                              |
| amountOut          | VARCHAR   | 299594623000000000000                                              |                                                              |
| amountOutAfterFees | VARCHAR   | 299534704075400000000                                              |                                                              |
| feeBasisPoints     | VARCHAR   | 2                                                                  |                                                              |

## 20. Table: Vault\_event\_UpdateFundingRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-20 11:48:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 92591728                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaadf8a7309f5c2d0c637befe281d8cee63af9267a6d83a0dd4eafc6d3e7b7138 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xfa7f8980b0f1e64a2062791cc3b0871572f1f7f0                         |                                                              |
| fundingRate       | VARCHAR   | 159073                                                             |                                                              |

## 21. Table: Vault\_event\_UpdatePnl\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-29 17:30:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3439030                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea921894d22e670cb9bf29be8282be557c11c1139c43c8169c4f0b37d54d9cf0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0x4dda5980fb3a160bfe0a3d6511d7178528cecff7eb2bf463875363cc409e1459 |                                                              |
| hasProfit         | VARCHAR   | true                                                               |                                                              |
| delta             | VARCHAR   | 5410240000000000000000000000000000                                 |                                                              |

## 22. Table: Vault\_event\_UpdatePosition\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-26 14:48:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 105132454                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x56ce62a09598ff3a3a0de0a22c67725c015230954a7927a7d842c28782131a4d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 516                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x489ee077994b6658eafa855c308275ead8097c4a                         | Address of the contract that produced the log                |
| key               | VARCHAR   | 0xcd46c4c6d73a71940d498c6f45f280beaf052e26c0a2ba7f48c197526f9d38f2 |                                                              |
| size              | VARCHAR   | 261969953030537909885763741112170300                               |                                                              |
| collateral        | VARCHAR   | 12881085046969462090114236258887828                                |                                                              |
| averagePrice      | VARCHAR   | 1877773671425061361301466402786705                                 |                                                              |
| entryFundingRate  | VARCHAR   | 601217                                                             |                                                              |
| reserveAmount     | VARCHAR   | 139510930958855266457                                              |                                                              |
| realisedPnl       | VARCHAR   | 0                                                                  |                                                              |
