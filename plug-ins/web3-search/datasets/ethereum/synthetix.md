# synthetix

## 1. Table: Issuer\_event\_SynthAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-20 23:50:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15792705                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0a4000aefe194802fb56c4c7030c98cf1f5ea6c86ed81e06a3a609222a7d679b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 489                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf187dad9bea2ba24bab1b3094e6fd7d809f29de7                         | Address of the contract that produced the log                |
| currencyKey       | VARCHAR   | 0x7343484600000000000000000000000000000000000000000000000000000000 |                                                              |
| synth             | VARCHAR   | 0xbb5b03e920cf702de5a3ba9fc1445af4b3919c88                         |                                                              |

## 2. Table: MultiCollateralSynth\_event\_ProxyUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 17:42:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14933855                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38e4799f7412ec8b5c0aceb255ea3aa318eaabdce03ad729605c03d6e7517305 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x75a0c1597137aa36b40b6a515d997f9a6c6eefeb                         | Address of the contract that produced the log                |
| proxyAddress      | VARCHAR   | 0x1715ac0743102bf5cd58efbb6cf2dc2685d967b6                         |                                                              |

## 3. Table: RewardEscrow\_event\_FeePoolUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-31 02:39:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9776850                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeda43eb5d693c77720427e0674371b30a36a9aea4961bd303508decaf57b9153 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb671f2210b1f6621a2607ea63e6b2dc3e2464d1f                         | Address of the contract that produced the log                |
| newFeePool        | VARCHAR   | 0x8a34aeff4cded94afa786fcf811a6307aa7c656a                         |                                                              |

## 4. Table: RewardEscrow\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-23 00:09:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16886595                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb4e8dcf66cf5cdb6e28d8d4946dd323f2952f21deaa8d47e97db42a88872ab1c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 448                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb671f2210b1f6621a2607ea63e6b2dc3e2464d1f                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0xe199d2bf3032400e5058381782c461df964b3439                         |                                                              |
| newOwner          | VARCHAR   | 0xeb3107117fead7de89cd14d463d340a2e6917769                         |                                                              |

## 5. Table: RewardEscrow\_event\_OwnerNominated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-19 00:31:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14233299                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5a47dc0d76e48118c9b87422480df89a753668ed3b7b62a68bd43329abf4370c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 481                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb671f2210b1f6621a2607ea63e6b2dc3e2464d1f                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0xeb3107117fead7de89cd14d463d340a2e6917769                         |                                                              |

## 6. Table: RewardEscrow\_event\_SynthetixUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-29 02:29:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8442410                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69199eae1c019d662cd28024b00f818d990c450bc48bd9f9514db6dabca687dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb671f2210b1f6621a2607ea63e6b2dc3e2464d1f                         | Address of the contract that produced the log                |
| newSynthetix      | VARCHAR   | 0xffc91f7088bf40f0419b451fb9d85718d8903628                         |                                                              |

## 7. Table: RewardEscrow\_event\_Vested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-10 08:43:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10430748                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60b01f18525e8272283c4292f9e33b07f1228d29376637e09576396bde1db3a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb671f2210b1f6621a2607ea63e6b2dc3e2464d1f                         | Address of the contract that produced the log                |
| beneficiary       | VARCHAR   | 0x4e6a82ac98e87c5acf7738fa57b5fd9ea14af932                         |                                                              |
| time              | VARCHAR   | 1594370603                                                         |                                                              |
| value             | VARCHAR   | 1102354720882112437200                                             |                                                              |

## 8. Table: RewardEscrow\_event\_VestingEntryCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-11 14:13:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7739657                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19084c91f2877e5bddd28a2174789f6adf63956fb4f906d58146eb89d39bccbd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb671f2210b1f6621a2607ea63e6b2dc3e2464d1f                         | Address of the contract that produced the log                |
| beneficiary       | VARCHAR   | 0x0fdebfe3b0a0e1bf4961894fc6145df36d0336b9                         |                                                              |
| time              | VARCHAR   | 1557584033                                                         |                                                              |
| value             | VARCHAR   | 1182718068316780920952                                             |                                                              |

## 9. Table: Synth\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-14 00:07:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9666253                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7544c5f896fbe66505557c5159d9316f89401a384d15f79ef0f4e2e03e0414a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5e74c9036fb86bd7ecdcb084a0673efc32ea31cb                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x196a3dc8446920cef0f0d1f6bf7ba5b40702c79f                         |                                                              |
| spender           | VARCHAR   | 0xe4c9194962532feb467dce8b3d42419641c6ed2e                         |                                                              |
| value             | VARCHAR   | 33290920124561832929                                               |                                                              |

## 10. Table: Synth\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-20 03:14:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9517656                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1a0e66fc20ce65250b43976a77b26e4c8e0ff107cd616f88e8923149cfa7a3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 175                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbbc455cb4f1b9e4bfc4b73970d360c8f032efee6                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0xb64ff7a4a33acdf48d97dab0d764afd0f6176882                         |                                                              |
| newOwner          | VARCHAR   | 0xb0a23f40de7f776a4f20153e8995ed3e7d7c8487                         |                                                              |

## 11. Table: Synth\_event\_OwnerNominated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-17 21:41:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14406469                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b607458bfda43ee3d19de3d114ce7e80651e69ac7a9eba34e1766613786869f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 421                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe36e2d3c7c34281fa3bc737950a68571736880a1                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0x9d10dcd04130b247cd08b31f64e60fa3b1502985                         |                                                              |

## 12. Table: Synth\_event\_TargetUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-18 03:40:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9123732                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74fb7378c066f5c2621d51037aa8d1116423885540b682cc7b1b6ce6491072dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57ab1ec28d129707052df4df418d58a2d46d5f51                         | Address of the contract that produced the log                |
| newTarget         | VARCHAR   | 0x289e9a4674663decee54f781aade5327304a32f8                         |                                                              |

## 13. Table: Synth\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-22 15:02:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16463109                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebe065c107ff9ba5205e2c5a39e9802ef3bb0434a4183b85e143246df1e32c0b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57ab1ec28d129707052df4df418d58a2d46d5f51                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x08780fb7e580e492c1935bee4fa5920b94aa95da                         |                                                              |
| to                | VARCHAR   | 0x9e380c121d291596812d680465156dde3bfba9c6                         |                                                              |
| value             | VARCHAR   | 86305805601432882080286                                            |                                                              |

## 14. Table: Synthetix\_event\_AccountFlaggedForLiquidation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-11 20:45:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15949244                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb59b06af723056024073f775f6ef124930a1c29ac6ed89bb03d83c3e294d1f45 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x05e661738e3a3c6f254d9c29a40dad0ec357ea85                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x63cbebce93d2d47d581e0d53b1ab5a860cf5ec18                         |                                                              |
| deadline          | VARCHAR   | 1668242759                                                         |                                                              |

## 15. Table: Synthetix\_event\_AccountRemovedFromLiquidation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-12 07:00:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15952304                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaa25416aae6ffc2a0afdec90edd5dcaa08e333ab86bb8ec27f5675520653980b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x05e661738e3a3c6f254d9c29a40dad0ec357ea85                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x5579f53f213ebcf68ea45e195b0e131d2fb64528                         |                                                              |
| time              | VARCHAR   | 1668236459                                                         |                                                              |

## 16. Table: Synthetix\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-16 17:27:10+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10471850                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9026d4ff15ff18800bbd9d43b3106ff3f032247cd16d6d28aaa5fa9c0a4aed67             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x20943a7fbdcb4b84ea553c13d765cd4adaee709b                                     |                                                              |
| spender           | VARCHAR   | 0x083d622790eebdc0dea4d9bd83557bbe0f7ca831                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 17. Table: Synthetix\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 19:16:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14934222                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf45faa68813326b9aad56473d20db130d43d7e706215f8f4f6a00d4735176327 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0xeb3107117fead7de89cd14d463d340a2e6917769                         |                                                              |
| newOwner          | VARCHAR   | 0x74beadeda41f10948bab911857a55bad93ce7636                         |                                                              |

## 18. Table: Synthetix\_event\_OwnerNominated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-24 01:18:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14832889                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c427a26db7ee910477ac639040790d6c1329d302e0cf5e752fcc986fefd72c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 349                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0x24dfd25d27605677dd9c2b7b63617d279194505a                         |                                                              |

## 19. Table: Synthetix\_event\_SynthExchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-20 02:42:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9705908                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa485685bd60761d36b95eece1d6ffc4ed3cf165173fad8c39d4b4af04c144ed2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc011a72400e58ecd99ee497cf89e3775d4bd732f                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x777ec27a8f1be1dbb74f591055f5457df8d6bffb                         |                                                              |
| fromCurrencyKey   | VARCHAR   | 0x6942544300000000000000000000000000000000000000000000000000000000 |                                                              |
| fromAmount        | VARCHAR   | 31787964826065                                                     |                                                              |
| toCurrencyKey     | VARCHAR   | 0x7345544800000000000000000000000000000000000000000000000000000000 |                                                              |
| toAmount          | VARCHAR   | 1035488714645530                                                   |                                                              |
| toAddress         | VARCHAR   | 0x777ec27a8f1be1dbb74f591055f5457df8d6bffb                         |                                                              |

## 20. Table: Synthetix\_event\_TargetUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-05 03:29:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10203309                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf286b1dd8d6163e866601cf85ba1646f76a11bae86f8f323ea4a8f0ca46db4c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f                         | Address of the contract that produced the log                |
| newTarget         | VARCHAR   | 0xc6738ed1eb79fa23941c75b4f437fc65893b5476                         |                                                              |

## 21. Table: Synthetix\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-03 16:52:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10789492                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc92e13531535eb42705027cd674ebea3f3195a3b1ebe593d5dd9969f67da4d00 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc011a73ee8576fb46f5e1c5751ca3b9fe0af2a6f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x00000000b1786c9698c160d78232c78d6f6474fe                         |                                                              |
| to                | VARCHAR   | 0xcd461b73d5fc8ea1d69a600f44618bdfac98364d                         |                                                              |
| value             | VARCHAR   | 288018688926219042816                                              |                                                              |

## 22. Table: sBTC\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-12 18:12:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11641732                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8650d401bf2ca3c17f53793f76556240afe923b5ab625869664d99d1e264dab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe18be6b3bd88a2d2a7f928d00292e7a9963cfc6                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x63be84b1d75751e52716ae153dbc5abb5b2a98f5                         |                                                              |
| spender           | VARCHAR   | 0x881d40237659c251811cec9c364ef91dc08d300c                         |                                                              |
| value             | VARCHAR   | 90071992547409910000000000                                         |                                                              |

## 23. Table: sBTC\_event\_Burned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-13 20:45:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13219617                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaa2b48df1a32010fbd592169dd08fe4352a67d847ed478bdb561f66d1a0a22f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe18be6b3bd88a2d2a7f928d00292e7a9963cfc6                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x510b0068c0756bbefcbaffb6567e467d661291fe                         |                                                              |
| value             | VARCHAR   | 274609363805472159                                                 |                                                              |

## 24. Table: sBTC\_event\_Issued\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-23 07:20:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10120729                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0bc99ff593fdc9df017e0ae63f0e988abd7b25a3d1bfb229974ccc5d3d800dcb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe18be6b3bd88a2d2a7f928d00292e7a9963cfc6                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x4fd06e4b573ddb0caf7f595fa61d2be4c3a1ada5                         |                                                              |
| value             | VARCHAR   | 9109868522135989                                                   |                                                              |

## 25. Table: sBTC\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 19:36:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14934329                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa454cf9d341857f377dc6923d86e6417f22f2e23cde9a13e914ad310b51b44d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe18be6b3bd88a2d2a7f928d00292e7a9963cfc6                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x74beadeda41f10948bab911857a55bad93ce7636                         |                                                              |
| newOwner          | VARCHAR   | 0xeb3107117fead7de89cd14d463d340a2e6917769                         |                                                              |

## 26. Table: sBTC\_event\_OwnerNominated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 19:16:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14934222                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf45faa68813326b9aad56473d20db130d43d7e706215f8f4f6a00d4735176327 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 563                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe18be6b3bd88a2d2a7f928d00292e7a9963cfc6                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0xeb3107117fead7de89cd14d463d340a2e6917769                         |                                                              |

## 27. Table: sBTC\_event\_ProxyUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| proxyAddress      | VARCHAR   |                                                              |             |

## 28. Table: sBTC\_event\_SelfDestructBeneficiaryUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newBeneficiary    | VARCHAR   |                                                              |             |

## 29. Table: sBTC\_event\_SelfDestructInitiated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| selfDestructDelay | VARCHAR   |                                                              |             |

## 30. Table: sBTC\_event\_SelfDestructTerminated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 31. Table: sBTC\_event\_SelfDestructed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| beneficiary       | VARCHAR   |                                                              |             |

## 32. Table: sBTC\_event\_TokenStateUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newTokenState     | VARCHAR   |                                                              |             |

## 33. Table: sBTC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-14 09:50:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16404258                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0c30226712927e3eddd7a185eab354cd4fb18ce507f33f958e5d093b5a670862 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 62                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfe18be6b3bd88a2d2a7f928d00292e7a9963cfc6                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xf253f83aca21aabd2a20553ae0bf7f65c755a07f                         |                                                              |
| to                | VARCHAR   | 0x0000000000a84d1a9b0063a910315c7ffa9cd248                         |                                                              |
| value             | VARCHAR   | 329614363787989084                                                 |                                                              |
