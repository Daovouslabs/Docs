# lendfme

## 1. Table: MoneyMarket\_event\_BorrowLiquidated\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2020-02-10 06:52:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 9453572                                                            | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0x66b0901864e61f54355cd7ae9cb79fa43c8dd822c87b960906eea50cf3c98fc5 | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| targetAccount                | VARCHAR   | 0x028e255f0d41dbc10b5c3b010887afb2766d915e                         |                                                              |
| assetBorrow                  | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         |                                                              |
| borrowBalanceBefore          | VARCHAR   | 617916518                                                          |                                                              |
| borrowBalanceAccumulated     | VARCHAR   | 617917248                                                          |                                                              |
| amountRepaid                 | VARCHAR   | 2201000                                                            |                                                              |
| borrowBalanceAfter           | VARCHAR   | 615716248                                                          |                                                              |
| liquidator                   | VARCHAR   | 0x8ac3435fd089410a65c0e727ced5a9843f5492f2                         |                                                              |
| assetCollateral              | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| collateralBalanceBefore      | VARCHAR   | 76929924092                                                        |                                                              |
| collateralBalanceAccumulated | VARCHAR   | 76941230550                                                        |                                                              |
| amountSeized                 | VARCHAR   | 241277709                                                          |                                                              |
| collateralBalanceAfter       | VARCHAR   | 76699952841                                                        |                                                              |

## 2. Table: MoneyMarket\_event\_BorrowRepaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-07 09:57:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9824315                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x815e5e873c7848b30954dc53bfec34c81e670013ceadd8fe927c10f300fc1df4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x3584ca77ba08bd8b3fe4762e60eb284e37696829                         |                                                              |
| asset             | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         |                                                              |
| amount            | VARCHAR   | 109131518                                                          |                                                              |
| startingBalance   | VARCHAR   | 109131290                                                          |                                                              |
| newBalance        | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: MoneyMarket\_event\_BorrowTaken\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2020-01-11 21:34:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 9262074                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x704aae04f839b08ba89d4f62fb4f16daa7463987398d5b018b19a31fec308311 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| account             | VARCHAR   | 0x3584ca77ba08bd8b3fe4762e60eb284e37696829                         |                                                              |
| asset               | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         |                                                              |
| amount              | VARCHAR   | 92523414                                                           |                                                              |
| startingBalance     | VARCHAR   | 227374351                                                          |                                                              |
| borrowAmountWithFee | VARCHAR   | 92569675                                                           |                                                              |
| newBalance          | VARCHAR   | 319946127                                                          |                                                              |

## 4. Table: MoneyMarket\_event\_EquityWithdrawn\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2020-05-06 06:06:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 10010983                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x29e3be282526f5a6329dc66c539b4d49f5d1d4dd740ed69edcb514150284bb53 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| asset                 | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| equityAvailableBefore | VARCHAR   | 1146971418                                                         |                                                              |
| amount                | VARCHAR   | 5492708                                                            |                                                              |
| owner                 | VARCHAR   | 0xa6a6783828ab3e4a9db54302bc01c4ca73f17efb                         |                                                              |

## 5. Table: MoneyMarket\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-11 08:48:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9087875                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa7824f8afed6daf8a1ac8ec05c3a67edddbb6d2191051f0b3377da359c121e5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 8                                                                  |                                                              |
| info              | VARCHAR   | 72                                                                 |                                                              |
| detail            | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: MoneyMarket\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-27 08:48:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9169987                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b175f2c39fd985cec9684379c9284b71b1f9f4df044e0fe32da5f927acb35fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 62                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0xd30076b706fa0425bc52d0739224fe8ef1ae7c81                         |                                                              |
| newAdmin          | VARCHAR   | 0x0eb7fc2a5fb656944e31c59a68151159c0745998                         |                                                              |

## 7. Table: MoneyMarket\_event\_NewOracle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-12 03:02:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9654228                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe3ead1cc991ccc90ee5a5b073cd125a7ddcb40f1ffa95aa075c82626fed52cf2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 147                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| oldOracle         | VARCHAR   | 0x21f2a370d02996bc914e1b92160d47d279d9f15a                         |                                                              |
| newOracle         | VARCHAR   | 0xb620707637c5b2cc49843a03d90e28d9abbda149                         |                                                              |

## 8. Table: MoneyMarket\_event\_NewOriginationFee\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2020-03-11 06:11:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 9648526                                                            | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x163438a5ce6a049cd3ea125ddfebbc0ae6e5772f7098fe3d96378e09eb010a37 | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| oldOriginationFeeMantissa | VARCHAR   | 500000000000000                                                    |                                                              |
| newOriginationFeeMantissa | VARCHAR   | 100000000000000                                                    |                                                              |

## 9. Table: MoneyMarket\_event\_NewPendingAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-11 15:48:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9462586                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3b0a8e274d74335e23e20cc462631a4d33c858eb378b289c1c29ae12fab7d52 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| oldPendingAdmin   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingAdmin   | VARCHAR   | 0xa6a6783828ab3e4a9db54302bc01c4ca73f17efb                         |                                                              |

## 10. Table: MoneyMarket\_event\_NewRiskParameters\_history

| Column                         | Type      | Example                                                            | Description                                                  |
| ------------------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp               | TIMESTAMP | 2019-08-06 07:02:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                  | INTEGER   | 8295635                                                            | The block number where this event was emitted                |
| transaction\_hash              | VARCHAR   | 0x15f7ad77325927414dceb77dcad2392940f3bde5c7b5e20c24864813d0781092 | Hash of the transactions in which this event was emitted     |
| log\_index                     | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address              | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| oldCollateralRatioMantissa     | VARCHAR   | 2000000000000000000                                                |                                                              |
| newCollateralRatioMantissa     | VARCHAR   | 1250000000000000000                                                |                                                              |
| oldLiquidationDiscountMantissa | VARCHAR   | 0                                                                  |                                                              |
| newLiquidationDiscountMantissa | VARCHAR   | 100000000000000000                                                 |                                                              |

## 11. Table: MoneyMarket\_event\_SetMarketInterestRateModel\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-08 08:10:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9070782                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x102026332f1dd97fc7f19359fe69304c8ec5f2af6c313b8e82302a5264034add | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| interestRateModel | VARCHAR   | 0x45b1953611da41f841def7dceff318f83409739d                         |                                                              |

## 12. Table: MoneyMarket\_event\_SetPaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-19 04:57:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9900772                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2cfa65ecd53cff73c10b774b0a32a10026037f942128fc5a09a89cf524d11ba4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| newState          | VARCHAR   | true                                                               |                                                              |

## 13. Table: MoneyMarket\_event\_SupplyReceived\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-30 07:52:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9382310                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa988a7e88155e0327f228234d4e9c3362d5476120d26a5f86f786c41c596ca4c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x2d7f8ad1eb0b7989e46feb4cbc594497ab9649c0                         |                                                              |
| asset             | VARCHAR   | 0x3212b29e33587a00fb1c83346f5dbfa69a458923                         |                                                              |
| amount            | VARCHAR   | 1243551                                                            |                                                              |
| startingBalance   | VARCHAR   | 2093706                                                            |                                                              |
| newBalance        | VARCHAR   | 3337305                                                            |                                                              |

## 14. Table: MoneyMarket\_event\_SupplyWithdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-28 09:38:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9571360                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa30b10c63541a1db39171dd28e7a1cbc7dfdec171723c6be2ad005262835f6ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xcd5f8fa45e0ca0937f86006b9ee8fe1eedee5fc4                         |                                                              |
| asset             | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| amount            | VARCHAR   | 29990119678                                                        |                                                              |
| startingBalance   | VARCHAR   | 29990118089                                                        |                                                              |
| newBalance        | VARCHAR   | 0                                                                  |                                                              |

## 15. Table: MoneyMarket\_event\_SupportedMarket\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-06 06:53:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8295587                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b35e20f0906fb2f6775e9a374dac004c0e3f518811fac611f0da715a8b1d264 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eee3e3828a45f7601d5f54bf49bb01d1a9df5ea                         | Address of the contract that produced the log                |
| asset             | VARCHAR   | 0xeb269732ab75a6fd61ea60b06fe994cd32a83549                         |                                                              |
| interestRateModel | VARCHAR   | 0xfe81311f90b21eb6614dc8113014b3b53eca9acc                         |                                                              |
