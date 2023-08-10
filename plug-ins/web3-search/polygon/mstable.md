# mstable

## 1. Table: EmissionsController\_call\_addRecipient\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-21 15:38:08+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 29833307                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x376bfea199b843467d0977290f966503712454001f35538980a37bfe559e27c5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 42                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,4                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x82182ac492fef111fb458fce8f4228553ed59a19                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_bridgeRecipient  | VARCHAR   | 0x9a718e9b80f7d7006e891051ba4790c6fc839268                         |                                                                                                                        |
| \_endRecipient     | VARCHAR   | 0x1ee5b5acd5253f61fe29531ece4a540c8b8d9efb                         |                                                                                                                        |

## 2. Table: EmissionsController\_call\_distributeRewards\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-03 01:01:03+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 24481897                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x62bd6a46b44647e2c18b3706262d0405b31be06baa82f45625964f298f7f1a28 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 47                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x82182ac492fef111fb458fce8f4228553ed59a19                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_endRecipients    | VARCHAR   | 0x32aBa856Dc5fFd5A56Bcd182b13380e5C855aa29                         |                                                                                                                        |

## 3. Table: EmissionsController\_event\_AddedDial\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-09 11:08:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22314992                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x77db9b29ddce6b31860ca772ddfa965bd09b24da3908af65f9d7cd3de54bf395 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x82182ac492fef111fb458fce8f4228553ed59a19                         | Address of the contract that produced the log                |
| bridgeRecipient   | VARCHAR   | 0xd3778a18ee00a6368a0e5d545cb3412886e5a04c                         |                                                              |
| endRecipient      | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         |                                                              |

## 4. Table: EmissionsController\_event\_DistributedReward\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-01 01:31:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32536896                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x95f35c9678b0b01e9a82e1c8ddbabf0e16165902e70e77db2664ebd3cffb17e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 467                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x82182ac492fef111fb458fce8f4228553ed59a19                         | Address of the contract that produced the log                |
| endRecipient      | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         |                                                              |
| amount            | VARCHAR   | 11074713115349294537923                                            |                                                              |

## 5. Table: FeederPoolMUSDFRAX\_call\_mintMulti\_history

| Column              | Type      | Example                                                                               | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2021-12-02 10:14:39+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 22045446                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x59cc500b8a757b85eac243b5db2303104ae8b95325d807f22a129c3c2e9c74fd                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 104                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                                            | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| \_inputs            | VARCHAR   | 0xE840B73E5287865EEc17d250bFb1536704B43B21,0x104592a158490a9228070E0A8e5343B499e125D0 |                                                                                                                        |
| \_inputQuantities   | VARCHAR   | 2063009285965103986,2057099886029535001                                               |                                                                                                                        |
| \_minOutputQuantity | VARCHAR   | 4111585594517006115                                                                   |                                                                                                                        |
| \_recipient         | VARCHAR   | 0xe480d5db1a9068bc31eddb795ca4bc358ccc2f40                                            |                                                                                                                        |

## 6. Table: FeederPoolMUSDFRAX\_call\_mint\_history

| Column              | Type      | Example                                                            | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2021-09-04 02:24:57+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 18722334                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xaaf59758e2cefa434e67a7d116a5b1f59a2a3497972d9ea47c2999e6e0f102cf | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 15                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_input             | VARCHAR   | 0x104592a158490a9228070e0a8e5343b499e125d0                         |                                                                                                                        |
| \_inputQuantity     | VARCHAR   | 4649731402524453353                                                |                                                                                                                        |
| \_minOutputQuantity | VARCHAR   | 4641483097246330125                                                |                                                                                                                        |
| \_recipient         | VARCHAR   | 0x140910281bc93afc0b6d359b3045bb107aae4b53                         |                                                                                                                        |

## 7. Table: FeederPoolMUSDFRAX\_call\_redeemExactBassets\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-10 04:52:33+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 21195804                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x27155b305aefec6edfdbeb6e2d9c8e0a553bc3c55cf009a285ff8a18f29a622b                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 145                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| \_outputs          | VARCHAR   | 0xE840B73E5287865EEc17d250bFb1536704B43B21,0x104592a158490a9228070E0A8e5343B499e125D0 |                                                                                                                        |
| \_outputQuantities | VARCHAR   | 6930000000000000000000,6940000000000000000000                                         |                                                                                                                        |
| \_maxInputQuantity | VARCHAR   | 13877982138990719249705                                                               |                                                                                                                        |
| \_recipient        | VARCHAR   | 0x48dbd1c8c3a7d1e6c8e0b21090f41c7c46c6e791                                            |                                                                                                                        |

## 8. Table: FeederPoolMUSDFRAX\_call\_redeemProportionately\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-05-24 19:57:14+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 43103171                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0x206bf5b22548bbc9664c59fceaef4f72d6d7a7fdc32d35a9f8ff0f20301fb51b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 37                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | 2,0,3                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_inputQuantity       | VARCHAR   | 4722735739465716903002                                             |                                                                                                                        |
| \_minOutputQuantities | VARCHAR   | 2337417001959038166380,2394876460540258285980                      |                                                                                                                        |
| \_recipient           | VARCHAR   | 0xdcb5a4b6ee39447d700f4fa3303b1d1c25ea9ca7                         |                                                                                                                        |

## 9. Table: FeederPoolMUSDFRAX\_call\_redeem\_history

| Column              | Type      | Example                                                            | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2022-04-06 01:12:55+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 26794626                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xc85352c0745c930e46f893de2e9ae41cc7021703536144b5dc80a9cb1409696f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 39                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_output            | VARCHAR   | 0xc2132d05d31c914a87c6611c10748aeb04b58e8f                         |                                                                                                                        |
| \_fpTokenQuantity   | VARCHAR   | 499997001916863148752                                              |                                                                                                                        |
| \_minOutputQuantity | VARCHAR   | 499501214                                                          |                                                                                                                        |
| \_recipient         | VARCHAR   | 0xee49d450de2f5ce95e5f1043aa45f572cd2ace40                         |                                                                                                                        |

## 10. Table: FeederPoolMUSDFRAX\_call\_swap\_history

| Column              | Type      | Example                                                            | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-06-07 07:06:06+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 43626696                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x098a9110e3d1aff737ba356ef7bb65e1ce8e6c7ab60733562b55ea5eedca07ed | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 49                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | 0,9,1,0,2                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_input             | VARCHAR   | 0x104592a158490a9228070e0a8e5343b499e125d0                         |                                                                                                                        |
| \_output            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_inputQuantity     | VARCHAR   | 206646206873482161987                                              |                                                                                                                        |
| \_minOutputQuantity | VARCHAR   | 204376765                                                          |                                                                                                                        |
| \_recipient         | VARCHAR   | 0x1111111254eeb25477b68fb85ed929f73a960582                         |                                                                                                                        |

## 11. Table: FeederPoolMUSDFRAX\_event\_MintedMulti\_history

| Column            | Type      | Example                                                                               | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-09 20:30:15+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21181931                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea7674f27727e4c2186889845eaf9661825a266a1fb477e4065faa4911547aa4                    | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 208                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                                            | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x1109297e392d92c1613fdbdf30579a0215c20da9                                            |                                                              |
| recipient         | VARCHAR   | 0x1109297e392d92c1613fdbdf30579a0215c20da9                                            |                                                              |
| output            | VARCHAR   | 152810958069839634117779                                                              |                                                              |
| inputs            | VARCHAR   | 0xE840B73E5287865EEc17d250bFb1536704B43B21,0x104592a158490a9228070E0A8e5343B499e125D0 |                                                              |
| inputQuantities   | VARCHAR   | 150381623092238315004738,2598377958435923760612                                       |                                                              |

## 12. Table: FeederPoolMUSDFRAX\_event\_Minted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-01 22:45:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22027794                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ad54a94261f5cb03a4a6b472374a8c0ae3fd438f53eafff71f7d3f238973db3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 569                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0x0a185251038cc4921d20697f0a63e1c8ab5dfb9c                         |                                                              |
| recipient         | VARCHAR   | 0x0a185251038cc4921d20697f0a63e1c8ab5dfb9c                         |                                                              |
| output            | VARCHAR   | 688075763560862431516                                              |                                                              |
| input             | VARCHAR   | 0x104592a158490a9228070e0a8e5343b499e125d0                         |                                                              |
| inputQuantity     | VARCHAR   | 688912293523070322883                                              |                                                              |

## 13. Table: FeederPoolMUSDFRAX\_event\_RedeemedMulti\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-08 17:32:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28080253                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5b81a85263ce716b910e1c0030cfc9c1af8027c5096099e411ccdd4c9de885a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x48dbd1c8c3a7d1e6c8e0b21090f41c7c46c6e791                         |                                                              |
| recipient         | VARCHAR   | 0x48dbd1c8c3a7d1e6c8e0b21090f41c7c46c6e791                         |                                                              |
| mAssetQuantity    | VARCHAR   | 8395999999999999500801                                             |                                                              |
| outputs           | VARCHAR   | 0x104592a158490a9228070E0A8e5343B499e125D0                         |                                                              |
| outputQuantity    | VARCHAR   | 8415385386827536000000                                             |                                                              |
| scaledFee         | VARCHAR   | 5037599999999999700                                                |                                                              |

## 14. Table: FeederPoolMUSDFRAX\_event\_Redeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-15 22:32:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39335974                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e9a1d7348fa0063561c0ad826d17eeb1b7bb3f8cbce7da28c116aa561ea22c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 268                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x6103d850a37ef5f829b3a8214b5edafb76bf692d                         |                                                              |
| recipient         | VARCHAR   | 0x6103d850a37ef5f829b3a8214b5edafb76bf692d                         |                                                              |
| mAssetQuantity    | VARCHAR   | 3026768795702890452226                                             |                                                              |
| output            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| outputQuantity    | VARCHAR   | 3029224640                                                         |                                                              |
| scaledFee         | VARCHAR   | 1816061277421734271                                                |                                                              |

## 15. Table: FeederPoolMUSDFRAX\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 08:56:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43629718                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05cd96bb0008babc624c9520828ae707a730eb9ab8e712210d90a3ac681f6a41 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 375                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the contract that produced the log                |
| swapper           | VARCHAR   | 0xb97cd69145e5a9357b2acd6af6c5076380f17afb                         |                                                              |
| input             | VARCHAR   | 0x104592a158490a9228070e0a8e5343b499e125d0                         |                                                              |
| output            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| outputAmount      | VARCHAR   | 20106001                                                           |                                                              |
| fee               | VARCHAR   | 0                                                                  |                                                              |
| recipient         | VARCHAR   | 0x1111111254eeb25477b68fb85ed929f73a960582                         |                                                              |

## 16. Table: FeederPoolMUSDFRAX\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 19:51:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19180534                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98867fcc9a0a6cebcb089c9e14c629b8854594c0d314a6ad9991bc9ee407a326 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 226                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x1fd6f8ab8f7c74cc86c2d7267e9e2e3c5fe2825e                         |                                                              |
| value             | VARCHAR   | 47184528068594980522                                               |                                                              |

## 17. Table: Liquidator\_event\_Liquidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-30 09:37:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13912319                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32e164f28c1785d36189a607af149f80d1c733e0dee4b18c089e4cb94aed9e8f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 168                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9f1c06cc13edc7691a2cf02e31faaa64d57867e2                         | Address of the contract that produced the log                |
| sellToken         | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| mUSD              | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                              |
| mUSDAmount        | VARCHAR   | 1533545147196530613643                                             |                                                              |
| buyToken          | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |

## 18. Table: MTA\_call\_deposit\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| user               | VARCHAR   |                                                                                                                        |             |
| depositData        | VARCHAR   |                                                                                                                        |             |

## 19. Table: MTA\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-08 08:45:49+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 44824631                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xca7061d9dcb3dd92dbbbcf596d8992734fde651593b22061e6793b4fde9673a4 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 2                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf501dd45a1198c2e1b5aef5314a68b9006d842e0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 10858448166343714203940                                            |                                                                                                                        |

## 20. Table: MTA\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 21:44:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24671182                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe26d31e46f0094d8acdf2b4ffb085710d2cab2857a77a50cdf016a9b669d7071 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 464                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf501dd45a1198c2e1b5aef5314a68b9006d842e0                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc425fd9ed3c892d849c9e1a971516da1c1b29696                         |                                                              |
| to                | VARCHAR   | 0x050ca83267e499abafaae55262afe35a21d90476                         |                                                              |
| value             | VARCHAR   | 50854333234                                                        |                                                              |

## 21. Table: MUSD\_call\_getBasset\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-06-24 15:38:21+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16099014                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x98bdb8a9470c5c6b6cbb8a77b0e0bb2fc4c07dbc133a668b8d744f823c345682 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 60                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,4                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_bAsset           | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                                                                                        |

## 22. Table: MUSD\_call\_getMintMultiOutput\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_inputs           | VARCHAR   |                                                                                                                        |             |
| \_inputQuantities  | VARCHAR   |                                                                                                                        |             |

## 23. Table: MUSD\_call\_getMintOutput\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-25 11:09:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 25320216                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x0282c92a3b0b7d0e5bd990e0e8ae96480d6886309fbd4aa6ccdcd5fe0b3e6b4d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 30                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,0,0,0,0,0,50,0                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_input            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_inputQuantity    | VARCHAR   | 1000000                                                            |                                                                                                                        |

## 24. Table: MUSD\_call\_getRedeemExactBassetsOutput\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-14 16:22:22+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 25939119                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x29b1fc726c305ec27f00df61c7ee4dd9ba8aee60819e64b4438e15a9a4a77e92 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 8                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_outputs          | VARCHAR   | 0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174                         |                                                                                                                        |
| \_outputQuantities | VARCHAR   | 3997534                                                            |                                                                                                                        |

## 25. Table: MUSD\_call\_getRedeemOutput\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-19 10:15:58+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 34532960                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xde151891dc564f72883a1fad9ce98779a3e707f41dfbf765ffff1c72bbd3586b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 9                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 38                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_output           | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_mAssetQuantity   | VARCHAR   | 584437308230396646187828                                           |                                                                                                                        |

## 26. Table: MUSD\_call\_getSwapOutput\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-21 12:45:30+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 27401863                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xee9c44d71bb92f908acbbbe535b53d94e06fbe9ebe9a24cd0e1cac8341e1e89f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 20                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,0,4,1,0                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_input            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_output           | VARCHAR   | 0xc2132d05d31c914a87c6611c10748aeb04b58e8f                         |                                                                                                                        |
| \_inputQuantity    | VARCHAR   | 1740421846                                                         |                                                                                                                        |

## 27. Table: MUSD\_call\_migrateBassets\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_bAssets          | VARCHAR   |                                                                                                                        |             |
| \_newIntegration   | VARCHAR   |                                                                                                                        |             |

## 28. Table: MUSD\_call\_mintDeficit\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |

## 29. Table: MUSD\_call\_mintMulti\_history

| Column              | Type      | Example                                                                               | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2021-07-16 19:32:36+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16933865                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xc2acb5830b2c1fbd4731d047eb06c16dcc7813534d585f91405b6c4d86c45e48                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 81                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                                            | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| \_inputs            | VARCHAR   | 0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174,0x8f3Cf7ad23Cd3CaDbD9735AFf958023239c6A063 |                                                                                                                        |
| \_inputQuantities   | VARCHAR   | 196500000,498477388870800232110                                                       |                                                                                                                        |
| \_minOutputQuantity | VARCHAR   | 694428522085500958383                                                                 |                                                                                                                        |
| \_recipient         | VARCHAR   | 0x381ecab70a94a4436c7a4fc34210a758dde06834                                            |                                                                                                                        |

## 30. Table: MUSD\_call\_mint\_history

| Column              | Type      | Example                                                            | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2021-06-29 14:20:27+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16289941                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x76bdfe311210fbff18b40e324db381c28736fbb3cfc2daa25f48e55ea10431dd | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 134                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_input             | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_inputQuantity     | VARCHAR   | 7155239                                                            |                                                                                                                        |
| \_minOutputQuantity | VARCHAR   | 7146079081937274147                                                |                                                                                                                        |
| \_recipient         | VARCHAR   | 0x299081f52738a4204c3d58264ff44f6f333c6c88                         |                                                                                                                        |

## 31. Table: MUSD\_call\_redeemExactBassets\_history

| Column              | Type      | Example                                                                               | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2021-07-12 20:53:32+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16792332                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x2857b831448ec7c46faba237cbd62818028415ac2974277046afad9300188096                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 147                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                                            | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| \_outputs           | VARCHAR   | 0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174,0x8f3Cf7ad23Cd3CaDbD9735AFf958023239c6A063 |                                                                                                                        |
| \_outputQuantities  | VARCHAR   | 175800000,176410000000000000000                                                       |                                                                                                                        |
| \_maxMassetQuantity | VARCHAR   | 352793880998330962484                                                                 |                                                                                                                        |
| \_recipient         | VARCHAR   | 0x09bbece6eb582e760dfb8a90969e7afa0d2abf02                                            |                                                                                                                        |

## 32. Table: MUSD\_call\_redeemMasset\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-06-10 15:15:48+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 43755351                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0xeb81102a5f93b86ea2ba8e6cbedc937582e05ccd9f3d7ad38ee95c3944b0f7b8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 53                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_mAssetQuantity      | VARCHAR   | 104534401464533662858680                                           |                                                                                                                        |
| \_minOutputQuantities | VARCHAR   | 35995228171,39399130761985884752444,29021170450                    |                                                                                                                        |
| \_recipient           | VARCHAR   | 0x871dbc800563f03bc58a88f699a6b28b7d33bfb7                         |                                                                                                                        |

## 33. Table: MUSD\_call\_redeem\_history

| Column              | Type      | Example                                                            | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2021-06-19 13:55:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 15901266                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0xf04a602fd8977f6c7178ca6a75f4585ee9b2527562ec60302adb343bb003149e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 32                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_output            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_mAssetQuantity    | VARCHAR   | 2416043442924701727338                                             |                                                                                                                        |
| \_minOutputQuantity | VARCHAR   | 2413985431                                                         |                                                                                                                        |
| \_recipient         | VARCHAR   | 0xab41783b2e59c5485e891e6f5d312022d7dcf812                         |                                                                                                                        |

## 34. Table: MUSD\_call\_setFees\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-15 10:48:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 24967523                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x0ca42314de823e0bb35ae9d5bc1a1a9d08f813369d17da113bf70f481b23ddf1 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 53                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,4                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_swapFee          | VARCHAR   | 200000000000000                                                    |                                                                                                                        |
| \_redemptionFee    | VARCHAR   | 200000000000000                                                    |                                                                                                                        |

## 35. Table: MUSD\_call\_setTransferFeesFlag\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_bAsset           | VARCHAR   |                                                                                                                        |             |
| \_flag             | VARCHAR   |                                                                                                                        |             |

## 36. Table: MUSD\_call\_swap\_history

| Column              | Type      | Example                                                            | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2021-06-30 03:40:56+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16311851                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x36bacb854b5516e4367dd8372b16d615f8d7f492729e92ca5af80584aaa3bc75 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 7                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_input             | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                                                                                        |
| \_output            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_inputQuantity     | VARCHAR   | 1647225389459309858662                                             |                                                                                                                        |
| \_minOutputQuantity | VARCHAR   | 1645890558                                                         |                                                                                                                        |
| \_recipient         | VARCHAR   | 0x0a474c5ad18d20441dc78f8e0f0731b3def9b54d                         |                                                                                                                        |

## 37. Table: MUSD\_event\_DeficitMinted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| amt               | VARCHAR   |                                                              |             |

## 38. Table: MUSD\_event\_FeesChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-15 10:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24967523                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ca42314de823e0bb35ae9d5bc1a1a9d08f813369d17da113bf70f481b23ddf1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the contract that produced the log                |
| swapFee           | VARCHAR   | 200000000000000                                                    |                                                              |
| redemptionFee     | VARCHAR   | 200000000000000                                                    |                                                              |

## 39. Table: MUSD\_event\_MintedMulti\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 15:09:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24660390                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9707f773c5a9ad8f3b0b68851f4971fe0e6cac343a7a40b0906ff41be59fb406 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 293                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                              |
| recipient         | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         |                                                              |
| mAssetQuantity    | VARCHAR   | 13500144122591218598                                               |                                                              |
| inputs            | VARCHAR   |                                                                    |                                                              |
| inputQuantities   | VARCHAR   |                                                                    |                                                              |

## 40. Table: MUSD\_event\_Minted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 00:06:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38683906                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0734257091915d5cf311a30097e336181919525155c47b5950d8fc242cd023f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the contract that produced the log                |
| minter            | VARCHAR   | 0xc657b9bf61e928e3114faf8aa269beb9a29105b1                         |                                                              |
| recipient         | VARCHAR   | 0xc657b9bf61e928e3114faf8aa269beb9a29105b1                         |                                                              |
| mAssetQuantity    | VARCHAR   | 6544761251884568721                                                |                                                              |
| input             | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                              |
| inputQuantity     | VARCHAR   | 6545472829742933208                                                |                                                              |

## 41. Table: MUSD\_event\_RedeemedMulti\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-29 04:55:42+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13863210                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc82fc7ddf8ccaf584c598562c2b69d76541e8a10040e56c494248f89e5b41096                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                                                           | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xc35ab820c9acefadfd96b4f4ea03a97c70a2d2ac                                                           |                                                              |
| recipient         | VARCHAR   | 0xc35ab820c9acefadfd96b4f4ea03a97c70a2d2ac                                                           |                                                              |
| mAssetQuantity    | VARCHAR   | 1998168927128176141821120                                                                            |                                                              |
| outputs           | VARCHAR   | 0x2791Bca1f2de4661ED88A30C99A7a9449Aa84174,0x8f3Cf7ad23Cd3CaDbD9735AFf958023239c6A063,0xc2132D05D31c |                                                              |
| outputQuantity    | VARCHAR   | 670000000000,607000000000000000000000,720000000000                                                   |                                                              |
| scaledFee         | VARCHAR   | 1198901356276905685092                                                                               |                                                              |

## 42. Table: MUSD\_event\_Redeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-08 17:14:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14250329                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb512eb87cd50620f12449d641b89522029fddb3c381b32c9e2f52ef052cadaab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0xabf7135fe323aed91ce92efe80381b1587aa7f65                         |                                                              |
| recipient         | VARCHAR   | 0xabf7135fe323aed91ce92efe80381b1587aa7f65                         |                                                              |
| mAssetQuantity    | VARCHAR   | 9967469082956610786099                                             |                                                              |
| output            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| outputQuantity    | VARCHAR   | 9966465673                                                         |                                                              |
| scaledFee         | VARCHAR   | 5980481449773966471                                                |                                                              |

## 43. Table: MUSD\_event\_SurplusBurned\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| creditor          | VARCHAR   |                                                              |             |
| amt               | VARCHAR   |                                                              |             |

## 44. Table: MUSD\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 13:40:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35639190                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4342b3f14d779ac80f4fbdbc2ae16a1e1d823e3b41f5c07d18fa1e8b56b264b5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the contract that produced the log                |
| swapper           | VARCHAR   | 0x0d15038f8a0362b4ce71d6c879d56bf9fc2884cf                         |                                                              |
| input             | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| output            | VARCHAR   | 0xc2132d05d31c914a87c6611c10748aeb04b58e8f                         |                                                              |
| outputAmount      | VARCHAR   | 5005531556                                                         |                                                              |
| scaledFee         | VARCHAR   | 1000504438864564722                                                |                                                              |
| recipient         | VARCHAR   | 0x0d15038f8a0362b4ce71d6c879d56bf9fc2884cf                         |                                                              |

## 45. Table: MUSD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 13:52:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27050004                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x34b2b499e512dc0f1896c74e3d843f55e1b68bd5ea0e5934f0f2be3c02ae01db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xb30a907084ac8a0d25dddab4e364827406fd09f0                         |                                                              |
| value             | VARCHAR   | 10031220660092073781775                                            |                                                              |

## 46. Table: PAaveIntegration\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-29 20:29:24+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 27729323                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xdd7c126f8edd6da93385bea94711e9e70abdafdb1c1981fe8c2f48f026c4996c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 74                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,1,0,0,3                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xeab7831c96876433db9b8953b4e7e8f66c3125c3                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_bAsset           | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                                                                                        |
| \_amount           | VARCHAR   | 1052193133311527417588                                             |                                                                                                                        |
| \_hasTxFee         | VARCHAR   | false                                                              |                                                                                                                        |

## 47. Table: PAaveIntegration\_call\_setPTokenAddress\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_bAsset           | VARCHAR   |                                                                                                                        |             |
| \_pToken           | VARCHAR   |                                                                                                                        |             |

## 48. Table: PAaveIntegration\_call\_withdrawRaw\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_receiver         | VARCHAR   |                                                                                                                        |             |
| \_bAsset           | VARCHAR   |                                                                                                                        |             |
| \_amount           | VARCHAR   |                                                                                                                        |             |

## 49. Table: PAaveIntegration\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-11 12:45:06+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 23594640                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9c8f972e5950c58047d21b88710ead8caa3eddafed62afcbf739028035ee3e8c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 44                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xeab7831c96876433db9b8953b4e7e8f66c3125c3                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_receiver         | VARCHAR   | 0x8d72a9bebbd5160fbd61e57bcca7810b9f2d1d86                         |                                                                                                                        |
| \_bAsset           | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_amount           | VARCHAR   | 108671158101                                                       |                                                                                                                        |
| \_totalAmount      | VARCHAR   | 108671158101                                                       |                                                                                                                        |
| \_hasTxFee         | VARCHAR   | false                                                              |                                                                                                                        |

## 50. Table: PAaveIntegration\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-27 18:57:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43220062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3401e2ada480beda831e371dc247ae5f02f70795f919378961c697359d1b981a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeab7831c96876433db9b8953b4e7e8f66c3125c3                         | Address of the contract that produced the log                |
| \_bAsset          | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                              |
| \_pToken          | VARCHAR   | 0x27f8d03b3a2196956ed754badc28d73be8830a6e                         |                                                              |
| \_amount          | VARCHAR   | 13200000000000000000000                                            |                                                              |

## 51. Table: PAaveIntegration\_event\_PTokenAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-23 12:48:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13630660                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x855b72634b54a76584d7e8acebd7e60f16ad1d6c8569d66dde687579ad4cac9f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeab7831c96876433db9b8953b4e7e8f66c3125c3                         | Address of the contract that produced the log                |
| \_bAsset          | VARCHAR   | 0xc2132d05d31c914a87c6611c10748aeb04b58e8f                         |                                                              |
| \_pToken          | VARCHAR   | 0x60d55f02a771d515e077c9c2403a1ef324885cec                         |                                                              |

## 52. Table: PAaveIntegration\_event\_PlatformWithdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-27 18:39:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19582467                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdbd29817254d1d96eac8e5e77e2d6704d47f39818427b1a72ff45a07f1e6ed19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 104                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeab7831c96876433db9b8953b4e7e8f66c3125c3                         | Address of the contract that produced the log                |
| bAsset            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| pToken            | VARCHAR   | 0x1a13f4ca1d028320a707d99520abfefca3998b7f                         |                                                              |
| totalAmount       | VARCHAR   | 101032171862                                                       |                                                              |
| userAmount        | VARCHAR   | 101032171862                                                       |                                                              |

## 53. Table: PAaveIntegration\_event\_RewardTokenApproved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-24 13:51:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13673228                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d6a6df0ff2f9c2bad0063a0171a70563eaeefb54ec37b40672bd30d11dfefbb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeab7831c96876433db9b8953b4e7e8f66c3125c3                         | Address of the contract that produced the log                |
| rewardToken       | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| account           | VARCHAR   | 0x9f1c06cc13edc7691a2cf02e31faaa64d57867e2                         |                                                              |

## 54. Table: PAaveIntegration\_event\_RewardsClaimed\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-08 07:45:59+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14234264                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe0da3451d300c885ef9149580f006c6dc01069f80b99053648a62ce7b95ebb8                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeab7831c96876433db9b8953b4e7e8f66c3125c3                                                           | Address of the contract that produced the log                |
| assets            | VARCHAR   | 0x1a13F4Ca1d028320A707D99520AbFefca3998b7F,0x27F8D03b3a2196956ED754baDc28D73be8830A6e,0x60D55F02A771 |                                                              |
| amount            | VARCHAR   | 488150069073070218539                                                                                |                                                              |

## 55. Table: PAaveIntegration\_event\_Withdrawal\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_bAsset          | VARCHAR   |                                                              |             |
| \_pToken          | VARCHAR   |                                                              |             |
| \_amount          | VARCHAR   |                                                              |             |

## 56. Table: SaveWrapper\_call\_saveAndStake\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_mAsset           | VARCHAR   |                                                                                                                        |             |
| \_save             | VARCHAR   |                                                                                                                        |             |
| \_vault            | VARCHAR   |                                                                                                                        |             |
| \_amount           | VARCHAR   |                                                                                                                        |             |
| \_referrer         | VARCHAR   |                                                                                                                        |             |

## 57. Table: SaveWrapper\_call\_saveViaMint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-28 17:56:56+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 27685794                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbf9e307d80fb22665d3733df032b79bae4becbe63bf09f49e21a900050161fce | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xfd8932f4887e39d8eed05dc407924124026bd902                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_mAsset           | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                                                                                        |
| \_save             | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         |                                                                                                                        |
| \_vault            | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         |                                                                                                                        |
| \_bAsset           | VARCHAR   | 0x8f3cf7ad23cd3cadbd9735aff958023239c6a063                         |                                                                                                                        |
| \_amount           | VARCHAR   | 10000000000000000                                                  |                                                                                                                        |
| \_minOut           | VARCHAR   | 1000000000000000                                                   |                                                                                                                        |
| \_stake            | VARCHAR   | true                                                               |                                                                                                                        |
| \_referrer         | VARCHAR   | 0xe0ee7fec8ec7eb5e88f1dbbfe3e0681cc49f6499                         |                                                                                                                        |

## 58. Table: SaveWrapper\_call\_saveViaSwap\_history

| Column              | Type      | Example                                                                                                                | Description |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number       | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index  | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address      | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address         | VARCHAR   | Address of the called contract                                                                                         |             |
| status              | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error               | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_mAsset            | VARCHAR   |                                                                                                                        |             |
| \_save              | VARCHAR   |                                                                                                                        |             |
| \_vault             | VARCHAR   |                                                                                                                        |             |
| \_feeder            | VARCHAR   |                                                                                                                        |             |
| \_fAsset            | VARCHAR   |                                                                                                                        |             |
| \_fAssetQuantity    | VARCHAR   |                                                                                                                        |             |
| \_minOutputQuantity | VARCHAR   |                                                                                                                        |             |
| \_stake             | VARCHAR   |                                                                                                                        |             |

## 59. Table: SaveWrapper\_call\_saveViaUniswapETH\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_mAsset           | VARCHAR   |                                                                                                                        |             |
| \_save             | VARCHAR   |                                                                                                                        |             |
| \_vault            | VARCHAR   |                                                                                                                        |             |
| \_uniswap          | VARCHAR   |                                                                                                                        |             |
| \_amountOutMin     | VARCHAR   |                                                                                                                        |             |
| \_path             | VARCHAR   |                                                                                                                        |             |
| \_minOutMStable    | VARCHAR   |                                                                                                                        |             |
| \_stake            | VARCHAR   |                                                                                                                        |             |

## 60. Table: SavingsManager\_call\_collectAndDistributeInterest\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-01 06:01:39+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 22002138                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1b6a65627ffe04bb4b932933f6738434a035341b00a5e916f5be30e7663cb138 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 152                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_mAsset           | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                                                                                        |

## 61. Table: SavingsManager\_call\_collectAndStreamInterest\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-11 23:56:07+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 24832026                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9de102be19da550f9c5b2f1ff4be3808247c67793202942bad6ef4c1149f4ab5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 35                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_mAsset           | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                                                                                        |

## 62. Table: SavingsManager\_call\_depositLiquidation\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-12-26 22:58:02+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 23001693                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xd06e3fabc9e213e421d96409805389a36d8a7b161b4a745ae1101c0bbbead623 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 18                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_mAsset           | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                                                                                        |
| \_liquidated       | VARCHAR   | 1936383699482083558345                                             |                                                                                                                        |

## 63. Table: SavingsManager\_call\_distributeUnallocatedInterest\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-09 06:27:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 41318834                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa61e3b116e8d58699e3eef84c276c5e4d51ca42be478a0f00a4c2751a0e5d8b4 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 22                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_mAsset           | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                                                                                        |

## 64. Table: SavingsManager\_event\_InterestCollected\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-13 09:44:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17934782                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19c31ad76f8c217d4cddb2d9778b82e8879d35ea6083dd05eeb06a695a8ed58f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         | Address of the contract that produced the log                |
| mAsset            | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                              |
| interest          | VARCHAR   | 0                                                                  |                                                              |
| newTotalSupply    | VARCHAR   | 14470433457034511831078609                                         |                                                              |
| apy               | VARCHAR   | 0                                                                  |                                                              |

## 65. Table: SavingsManager\_event\_InterestDistributed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-17 07:39:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18075345                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc5337ebdf7c5e0ffb819886ba353be2cb1a9fd45f7b334618b69eecdf49996b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         | Address of the contract that produced the log                |
| mAsset            | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                              |
| amountSent        | VARCHAR   | 55301531206933666                                                  |                                                              |

## 66. Table: SavingsManager\_event\_LiquidatorDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-17 04:25:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14590759                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0520da7eec7d17ff0a078d453e69ec756e7cf74c88bf573a526540e05f5fd6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         | Address of the contract that produced the log                |
| mAsset            | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                              |
| amount            | VARCHAR   | 191138702008187721250                                              |                                                              |

## 67. Table: SavingsManager\_event\_RevenueRedistributed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-22 06:23:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22818081                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa589a11d43c8adda86d1d3b87a3591c86fccdf9b1e92fa449e5df20f147e0ea4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x10bfccae079f31c451033798a4fd9d2c33ea5487                         | Address of the contract that produced the log                |
| mAsset            | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                              |
| recipient         | VARCHAR   | 0x4845a90664311f9f0c8cdb5d9b95bb0937863380                         |                                                              |
| amount            | VARCHAR   | 27133294566308218822982                                            |                                                              |

## 68. Table: imUSDVault\_call\_claimRewardOnly\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-10 14:44:14+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 43754463                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf295326436b936badac9e72f065c0afea9a0679c09fa33926ae8f26bf4930fdb | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 55                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 69. Table: imUSDVault\_call\_claimReward\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-03 15:48:48+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 32643989                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3805e749a6bbc3ebf60504705a2a41eca785e7072f593564e631847ffb59d714 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 24                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 70. Table: imUSDVault\_call\_exit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-23 17:50:28+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 25265533                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xd07ad6c242b9746479a4e42e45ad8744c890475da0c556ded2c8365e190fd9fb | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 1                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 71. Table: imUSDVault\_call\_stake\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-08 23:00:15+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 36595181                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x279c14cd7e761901d57fcb5cc92b63e47917733a4de3adb2e0a0c829fab26602 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 61                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 5,14                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_beneficiary      | VARCHAR   | 0xabf94c1f5f2bdcf20f29fde4279d189b77910b3f                         |                                                                                                                        |
| \_amount           | VARCHAR   | 1441315230242966                                                   |                                                                                                                        |

## 72. Table: imUSDVault\_call\_withdrawAndUnwrap\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-24 17:56:05+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 25297536                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x363f00a31d7c5fd694c71097b015f6fb091b2f075fceb5c7f91ab8c9d69f5f82 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 113                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 17122442635753385173325                                            |                                                                                                                        |
| \_minAmountOut     | VARCHAR   | 1875123801                                                         |                                                                                                                        |
| \_output           | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_beneficiary      | VARCHAR   | 0xf2b8c142edcf2f3cc22665cce863a7c9a3e9f156                         |                                                                                                                        |
| \_router           | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                                                                                        |
| \_isBassetOut      | VARCHAR   | true                                                               |                                                                                                                        |

## 73. Table: imUSDVault\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-07-19 09:32:00+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17028939                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8a3edfd4a96f45bdf961b226bae721a6c54d05801b78a8e66ffdfe4bcacf1791 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 9675000000000000000000                                             |                                                                                                                        |

## 74. Table: imUSDVault\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-10 00:48:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24755840                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2776a992a780202db579d4bc973de9185dbc0851d7ef2405757f3cd95bc1307c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 807                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 23870001420402553002069                                            |                                                              |
| platformReward    | VARCHAR   | 0                                                                  |                                                              |

## 75. Table: imUSDVault\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 10:44:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22354175                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98b476b674ea503f35dcd4a8a437a5f4d6e55f22368bd9b3f8b301956aa854c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 208                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x2486c40f5cbac257217129d681d5a4412be7328d                         |                                                              |
| reward            | VARCHAR   | 3925834203588658187                                                |                                                              |
| platformReward    | VARCHAR   | 0                                                                  |                                                              |

## 76. Table: imUSDVault\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-19 23:40:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17050580                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaad7d48d9680b8e4480c76284f6cce8e1daef588735c14ec9b6aebc634de1af7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x02cd173b9058e8ba36a01aa2caceafa3ad9b9066                         |                                                              |
| amount            | VARCHAR   | 193128476757222761968                                              |                                                              |
| payer             | VARCHAR   | 0x02cd173b9058e8ba36a01aa2caceafa3ad9b9066                         |                                                              |

## 77. Table: imUSDVault\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 20:13:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38912928                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x134b7da04d1d571f68d599f3d4140cefcff98faa305d109ec944459bdef76832 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 392                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xc657b9bf61e928e3114faf8aa269beb9a29105b1                         |                                                              |
| value             | VARCHAR   | 59148226436441285970                                               |                                                              |

## 78. Table: imUSDVault\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-05 03:01:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25593593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd9c534d48739bb6f15f4ffd7a177aa65da23a22c4ae84ce5af5eb62d79fad953 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32aba856dc5ffd5a56bcd182b13380e5c855aa29                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x185cf6633862e2cc3e6bffc9c7d9a5c5e55f8878                         |                                                              |
| amount            | VARCHAR   | 2000000000000000000000                                             |                                                              |

## 79. Table: imUSD\_call\_depositInterest\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-08-20 01:27:01+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 18177801                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x112782d116981a25d0dc787183f5cdc1bd2210add014db305f0f99bad3d2b47a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 84                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 39588194523497843                                                  |                                                                                                                        |

## 80. Table: imUSD\_call\_depositSavings\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-20 21:29:04+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 29804396                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa41192ab26ee31b2be8fc2709399f6dea87c392fac99c36b1bfc5c6a390021bb | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 13                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 31                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_underlying       | VARCHAR   | 1177957870443107293                                                |                                                                                                                        |

## 81. Table: imUSD\_call\_deposit\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| assets             | VARCHAR   |                                                                                                                        |             |
| receiver           | VARCHAR   |                                                                                                                        |             |

## 82. Table: imUSD\_call\_emergencyWithdraw\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_withdrawAmount   | VARCHAR   |                                                                                                                        |             |

## 83. Table: imUSD\_call\_mint\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| shares             | VARCHAR   |                                                                                                                        |             |
| receiver           | VARCHAR   |                                                                                                                        |             |
| referrer           | VARCHAR   |                                                                                                                        |             |

## 84. Table: imUSD\_call\_redeemAndUnwrap\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-29 04:38:53+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 34931948                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x77bb585d673fd357a6d8cb7d55a8a853a659d50c95f892e4c486dc52d461e7aa | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 28                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 1457007198360027703157                                             |                                                                                                                        |
| \_isCreditAmt      | VARCHAR   | true                                                               |                                                                                                                        |
| \_minAmountOut     | VARCHAR   | 162338917                                                          |                                                                                                                        |
| \_output           | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                                                                                        |
| \_beneficiary      | VARCHAR   | 0x939e1b3fa48b1f733ddf8ea2f98eb93549933458                         |                                                                                                                        |
| \_router           | VARCHAR   | 0xe840b73e5287865eec17d250bfb1536704b43b21                         |                                                                                                                        |
| \_isBassetOut      | VARCHAR   | true                                                               |                                                                                                                        |

## 85. Table: imUSD\_call\_redeemCredits\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-19 11:18:00+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 29751524                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xaef4079cda8584b3e9977ebf12abf85d6fe3e04f2ae229a31f687afe32f4d78a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 39                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_credits          | VARCHAR   | 9000000000000000000000                                             |                                                                                                                        |

## 86. Table: imUSD\_call\_redeemUnderlying\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-20 18:31:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 23956249                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x702d1b24572a54a6c68756142c92921ee13e1207f201ac62f700681a09ec2930 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 4                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_underlying       | VARCHAR   | 1005010000000000000000                                             |                                                                                                                        |

## 87. Table: imUSD\_call\_redeem\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-15 02:15:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 24953521                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xfcbd9d344103c649ac2a3127a8cf5a313d5fd0b8ee142371d29cbe5e569f8f45 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 39                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2,0,3,1,2                                                        | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_credits          | VARCHAR   | 5757463169785778730                                                |                                                                                                                        |

## 88. Table: imUSD\_call\_withdraw\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| assets             | VARCHAR   |                                                                                                                        |             |
| receiver           | VARCHAR   |                                                                                                                        |             |
| owner              | VARCHAR   |                                                                                                                        |             |

## 89. Table: imUSD\_event\_CreditsRedeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 11:59:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16286141                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x884d07a3bbb2a2065542d7fcf76fe0aa8f6120af69ced7ac3a83071a5668d1a9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the contract that produced the log                |
| redeemer          | VARCHAR   | 0x6d84264a7bd2cffa4a117ba2350403b3a9866949                         |                                                              |
| creditsRedeemed   | VARCHAR   | 87190468995025841139085                                            |                                                              |
| savingsCredited   | VARCHAR   | 8998125172270186910879                                             |                                                              |

## 90. Table: imUSD\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-05 18:42:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31558050                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcd92266988f1b536824fb8771afd884777c5036f56ecedf8f0c08908fc38d78a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x299081f52738a4204c3d58264ff44f6f333c6c88                         |                                                              |
| owner             | VARCHAR   | 0xabf94c1f5f2bdcf20f29fde4279d189b77910b3f                         |                                                              |
| assets            | VARCHAR   | 768877750151086                                                    |                                                              |
| shares            | VARCHAR   | 6910927068300820                                                   |                                                              |

## 91. Table: imUSD\_event\_ExchangeRateUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-04 14:00:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22127554                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f857c6f2119ac8549ab2231c64357aff5efd776eb1d9f90f23ff058b9d6277b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the contract that produced the log                |
| newExchangeRate   | VARCHAR   | 107420328014242592                                                 |                                                              |
| interestCollected | VARCHAR   | 184725331695196541262                                              |                                                              |

## 92. Table: imUSD\_event\_Poked\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldBalance        | VARCHAR   |                                                              |             |
| newBalance        | VARCHAR   |                                                              |             |
| interestDetected  | VARCHAR   |                                                              |             |

## 93. Table: imUSD\_event\_Referral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-04 10:45:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31507725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3e80789f15b0ef4a992829bdf98ae127d9eb631b20664c4c9acc394a07cbbc2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 331                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the contract that produced the log                |
| referrer          | VARCHAR   | 0xe0ee7fec8ec7eb5e88f1dbbfe3e0681cc49f6499                         |                                                              |
| beneficiary       | VARCHAR   | 0x89252e32e98d467c6ae3e2e6a9942ba3033f938a                         |                                                              |
| amount            | VARCHAR   | 999839698500830993                                                 |                                                              |

## 94. Table: imUSD\_event\_SavingsDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-20 17:45:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20423181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x19ebd396922e4e548c1a3324f75a820f76b59c68a5eb43ad2f75e2bc913ec281 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 402                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the contract that produced the log                |
| saver             | VARCHAR   | 0x1f803cc4fc6f21ce00f0c5f5932c9800045d25f0                         |                                                              |
| savingsDeposited  | VARCHAR   | 59212947835485591848291                                            |                                                              |
| creditsIssued     | VARCHAR   | 561847360590277282207669                                           |                                                              |

## 95. Table: imUSD\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 08:20:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16280233                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3cceb6a25eb17333c84838257650d5ff5987975c1bbd693a8593fed7371a6e28 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xe97aa7b566a39fbf5c9c66cd3414f88d1e883153                         |                                                              |
| value             | VARCHAR   | 22908372817612202509712                                            |                                                              |

## 96. Table: imUSD\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 19:26:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35325695                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0d27417714b19b2010a0f3a420d4edc12b3be33d4bad24b49dfbd66e2e57122 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 273                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5290ad3d83476ca6a2b178cd9727ee1ef72432af                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x33af07f9627f98e8a3dd7c000fe142732080775a                         |                                                              |
| receiver          | VARCHAR   | 0x33af07f9627f98e8a3dd7c000fe142732080775a                         |                                                              |
| owner             | VARCHAR   | 0x33af07f9627f98e8a3dd7c000fe142732080775a                         |                                                              |
| assets            | VARCHAR   | 103500952460475                                                    |                                                              |
| shares            | VARCHAR   | 926321695108110                                                    |                                                              |
