# reflexer

## 1. Table: CoinJoin\_event\_Exit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 09:22:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14158102                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x051039fcd5530164e7592db444e18b875e0c4d9f6c864b44529cf4103bdef773 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 493                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0a5653cca4db1b6e265f47caf6969e64f1cfdc45                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xd0a8e874daaa34e6df58692c7cb2bba8086b0ee3                         |                                                              |
| account           | VARCHAR   | 0x6cb286fe6915adbd4f5c08b09841839e66335cfb                         |                                                              |
| wad               | VARCHAR   | 2150000000000000000000                                             |                                                              |

## 2. Table: CoinJoin\_event\_Join\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 13:58:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13639725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc77f2a3f73be267d8f3b59343adc82b77e7bcd6ca8e795c90478ed56192c49dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 201                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0a5653cca4db1b6e265f47caf6969e64f1cfdc45                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x9d7c587709205fe908fac2be6df9bc15c4b56b37                         |                                                              |
| account           | VARCHAR   | 0x373a86c48df381927f0cabb34b525e4156a13e9d                         |                                                              |
| wad               | VARCHAR   | 4626462972603660520950447                                          |                                                              |

## 3. Table: CollateralETHJoin1\_event\_Exit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-30 16:24:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12736411                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc4c55befa1c509f41b3dc04c7034caf17e11398d763976c39ba0c5df8bec7c5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d3cd7b81c93f188f3cb8ad87c8acc73d6226e3a                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xe8f5bc6a4c41d0ce471da082b2eee3ef51e5ee23                         |                                                              |
| usr               | VARCHAR   | 0xe8f5bc6a4c41d0ce471da082b2eee3ef51e5ee23                         |                                                              |
| wad               | VARCHAR   | 20000000000000000000                                               |                                                              |

## 4. Table: CollateralETHJoin1\_event\_Join\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 23:57:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13642383                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19ce4e55f0f4e332383d61c7ef831ffabcb9adea60249768a5606db15d3607a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 153                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d3cd7b81c93f188f3cb8ad87c8acc73d6226e3a                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x3202573b2b4d9a14d2d0d3506b79aaa9797e72ac                         |                                                              |
| usr               | VARCHAR   | 0x3202573b2b4d9a14d2d0d3506b79aaa9797e72ac                         |                                                              |
| wad               | VARCHAR   | 17250000000000000000                                               |                                                              |

## 5. Table: DSProxyFactory\_event\_Created\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-05 11:13:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17194058                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f92cab1a1eef58c4484f84dfc36d71a19bff7fdb69ecb3b42e90ae377df5fc7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa26e15c895efc0616177b7c1e7270a4c7d51c997                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x4678f0a6958e4d2bc4f1baf7bc52e8f3564f3fe4                         |                                                              |
| owner             | VARCHAR   | 0x664134e0a2ee5d5a2d1ff3e39428f0e8c948b255                         |                                                              |
| proxy             | VARCHAR   | 0xc3640d638148f1335eccc55462f0d3e8a605d6d2                         |                                                              |
| cache             | VARCHAR   | 0x271293c67e2d3140a0e9381eff1f9b01e07b0795                         |                                                              |

## 6. Table: DSProxy\_event\_LogSetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-02-08 22:25:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7195003                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x468846d4ad592eb96ebf479aef5c8481b631197890a33831ebffafb0939c2c78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1da08d07aab8bea7d627f8b0a304bc9c41939989                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xa26e15c895efc0616177b7c1e7270a4c7d51c997                         |                                                              |

## 7. Table: GebSafeManager\_event\_AllowSAFE\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-23 00:37:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12091919                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x81701bc90c01f17b4643999956bea3642146f6005d7d052eb5fee403a1fb12a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x88a58815754f24d1e4e4d83de2596db457c31fe5                         |                                                              |
| safe              | VARCHAR   | 1419                                                               |                                                              |
| usr               | VARCHAR   | 0xf91f8844258d3246be5daa201b52b51fc7fccfd7                         |                                                              |
| ok                | VARCHAR   | 1                                                                  |                                                              |

## 8. Table: GebSafeManager\_event\_EnterSystem\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| src               | VARCHAR   |                                                              |             |
| safe              | VARCHAR   |                                                              |             |

## 9. Table: GebSafeManager\_event\_ModifySAFECollateralization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 04:13:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14137280                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63c7fd663eef713cfc7766a9c47a58ce2108b18c2f1aedc9182edfe5aa640580 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc9cea6df3a736846c5b610ff342836838ec1a84d                         |                                                              |
| safe              | VARCHAR   | 2200                                                               |                                                              |
| deltaCollateral   | VARCHAR   | 0                                                                  |                                                              |
| deltaDebt         | VARCHAR   | 596305816130371676002627                                           |                                                              |

## 10. Table: GebSafeManager\_event\_MoveSAFE\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| safeSrc           | VARCHAR   |                                                              |             |
| safeDst           | VARCHAR   |                                                              |             |

## 11. Table: GebSafeManager\_event\_OpenSAFE\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-27 21:38:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12324949                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c39ea8905a0d0dd7d29483b3265ffddd240d5b2a37622983143a46ef027d4da | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xbe6777faf4cbe4b4e3530e88cf8200b23bae9a63                         |                                                              |
| own               | VARCHAR   | 0xbe6777faf4cbe4b4e3530e88cf8200b23bae9a63                         |                                                              |
| safe              | VARCHAR   | 1938                                                               |                                                              |

## 12. Table: GebSafeManager\_event\_ProtectSAFE\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-05 09:16:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14716405                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x03aaf37252558897babf2f8172c5ef719441fe8f69c26caa4fea143918447245 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x3c78a3261457272e9b26af5a9d5c781c5334e802                         |                                                              |
| safe              | VARCHAR   | 489                                                                |                                                              |
| liquidationEngine | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         |                                                              |
| saviour           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 13. Table: GebSafeManager\_event\_QuitSystem\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| safe              | VARCHAR   |                                                              |             |
| dst               | VARCHAR   |                                                              |             |

## 14. Table: GebSafeManager\_event\_TransferCollateral\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| collateralType    | VARCHAR   |                                                              |             |
| safe              | VARCHAR   |                                                              |             |
| dst               | VARCHAR   |                                                              |             |
| wad               | VARCHAR   |                                                              |             |

## 15. Table: GebSafeManager\_event\_TransferInternalCoins\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-16 05:54:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12249325                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4d7d273e395a57c225bc5da80dee2f30d1bb7458b7babfe7c7040dedbb74208e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xefe0b4ca532769a3ae758fd82e1426a03a94f185                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xffa69579bfbc1a2fb7ccf0ea9c4ce4de124d9aac                         |                                                              |
| safe              | VARCHAR   | 42                                                                 |                                                              |
| dst               | VARCHAR   | 0xffa69579bfbc1a2fb7ccf0ea9c4ce4de124d9aac                         |                                                              |
| rad               | VARCHAR   | 200000000000000000000000000000000000000000000000000                |                                                              |

## 16. Table: LiquidationEngine\_event\_Liquidate\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-03-22 10:00:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12087953                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xc84bf207d6d66164dbd6fffb34064af042a9b91e13a196bd7c810e3f153134f6 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 48                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         | Address of the contract that produced the log                |
| collateralType       | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| safe                 | VARCHAR   | 0x5cdc8f2894c503a81d90fdc9b69333c5faa27de3                         |                                                              |
| collateralAmount     | VARCHAR   | 5000000000000000000                                                |                                                              |
| debtAmount           | VARCHAR   | 2035935671313509567352                                             |                                                              |
| amountToRaise        | VARCHAR   | 2040000000000000000000595693274620755795645070848                  |                                                              |
| collateralAuctioneer | VARCHAR   | 0x6d2a73e16c255c1931730b776d96aaff1909322e                         |                                                              |
| auctionId            | VARCHAR   | 104                                                                |                                                              |

## 17. Table: RAI\_call\_burn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-15 03:07:46+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13617873                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x20139c50aa454f383e16093c75434971e9e3e4ebd506992d123080e03b6378a8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 96                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,5,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x03ab458634910aad20ef5f1c8ee96f1d6ac54919                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0x52f6dcc0b2efb3a9e5d5db762f461a818e4c1586                         |                                                                                                                        |
| amount             | VARCHAR   | 2569843817054450256860                                             |                                                                                                                        |

## 18. Table: RAI\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-02 04:21:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14504595                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xde2f93c5041ffabf222504e0dd46e6510d3319276fe85ac34aec1373f8d08b9e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 195                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,8,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x03ab458634910aad20ef5f1c8ee96f1d6ac54919                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| usr                | VARCHAR   | 0x7d7fea3cea7bfa805006b9ce1a842054b8490052                         |                                                                                                                        |
| amount             | VARCHAR   | 4000000000000000000000                                             |                                                                                                                        |

## 19. Table: RAI\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-01 19:53:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16092170                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c4c57bb304743462b46c978952c43c9680a11ff9b7782e811fa162ef824c828 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x03ab458634910aad20ef5f1c8ee96f1d6ac54919                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xcb0c5d9d92f4f2f80cce7aa271a1e148c226e19d                         |                                                              |
| dst               | VARCHAR   | 0x8ae720a71622e824f576b4a8c03031066548a3b1                         |                                                              |
| amount            | VARCHAR   | 716217953989251677229                                              |                                                              |

## 20. Table: SAFEEngine\_event\_ConfiscateSAFECollateralAndDebt\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-06-10 18:00:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 14939827                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xa1c004910b238c7d2a443b3b7f450118b818c6f953a96c7384f975af041c741a | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType         | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| safe                   | VARCHAR   | 0x073ec28e1fc791a4da7c04eec45733ea59eabc54                         |                                                              |
| collateralCounterparty | VARCHAR   | 0x27efc6ffe79692e0521e7e27657cf228240a06c2                         |                                                              |
| debtCounterparty       | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         |                                                              |
| deltaCollateral        | VARCHAR   | -60000000000000000000                                              |                                                              |
| deltaDebt              | VARCHAR   | -24843384747541844867483                                           |                                                              |
| globalUnbackedDebt     | VARCHAR   | 32655206319902851858931793215829434365120046586102                 |                                                              |

## 21. Table: SAFEEngine\_event\_CreateUnbackedDebt\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| debtDestination    | VARCHAR   |                                                              |             |
| coinDestination    | VARCHAR   |                                                              |             |
| rad                | VARCHAR   |                                                              |             |
| debtDstBalance     | VARCHAR   |                                                              |             |
| coinDstBalance     | VARCHAR   |                                                              |             |
| globalUnbackedDebt | VARCHAR   |                                                              |             |
| globalDebt         | VARCHAR   |                                                              |             |

## 22. Table: SAFEEngine\_event\_InitializeCollateralType\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 13:39:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11848573                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7935c32b4b3602f0761587fe1b9011b08a9e163e61fe9064ecfe02b2c8bfbe3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |

## 23. Table: SAFEEngine\_event\_ModifyCollateralBalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-15 23:45:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17702096                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96566be2ff277fedbff93fcc7f0e854f8a8ee21889a9069d8a5da55446d4e85c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0x696d1571ba1be18229f8b32faa8b44dacd96b1c5                         |                                                              |
| wad               | VARCHAR   | -34275411960815804084                                              |                                                              |

## 24. Table: SAFEEngine\_event\_ModifySAFECollateralization\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-22 10:52:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14435668                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x59e30a53b8a50ab2135377e505104b99e25020bfade81e35d264f3c26e329dd3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| safe              | VARCHAR   | 0x2bf9a25c4c868c1b3f4bfafb03f851207e71b285                         |                                                              |
| collateralSource  | VARCHAR   | 0xde723b09ec1266f45d1bbef9d07b31f054ddd7b7                         |                                                              |
| debtDestination   | VARCHAR   | 0xde723b09ec1266f45d1bbef9d07b31f054ddd7b7                         |                                                              |
| deltaCollateral   | VARCHAR   | 28910000000000000000                                               |                                                              |
| deltaDebt         | VARCHAR   | 0                                                                  |                                                              |
| lockedCollateral  | VARCHAR   | 5501910000000000000000                                             |                                                              |
| generatedDebt     | VARCHAR   | 1876065622115453712332540                                          |                                                              |
| globalDebt        | VARCHAR   | 24480880076133133308612906798551643397968092825681376              |                                                              |

## 25. Table: SAFEEngine\_event\_SettleDebt\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-04-03 21:18:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 12168983                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xd151b8e0ea6f43b3455217c6aafb42df6fbc18ddc528fe7d126ff6e1c51c46d4 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 327                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| account            | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         |                                                              |
| rad                | VARCHAR   | 6000429200374285858342000749775368314273311672578                  |                                                              |
| debtBalance        | VARCHAR   | 5603430161389239180606453093315274126512479833728                  |                                                              |
| coinBalance        | VARCHAR   | 190897929663384666985013006578392326218455612394395                |                                                              |
| globalUnbackedDebt | VARCHAR   | 5603430161389239180606453093315274126512479833728                  |                                                              |
| globalDebt         | VARCHAR   | 35502500211264735127101258163239880613622163573372416              |                                                              |

## 26. Table: SAFEEngine\_event\_TransferCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 16:04:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17671444                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04699c69b78bb1c2f5f80ba197a6920ae228191bd5c44c6e39c1bd5c27836c78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 392                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| src               | VARCHAR   | 0x6ea1751c564f3b2d9bba22a234aea05135ca4a19                         |                                                              |
| dst               | VARCHAR   | 0x7f2528313483f6293e068a164d6e49e1e2ca4296                         |                                                              |
| wad               | VARCHAR   | 6500000000000000000                                                |                                                              |

## 27. Table: SAFEEngine\_event\_TransferInternalCoins\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 23:59:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17389362                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9267ed4b1fbb05913a1a2c6f9233a02f6fc1368f750626d815d69c16bd995fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x83533fdd3285f48204215e9cf38c785371258e76                         |                                                              |
| dst               | VARCHAR   | 0x1b988a9bf09a452bf60c139a116580cbcb84bdfb                         |                                                              |
| rad               | VARCHAR   | 4074413192392099645000000000000000000000000000                     |                                                              |

## 28. Table: SAFEEngine\_event\_TransferSAFECollateralAndDebt\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| collateralType      | VARCHAR   |                                                              |             |
| src                 | VARCHAR   |                                                              |             |
| dst                 | VARCHAR   |                                                              |             |
| deltaCollateral     | VARCHAR   |                                                              |             |
| deltaDebt           | VARCHAR   |                                                              |             |
| srcLockedCollateral | VARCHAR   |                                                              |             |
| srcGeneratedDebt    | VARCHAR   |                                                              |             |
| dstLockedCollateral | VARCHAR   |                                                              |             |
| dstGeneratedDebt    | VARCHAR   |                                                              |             |

## 29. Table: SAFEEngine\_event\_UpdateAccumulatedRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-26 10:57:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14080830                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fe428a94ab7cd9f7fd3e007972694c6580a93a0d42b91be004c1295bc984b23 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 263                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc88a9d330da1133df3a7bd823b95e52511a6962                         | Address of the contract that produced the log                |
| collateralType    | VARCHAR   | 0x4554482d41000000000000000000000000000000000000000000000000000000 |                                                              |
| surplusDst        | VARCHAR   | 0xcee6aa1ab47d0fb0f24f51a3072ec16e20f90fce                         |                                                              |
| rateMultiplier    | VARCHAR   | 9624261266448716949                                                |                                                              |
| dstCoinBalance    | VARCHAR   | 533352588956261607773280855764825199919194765912346                |                                                              |
| globalDebt        | VARCHAR   | 22624607827857818804470426275242021635501770333262410              |                                                              |
