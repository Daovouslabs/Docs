# rari\_capital

## 1. Table: FusePoolDirectory\_event\_PoolRegistered\_history

| Column               | Type                                                                                                 | Example                                                                                              | Description                                                  |
| -------------------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP                                                                                            | 2021-10-02 03:54:10+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER                                                                                              | 13337591                                                                                             | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR                                                                                              | 0x69d371ae6bdbced9aa1cbe0c50a5d029e5fb9c006b754073f068ca67bbf6023f                                   | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER                                                                                              | 242                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR                                                                                              | 0x835482fe0532f169024d5e9410199369aad5c77e                                                           | Address of the contract that produced the log                |
| index                | VARCHAR                                                                                              | 34                                                                                                   |                                                              |
| pool                 | STRUCT\<name STRING, creator STRING, comptroller STRING, blockPosted STRING, timestampPosted STRING> | {'name': "state's pool", 'creator': '0xc8e0345596d7196941e61d3ab607e57fe61f85e7', 'comptroller': '0x |                                                              |
| pool.name            | VARCHAR                                                                                              | state's pool                                                                                         |                                                              |
| pool.creator         | VARCHAR                                                                                              | 0xc8e0345596d7196941e61d3ab607e57fe61f85e7                                                           |                                                              |
| pool.comptroller     | VARCHAR                                                                                              | 0x2a6b72539c020f751e45e235606667c53c105aaf                                                           |                                                              |
| pool.blockPosted     | VARCHAR                                                                                              | 13337591                                                                                             |                                                              |
| pool.timestampPosted | VARCHAR                                                                                              | 1633146850                                                                                           |                                                              |

## 2. Table: Unitroller\_event\_MarketListed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-23 18:28:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14831138                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac19a86bf2175c4bcba3315504e35aca44cea00c5cd4152d0fa4e9302729ecf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf2adaa305235623fe0fd108c7afbc10716c9005c                         | Address of the contract that produced the log                |
| cToken            | VARCHAR   | 0x2c88b6dd5dd6f576b4ee6566dee706a4039906fd                         |                                                              |

## 3. Table: cToken\_event\_AccrueInterest\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2021-09-16 03:54:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 13234448                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0xd44d9359935292d9cc45920a80bf81a4ef07e5d2c5383f583d2a2e49e367cab3 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x1066ab47a342152c564af62d179aa4b659a11f7d                         | Address of the contract that produced the log                |
| cashPrior           | VARCHAR   | 451524081516083476914516                                           |                                                              |
| interestAccumulated | VARCHAR   | 0                                                                  |                                                              |
| borrowIndex         | VARCHAR   | 1000000000000000000                                                |                                                              |
| totalBorrows        | VARCHAR   | 0                                                                  |                                                              |

## 4. Table: cToken\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 02:10:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14156188                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76935c4231bf8a2daacbffbba1f5476207919fcf5c3475a4cd0085a2f78df496 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 313                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1531c1a63a169ac75a2daae399080745fa51de44                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xf8e11c4df446ccd95f9362c4a998e9728c1e07be                         |                                                              |
| borrowAmount      | VARCHAR   | 11000000000000000000000                                            |                                                              |
| accountBorrows    | VARCHAR   | 11000000000000000000000                                            |                                                              |
| totalBorrows      | VARCHAR   | 10384360539506939633476682                                         |                                                              |

## 5. Table: cToken\_event\_LiquidateBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-15 05:45:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14588159                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdc296eaa9b8e0e03cf70fa1475b7f7f2eb1b95199792a635abcaf717e671911d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x342ac2c024f214a711356f48326614e1d8dd0420                         | Address of the contract that produced the log                |
| liquidator        | VARCHAR   | 0x6287d56e246eee33bead2d7dd3a99db693f4554c                         |                                                              |
| borrower          | VARCHAR   | 0x0ead347d565ac2cf5b42595be53edf343e52b9d9                         |                                                              |
| repayAmount       | VARCHAR   | 7835043944347959558144                                             |                                                              |
| cTokenCollateral  | VARCHAR   | 0x78dcc36dc532b0def7b53a56a91610c44dd09444                         |                                                              |
| seizeTokens       | VARCHAR   | 11257076711090                                                     |                                                              |

## 6. Table: cToken\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-14 03:11:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12822699                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5b9843b87fe95996222d07260bc0ec54457e5fd0f060722a7702e6807d71c23f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 311                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6eda4b59bac787933a4a21b65672539cef6ec97b                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x4a205424de1a6e5fc83d5f5f415fb2296542efce                         |                                                              |
| mintAmount        | VARCHAR   | 39099075938                                                        |                                                              |
| mintTokens        | VARCHAR   | 31557720111                                                        |                                                              |

## 7. Table: cToken\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 09:53:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14931956                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51253e78299ae6e3ba4c0aba3614701b7cbedf1c5953cced96fc35339aa645fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 251                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd79471754c9f1e19321308575abfb47389e547d2                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x38240bac58246ab1f932807ccb88fb7df1456e7f                         |                                                              |
| redeemAmount      | VARCHAR   | 474976408495628757                                                 |                                                              |
| redeemTokens      | VARCHAR   | 1393727772075548318                                                |                                                              |

## 8. Table: cToken\_event\_RepayBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 13:33:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17032246                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6cde31520abece842b4c9fb6b878e6681245ab41df8158857fd7ba83608d717e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 111                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x989273ec41274c4227bcb878c2c26fdd3afbe70d                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xcdefd5afcaa6db4d4c30aa49ce44fe1f81f4dd4b                         |                                                              |
| borrower          | VARCHAR   | 0xcdefd5afcaa6db4d4c30aa49ce44fe1f81f4dd4b                         |                                                              |
| repayAmount       | VARCHAR   | 119932997338434729806                                              |                                                              |
| accountBorrows    | VARCHAR   | 5593326650693816970017                                             |                                                              |
| totalBorrows      | VARCHAR   | 300510318057093340236366                                           |                                                              |

## 9. Table: cToken\_event\_ReservesAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 02:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17539358                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c6f377dfcc68c37a5fdb25beb3541ba78b9cb739bfb443f4641ef0db42ac32f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59bd6774c22486d9f4fab2d448dce4f892a9ae25                         | Address of the contract that produced the log                |
| benefactor        | VARCHAR   | 0x59bd6774c22486d9f4fab2d448dce4f892a9ae25                         |                                                              |
| addAmount         | VARCHAR   | 4669069969867071                                                   |                                                              |
| newTotalReserves  | VARCHAR   | 71973358323783758579                                               |                                                              |

## 10. Table: cToken\_event\_ReservesReduced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-20 17:21:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12278351                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ae506949f647536afa994eff30b9b0e1fe30d0438169e116f6003f62679be1e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x484d065931c19b8dc2d915b2cf23bb142c2c7637                         | Address of the contract that produced the log                |
| admin             | VARCHAR   | 0xb8f02248d53f7edfa38e79263e743e9390f81942                         |                                                              |
| reduceAmount      | VARCHAR   | 58316902398013444273                                               |                                                              |
| newTotalReserves  | VARCHAR   | 748338183083861744                                                 |                                                              |

## 11. Table: cToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 23:39:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17837799                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa215a34ce2f41b57cc65fb9633fa1479daec9704b53b2a7ba737ff6459bbcbf6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1531c1a63a169ac75a2daae399080745fa51de44                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x1531c1a63a169ac75a2daae399080745fa51de44                         |                                                              |
| to                | VARCHAR   | 0x8c1a4c98c470900567fb9e764243c89cda79400c                         |                                                              |
| amount            | VARCHAR   | 3134815502312                                                      |                                                              |
