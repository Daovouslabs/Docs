# dodo

## 1. Table: DODOPool\_event\_BuyBaseToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-04 14:12:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10795344                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb5a2cc874500b94e20f73945e5fae9aed270728bc048da0809cfc9e4380e1e9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d04146b2fe5d267629a7eb341fb4388dcdbd22f                         | Address of the contract that produced the log                |
| buyer             | VARCHAR   | 0x4063c9ada6758eb625d01baa49c008a8555f989a                         |                                                              |
| receiveBase       | VARCHAR   | 5920000000000000000                                                |                                                              |
| payQuote          | VARCHAR   | 1153934291                                                         |                                                              |

## 2. Table: DODOPool\_event\_ChargeMaintainerFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 02:20:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17788533                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65aae0d261c8fd46776acbd621af029c2e928bfe3857cb3c05898b3911ce0781 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc9f93163c99695c6526b799ebca2207fdf7d61ad                         | Address of the contract that produced the log                |
| maintainer        | VARCHAR   | 0x95c4f5b83aa70810d4f142d58e5f7242bd891cb0                         |                                                              |
| isBaseToken       | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 4320752                                                            |                                                              |

## 3. Table: DODOPool\_event\_ChargePenalty\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 07:42:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16903063                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcab44631737868d41e819f66cc768b929242d6574afd4240f9084b0a6be37047 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x75c23271661d9d143dcb617222bc4bec783eff34                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x4ff54b0422e429b36e4af292734b0c4230c6fa7e                         |                                                              |
| isBaseToken       | VARCHAR   | false                                                              |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 4. Table: DODOPool\_event\_ClaimAssets\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |
| baseTokenAmount   | VARCHAR   |                                                              |             |
| quoteTokenAmount  | VARCHAR   |                                                              |             |

## 5. Table: DODOPool\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-08 09:23:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17002775                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x611d7184becfaf0ddc58d3e639f5766a39116d9ff1fcd90e2572215784abe996 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 242                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc9f93163c99695c6526b799ebca2207fdf7d61ad                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0xa356867fdcea8e71aeaf87805808803806231fdc                         |                                                              |
| receiver          | VARCHAR   | 0x85402d5810d398d923b3fe6a2dbc8d0f46166eac                         |                                                              |
| isBaseToken       | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 118962530000                                                       |                                                              |
| lpTokenAmount     | VARCHAR   | 106539562816                                                       |                                                              |

## 6. Table: DODOPool\_event\_Donate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 22:53:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17851876                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x128e5835181e846c952a7947af3b687199368eda200dde9c45926cad817098aa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc9f93163c99695c6526b799ebca2207fdf7d61ad                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 0                                                                  |                                                              |
| isBaseToken       | VARCHAR   | true                                                               |                                                              |

## 7. Table: DODOPool\_event\_OwnershipTransferPrepared\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 08:35:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11091936                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc8252f6007841a538ef6f4d23d8bf9cf57806cbd48e1dba3d274d6e8437edc3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc226118fcd120634400ce228d61e1538fb21755f                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xf45ce66f2b1cba1793e7c32c4f2d5ca8e566dcc7                         |                                                              |
| newOwner          | VARCHAR   | 0x95c4f5b83aa70810d4f142d58e5f7242bd891cb0                         |                                                              |

## 8. Table: DODOPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-30 16:09:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10763166                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x311a30a13c32db40b1fa3b3a29a6a0d1e0a90912d3894308a5fcbfb7adac8d87 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d04146b2fe5d267629a7eb341fb4388dcdbd22f                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x6dae6ae227438378c117821c51fd61661faa8893                         |                                                              |

## 9. Table: DODOPool\_event\_SellBaseToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 15:44:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16348716                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x42cb6fdf3bf2704b73d6719c8c6204ffa0ee0b54a80693d9d49ef0a24ce2e169 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc9f93163c99695c6526b799ebca2207fdf7d61ad                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x0773edc0438b2ef18fc535b21d0ac77912c308c0                         |                                                              |
| payBase           | VARCHAR   | 40033458690                                                        |                                                              |
| receiveQuote      | VARCHAR   | 40017561295                                                        |                                                              |

## 10. Table: DODOPool\_event\_UpdateGasPriceLimit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-14 05:12:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10656174                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdb7e18c1b45357db3f6d177b640e6ba07d12b410f1a1839d8a03078c1eaeca4c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x75c23271661d9d143dcb617222bc4bec783eff34                         | Address of the contract that produced the log                |
| oldGasPriceLimit  | VARCHAR   | 1000000000000000                                                   |                                                              |
| newGasPriceLimit  | VARCHAR   | 100000000000000                                                    |                                                              |

## 11. Table: DODOPool\_event\_UpdateK\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 08:30:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17740335                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x61998d5325f15f95c2a69756af864e6dadc9886301febd6eddb72861defc93d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 203                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc9f93163c99695c6526b799ebca2207fdf7d61ad                         | Address of the contract that produced the log                |
| oldK              | VARCHAR   | 100000000000000                                                    |                                                              |
| newK              | VARCHAR   | 10000000000000                                                     |                                                              |

## 12. Table: DODOPool\_event\_UpdateLiquidityProviderFeeRate\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2021-04-26 02:10:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 12313171                                                           | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0x17ff56567e4851a4e96eae2454bbaadfb733ec0c3a16a9bac757e6824d66ee7a | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0xc9f93163c99695c6526b799ebca2207fdf7d61ad                         | Address of the contract that produced the log                |
| oldLiquidityProviderFeeRate | VARCHAR   | 100000000000000                                                    |                                                              |
| newLiquidityProviderFeeRate | VARCHAR   | 0                                                                  |                                                              |

## 13. Table: DODOPool\_event\_UpdateMaintainerFeeRate\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-04-27 03:26:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12319958                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x658085a00a91f9a1f256c47ee608c5089a527653998c7f6e3eee8990cf2aaeb5 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 250                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xc9f93163c99695c6526b799ebca2207fdf7d61ad                         | Address of the contract that produced the log                |
| oldMaintainerFeeRate | VARCHAR   | 100000000000000                                                    |                                                              |
| newMaintainerFeeRate | VARCHAR   | 0                                                                  |                                                              |

## 14. Table: DODOPool\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-04 22:26:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12175883                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38d5316cc316594445aaec9c425e6c9a6717c661d867e55efcd7a3c2602a4dc1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 296                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x75c23271661d9d143dcb617222bc4bec783eff34                         | Address of the contract that produced the log                |
| payer             | VARCHAR   | 0x37adc35f7b12582240818df04aac04ca409d5913                         |                                                              |
| receiver          | VARCHAR   | 0x37adc35f7b12582240818df04aac04ca409d5913                         |                                                              |
| isBaseToken       | VARCHAR   | true                                                               |                                                              |
| amount            | VARCHAR   | 300000056776505514889                                              |                                                              |
| lpTokenAmount     | VARCHAR   | 316328696858617653383                                              |                                                              |

## 15. Table: DODOV2Proxy\_call\_createDODOPrivatePool\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-08-29 14:30:51+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13120919                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xcd57db3f10eca940e8552a5ff0ae99e84267faffdb79125d30b51bf910ee491f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 72                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa356867fdcea8e71aeaf87805808803806231fdc                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| baseToken          | VARCHAR   | 0x163c747dbacbec87dbba7c7a8c83dba50d3ef011                         |                                                                                                                        |
| quoteToken         | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                                                                                        |
| baseInAmount       | VARCHAR   | 500000000000000000000000                                           |                                                                                                                        |
| quoteInAmount      | VARCHAR   | 0                                                                  |                                                                                                                        |
| lpFeeRate          | VARCHAR   | 2400000000000000                                                   |                                                                                                                        |
| i                  | VARCHAR   | 200000                                                             |                                                                                                                        |
| k                  | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| isOpenTwap         | VARCHAR   | false                                                              |                                                                                                                        |
| deadLine           | VARCHAR   | 1630251019                                                         |                                                                                                                        |

## 16. Table: DODOZoo\_event\_DODOBirth\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-22 13:54:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11106395                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43c9c32084e7454487130a096491b8b966575465b00782fb3dbb877aaed1f40c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3a97247df274a17c59a3bd12735ea3fcdfb49950                         | Address of the contract that produced the log                |
| newBorn           | VARCHAR   | 0xc9f93163c99695c6526b799ebca2207fdf7d61ad                         |                                                              |
| baseToken         | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| quoteToken        | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |

## 17. Table: DODOZoo\_event\_OwnershipTransferPrepared\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-08 03:55:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10616853                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf6275753f38f05fba3dca8bad3037cb4ff44848d6ebebe3f6ec12b969f066835 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3a97247df274a17c59a3bd12735ea3fcdfb49950                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x9c59990ec0177d87ed7d60a56f584e6b06c639a2                         |                                                              |
| newOwner          | VARCHAR   | 0xef9998dd51b5f75dd40e6ec5c24631b5f0909f0b                         |                                                              |

## 18. Table: DODOZoo\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-14 15:16:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10658870                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2077017941bd991c5066e1e2da3d160d92f67b281ff55c9c0afabe8e709976d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3a97247df274a17c59a3bd12735ea3fcdfb49950                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xef9998dd51b5f75dd40e6ec5c24631b5f0909f0b                         |                                                              |
| newOwner          | VARCHAR   | 0x6dae6ae227438378c117821c51fd61661faa8893                         |                                                              |

## 19. Table: DPPFactoryProxy\_call\_createDODOPrivatePool\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-23 01:13:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17538943                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5dec34ca9d042e377bdb4f48d4ae7a1caa1d6b5b6ca755df644445dc5944607e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 85                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xff7c8f518e6f1435957ed3d3e0692c94676dae7a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| baseToken          | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                                                                                        |
| quoteToken         | VARCHAR   | 0x905f06debcd355809c0eabe2abc1332a5c7159cd                         |                                                                                                                        |
| baseInAmount       | VARCHAR   | 117321803                                                          |                                                                                                                        |
| quoteInAmount      | VARCHAR   | 15000000000000000000000000                                         |                                                                                                                        |
| lpFeeRate          | VARCHAR   | 3000000000000000                                                   |                                                                                                                        |
| i                  | VARCHAR   | 116463984000000000000000000000000                                  |                                                                                                                        |
| k                  | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| isOpenTwap         | VARCHAR   | false                                                              |                                                                                                                        |
| deadLine           | VARCHAR   | 1687486393                                                         |                                                                                                                        |

## 20. Table: DPPFactoryProxy\_createDODOPrivatePool\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-26 01:12:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15614187                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x810203046991fce21427bf311229e25cc31dd3373da8a71b372fd04dca536e34 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 103                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xff7c8f518e6f1435957ed3d3e0692c94676dae7a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| baseToken          | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                                                                                        |
| quoteToken         | VARCHAR   | 0x9d1089802ee608ba84c5c98211afe5f37f96b36c                         |                                                                                                                        |
| baseInAmount       | VARCHAR   | 1000000                                                            |                                                                                                                        |
| quoteInAmount      | VARCHAR   | 1000000                                                            |                                                                                                                        |
| lpFeeRate          | VARCHAR   | 3000000000000000                                                   |                                                                                                                        |
| i                  | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| k                  | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| isOpenTwap         | VARCHAR   | false                                                              |                                                                                                                        |
| deadLine           | VARCHAR   | 1664158341                                                         |                                                                                                                        |

## 21. Table: DPPFactory\_event\_NewDPP\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-10 07:33:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12996079                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1dd1061310157a381138f24444d5a4bc83c5aee370bb8bb880d739bd129ab76c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 299                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6b4fa0bc61eddc928e0df9c7f01e407bfcd3e5ef                         | Address of the contract that produced the log                |
| baseToken         | VARCHAR   | 0x4fabb145d64652a948d72533023f6e7a623c7c53                         |                                                              |
| quoteToken        | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| creator           | VARCHAR   | 0x4239dd663d7b64eb86bc9468d60ca634726c15b7                         |                                                              |
| dpp               | VARCHAR   | 0x877c87d92a67f124336e5ccafe2a9259a8c55b29                         |                                                              |

## 22. Table: DPP\_event\_DODOFlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 10:59:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17031494                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6e1158b3839ce8b4c1790130820e5e61c137d7df47056639cb6004b91e32187 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6e94fddbb7ab473fbf684f882a7a1a5e042b481c                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x9db7378614d8d9d7149c4ee4763f88c38f9b1517                         |                                                              |
| assetTo           | VARCHAR   | 0x9db7378614d8d9d7149c4ee4763f88c38f9b1517                         |                                                              |
| baseAmount        | VARCHAR   | 0                                                                  |                                                              |
| quoteAmount       | VARCHAR   | 116321219                                                          |                                                              |

## 23. Table: DPP\_event\_DODOSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-15 02:53:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13027206                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0fb9977a0b2406c99cc7d09a847676a1e24ceb51fe9de1e754b2706dadee1cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc74eba6863c11266dcffbbf39de34f5845e0ebe4                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| toToken           | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| fromAmount        | VARCHAR   | 34967042440                                                        |                                                              |
| toAmount          | VARCHAR   | 34936293889094960678704                                            |                                                              |
| trader            | VARCHAR   | 0x0bf16c34b38648bb08deacf4dd4b239c44bb33c1                         |                                                              |
| receiver          | VARCHAR   | 0x0bf16c34b38648bb08deacf4dd4b239c44bb33c1                         |                                                              |

## 24. Table: DPSFactory\_call\_createDODOStablePool\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-26 21:36:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16271656                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8938373e3e2098c77488f6f64795d08837995f27f6c3a657e13aae3c60b0b736 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 200                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x6fddb76c93299d985f4d3fc7ac468f9a168577a4                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| baseToken          | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                                                                                        |
| quoteToken         | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                                                                                        |
| lpFeeRate          | VARCHAR   | 0                                                                  |                                                                                                                        |
| i                  | VARCHAR   | 1000000                                                            |                                                                                                                        |
| k                  | VARCHAR   | 0                                                                  |                                                                                                                        |
| isOpenTWAP         | VARCHAR   | false                                                              |                                                                                                                        |

## 25. Table: DPSFactory\_createDODOStablePool\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-06-05 19:55:58+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12576448                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc9d6cb27d7af3f535995810b20f71ca1bd04b7461644246cbd2b8844145ac8b2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 41                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x6fddb76c93299d985f4d3fc7ac468f9a168577a4                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| baseToken          | VARCHAR   | 0x2707ab358b5383d087fe4736da36c1c70179e3bd                         |                                                                                                                        |
| quoteToken         | VARCHAR   | 0xcc7dcc3f649cb3932857d4edc6268e0ef4960995                         |                                                                                                                        |
| lpFeeRate          | VARCHAR   | 0                                                                  |                                                                                                                        |
| i                  | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| k                  | VARCHAR   | 0                                                                  |                                                                                                                        |
| isOpenTWAP         | VARCHAR   | false                                                              |                                                                                                                        |

## 26. Table: DSPFactory\_event\_NewDSP\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-05 17:57:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12575900                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x71428fda42bbe4bfd2c51add8afbe1ef09baca665274a2c51f992e814bb342d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6fddb76c93299d985f4d3fc7ac468f9a168577a4                         | Address of the contract that produced the log                |
| baseToken         | VARCHAR   | 0xcc7dcc3f649cb3932857d4edc6268e0ef4960995                         |                                                              |
| quoteToken        | VARCHAR   | 0x2707ab358b5383d087fe4736da36c1c70179e3bd                         |                                                              |
| creator           | VARCHAR   | 0xc98b29cf037df0f6df6af9b7c96c76c19eb96c1d                         |                                                              |
| DSP               | VARCHAR   | 0xccbb348998d323b7ea338fc4af841a830a9e40c5                         |                                                              |

## 27. Table: DSP\_event\_DODOFlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-31 03:28:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16524122                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7380a6ecc909c494fc538f68fb4e25cbe06779dac08b92a0a2ba307fdddf918 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 777                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3058ef90929cb8180174d74c507176cca6835d73                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x5e9caaf6abd173b908337d433e2b24cca2d6ecf9                         |                                                              |
| assetTo           | VARCHAR   | 0x5e9caaf6abd173b908337d433e2b24cca2d6ecf9                         |                                                              |
| baseAmount        | VARCHAR   | 0                                                                  |                                                              |
| quoteAmount       | VARCHAR   | 201322950628                                                       |                                                              |

## 28. Table: DSP\_event\_DODOSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-28 00:54:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14471574                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x195b18b70c6073ce53357528d74657dfbbba2f3c770a28340d7c96af0b2c86cb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3058ef90929cb8180174d74c507176cca6835d73                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0xdac17f958d2ee523a2206206994597c13d831ec7                         |                                                              |
| toToken           | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| fromAmount        | VARCHAR   | 200000000000                                                       |                                                              |
| toAmount          | VARCHAR   | 200093310832620815800000                                           |                                                              |
| trader            | VARCHAR   | 0x220bda5c8994804ac96ebe4df184d25e5c2196d4                         |                                                              |
| receiver          | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                         |                                                              |

## 29. Table: DVMFactory\_call\_createDODOVendingMachine\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-05 11:27:15+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14326596                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x88b35dd88538f8ba4be42f01d0190c227d15a9a401b5ef2a2cb2c7276ea53f93 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 231                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x72d220ce168c4f361dd4dee5d826a01ad8598f6c                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| baseToken          | VARCHAR   | 0xbc138bd20c98186cc0342c8e380953af0cb48ba8                         |                                                                                                                        |
| quoteToken         | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                                                                                        |
| lpFeeRate          | VARCHAR   | 16000000000000                                                     |                                                                                                                        |
| i                  | VARCHAR   | 280000                                                             |                                                                                                                        |
| k                  | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| isOpenTWAP         | VARCHAR   | false                                                              |                                                                                                                        |

## 30. Table: DVMFactory\_createDODOVendingMachine\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-06-10 10:26:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12606203                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x78ea33a4ff0a6e9372b0166521d7a8371409cc29ea43e84d05aa326315f5924c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 119                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x72d220ce168c4f361dd4dee5d826a01ad8598f6c                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| baseToken          | VARCHAR   | 0x6b9f1c3715f346e42882bc54bab2730db8bddacf                         |                                                                                                                        |
| quoteToken         | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                                                                                        |
| lpFeeRate          | VARCHAR   | 500000000000000                                                    |                                                                                                                        |
| i                  | VARCHAR   | 1000000000                                                         |                                                                                                                        |
| k                  | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| isOpenTWAP         | VARCHAR   | false                                                              |                                                                                                                        |

## 31. Table: DVMFactory\_event\_NewDVM\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-29 03:47:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17149176                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x71170e15ccd716dce6f7c841e885a43d1bd506ce29e85640bd522bf2ec70994a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72d220ce168c4f361dd4dee5d826a01ad8598f6c                         | Address of the contract that produced the log                |
| baseToken         | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| quoteToken        | VARCHAR   | 0x095f2f2c7a145be86638a9bb73a06775ec142cda                         |                                                              |
| creator           | VARCHAR   | 0xddc395ffd8509b957c14d9b87b879fc0619f0fc9                         |                                                              |
| dvm               | VARCHAR   | 0x4ef0480c6f5c7c51d8059bcacfebca79a379bbe8                         |                                                              |

## 32. Table: DVM\_event\_DODOFlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 19:48:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15562613                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xad2cee9beb7271f1a244a298bb075cefe67043bed276c22b0d101e32dd633cbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9fbe3138cc9cd57feef4edb1ef265bb32616a634                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x6c6b87d44d239b3750bf9badce26a9a0a3d2364e                         |                                                              |
| assetTo           | VARCHAR   | 0x6c6b87d44d239b3750bf9badce26a9a0a3d2364e                         |                                                              |
| baseAmount        | VARCHAR   | 0                                                                  |                                                              |
| quoteAmount       | VARCHAR   | 3689214821                                                         |                                                              |

## 33. Table: DVM\_event\_DODOSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 17:32:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15372662                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x190d4b0690f842099ae9b5250091bcd8a5170fc5e96b2eee8bfa3d525f30f4ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 547                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x182d868284b80b2e3175c09e1f88e68cbabc390c                         | Address of the contract that produced the log                |
| fromToken         | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| toToken           | VARCHAR   | 0x2176e2472204901226c05ab7b002728b929950fc                         |                                                              |
| fromAmount        | VARCHAR   | 1833985                                                            |                                                              |
| toAmount          | VARCHAR   | 38268328550887184211                                               |                                                              |
| trader            | VARCHAR   | 0x22f9dcf4647084d6c31b2765f6910cd85c178c18                         |                                                              |
| receiver          | VARCHAR   | 0x22f9dcf4647084d6c31b2765f6910cd85c178c18                         |                                                              |
