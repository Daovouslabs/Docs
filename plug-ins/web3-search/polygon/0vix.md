# 0vix

## 1. Table: Unitroller\_event\_MarketListed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-22 18:16:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40645403                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9fe4b490ec55ec40b61a21b3ee278cd1d4f9f0f623c2f1bfe5c0369729c6a75 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8849f1a0cb6b5d6076ab150546eddee193754f1c                         | Address of the contract that produced the log                |
| oToken            | VARCHAR   | 0xe053a4014b50666ed388ab8cbb18d5834de0ab12                         |                                                              |

## 2. Table: oToken\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2023-04-01 17:42:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 41026513                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x0951b755524f886ecd2288891783f062c5457570c78265641db5313481ab4776 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 239                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x3b9128ddd834ce06a60b0ec31ccfb11582d8ee18                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 2142730050                                                         |                                                              |
| interestAccumulated | VARCHAR   | 121                                                                |                                                              |
| borrowIndex         | VARCHAR   | 1034557247241155221                                                |                                                              |
| totalBorrows        | VARCHAR   | 526102613                                                          |                                                              |

## 3. Table: oToken\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-22 17:33:48+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27450247                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe24754c9ceac39afbe95fb72bbb8d052b55d1e5facef8d3fb15cffe843e4891b             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 279                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xebb865bf286e6ea8abf5ac97e1b56a76530f3fbe                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0caee49bdd3440735cea29f855afcc19c0214875                                     |                                                              |
| spender           | VARCHAR   | 0x216b4b4ba9f3e719726886d34a177484278bfcae                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 4. Table: oToken\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-20 04:23:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32098029                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8fc937e407ec7db4f8b31a470dd5fea40a482999bb46af45131195f5a95e5c06 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1372c34acc14f1e8644c72dad82e3a21c211729f                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x2be832d51e484ad274380f0e74676359ffa94c64                         |                                                              |
| borrowAmount      | VARCHAR   | 2170444                                                            |                                                              |
| accountBorrows    | VARCHAR   | 2170444                                                            |                                                              |
| totalBorrows      | VARCHAR   | 43240519562                                                        |                                                              |

## 5. Table: oToken\_event\_Failure\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 11:04:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34739206                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4c03ce45bd8dc637302dca1a9a734a91c39e368d4fa5e7632112e2618d0828b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc57e5e261d49af3026446de3ec381172f17bb799                         | Address of the contract that produced the log                |
| error             | VARCHAR   | 3                                                                  |                                                              |
| info              | VARCHAR   | 40                                                                 |                                                              |
| detail            | VARCHAR   | 4                                                                  |                                                              |

## 6. Table: oToken\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 17:47:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38909065                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6bc03bed6b862e2c1dc6d35223a8c47835854e00a3529a9278142939fae694aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 272                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe554e874c9c60e45f1debd479389c76230ae25a8                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x2b59932c8f035893ea68b9968096241a84cbc365                         |                                                              |
| borrower          | VARCHAR   | 0x803f4a26b35e20f025ea47bba26ca0c7df60c4de                         |                                                              |
| repayAmount       | VARCHAR   | 7814430510157970511                                                |                                                              |
| oTokenCollateral  | VARCHAR   | 0xebb865bf286e6ea8abf5ac97e1b56a76530f3fbe                         |                                                              |
| seizeTokens       | VARCHAR   | 54101227960                                                        |                                                              |

## 7. Table: oToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-16 15:07:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29641143                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee14339eb69841604cf21b135555db681620520bfc19bbf0d887af843c3303ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1372c34acc14f1e8644c72dad82e3a21c211729f                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x1a074cd2eeed45eb05a37f864aa6956e7023117e                         |                                                              |
| mintAmount        | VARCHAR   | 1000000                                                            |                                                              |
| mintTokens        | VARCHAR   | 4967319030                                                         |                                                              |

## 8. Table: oToken\_event\_NewAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-06 14:17:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42377070                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2aaa0a6ba660ba32801d7de29c21f8855ee3f00926614846ba78838f920a9c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x29b0f07d5a61595685a17d5f9f86313742ebd6bc                         | Address of the contract that produced the log                |
| oldAdmin          | VARCHAR   | 0x8e1304ea39c47e791182ba39fdf362a8767d7e97                         |                                                              |
| newAdmin          | VARCHAR   | 0x7b2b0cbadc25953a64d77b4785848b48b45e1017                         |                                                              |

## 9. Table: oToken\_event\_NewComptroller\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 23:56:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36596683                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x07655be9553e1c4447fd005992c7d9ea967c40cbac3e667a8ed4b76b3e126c47 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x29b0f07d5a61595685a17d5f9f86313742ebd6bc                         | Address of the contract that produced the log                |
| oldComptroller    | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newComptroller    | VARCHAR   | 0x8849f1a0cb6b5d6076ab150546eddee193754f1c                         |                                                              |

## 10. Table: oToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 11:05:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38898142                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x77d60cb859323e2bf0c137e51f2c4835cabdfefc180907d598b6c23a14e6e797 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1372c34acc14f1e8644c72dad82e3a21c211729f                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x8f01efdc8353c4753a3d57d20e2292ec224ffff0                         |                                                              |
| redeemAmount      | VARCHAR   | 30000000                                                           |                                                              |
| redeemTokens      | VARCHAR   | 147089994227                                                       |                                                              |

## 11. Table: oToken\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-19 20:08:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35814791                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5168723b82d76c444ecb6c67be76fdd08ca2ab7056ffca7f8c218d3d76f9af8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 183                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xebb865bf286e6ea8abf5ac97e1b56a76530f3fbe                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x011c7d8f2e81debad70e0ef02f68bc3742d578f0                         |                                                              |
| borrower          | VARCHAR   | 0x011c7d8f2e81debad70e0ef02f68bc3742d578f0                         |                                                              |
| repayAmount       | VARCHAR   | 4050142                                                            |                                                              |
| accountBorrows    | VARCHAR   | 0                                                                  |                                                              |
| totalBorrows      | VARCHAR   | 431885260954                                                       |                                                              |

## 12. Table: oToken\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-22 14:46:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40640041                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x95029fffc3798ef61caceb082af68078002b45864462083294ef2341ac876ead | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2175110f2936bf630a278660e9b6e4efa358490a                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x2175110f2936bf630a278660e9b6e4efa358490a                         |                                                              |
| addAmount         | VARCHAR   | 1153808100757814187                                                |                                                              |
| newTotalReserves  | VARCHAR   | 3931133320577634763995                                             |                                                              |

## 13. Table: oToken\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 12:14:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43050617                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaac7bb8085e7ca5f588eb9701288685c37b30f6285dd3b377cb981a69d359c50 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 302                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xebb865bf286e6ea8abf5ac97e1b56a76530f3fbe                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0x7b2b0cbadc25953a64d77b4785848b48b45e1017                         |                                                              |
| reduceAmount      | VARCHAR   | 734998437000                                                       |                                                              |
| newTotalReserves  | VARCHAR   | 19592634333                                                        |                                                              |

## 14. Table: oToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-25 07:03:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43121585                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31927ee3951d2e3ab19309e13a640721c7605fedf885b822792e04b5996d69cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 323                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6f063fe661d922e4fd77227f8579cb84f9f41f0b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7753dd631cc0bf96dafd58614d03b8258947b22e                         |                                                              |
| to                | VARCHAR   | 0xfa08377db6866b0a704da0d15df79ebb86afa369                         |                                                              |
| amount            | VARCHAR   | 6104630876957                                                      |                                                              |
