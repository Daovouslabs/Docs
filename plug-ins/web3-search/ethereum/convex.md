# convex

## 1. Table: ConvexFraxPool\_call\_getReward2\_history

| Column               | Type      | Example                                                            | Description                                                                                                            |
| -------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp     | TIMESTAMP | 2022-08-01 00:21:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number        | INTEGER   | 15253390                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash    | VARCHAR   | 0x9664bd86e9fc404415fd6084a2fe994b0c352e9be45f2a7d2d18e5fab6acc359 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index   | INTEGER   | 15                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address       | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address          | VARCHAR   | 0x35678017e1d252da1cdd6745b147e3e75d1f9c27                         | Address of the called contract                                                                                         |
| status               | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| destination\_address | VARCHAR   | 0xe0430c83f34b4d722636ec1988412f756b1cee4d                         |                                                                                                                        |
| claim\_extra\_too    | VARCHAR   | true                                                               |                                                                                                                        |

## 2. Table: ConvexFraxPool\_call\_getReward\_history

| Column               | Type      | Example                                                            | Description                                                                                                            |
| -------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp     | TIMESTAMP | 2023-06-23 19:20:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number        | INTEGER   | 17544310                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash    | VARCHAR   | 0x673a316ed631fa8ff254aded4afe427d573a72cda8f8b53eb0abd8ce2027e28d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index   | INTEGER   | 264                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address       | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address          | VARCHAR   | 0x57c9f019b25aaaf822926f4cacf0a860f61edd8d                         | Address of the called contract                                                                                         |
| status               | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| destination\_address | VARCHAR   | 0x163bd08f122fe2431a4917735d6024d3b6eeb8a5                         |                                                                                                                        |

## 3. Table: ConvexFraxPool\_call\_lockAdditional\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-12 15:57:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17032956                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x287d3b2b4425b32f7f21f19f3c9b322fb40901c2daf3f238fbfc90b2d7576d37 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 113                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 19,12,0,2                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x711d650cd10df656c2c28d375649689f137005fa                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| kek\_id            | VARCHAR   | 0x6f776401f94ed66f92dddc16e5086cfaf49513bfe33c17c9cfce4277e3d05a1b |                                                                                                                        |
| addl\_liq          | VARCHAR   | 99960466767172735165170                                            |                                                                                                                        |

## 4. Table: ConvexFraxPool\_call\_stakeLocked\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-21 20:16:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17530357                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xaa8fc52ab468c0e522ab767275a1669ce5498d14ae220ca5dcb98e4c7c3834e5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 117                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa0657642224fc53dab4a3d2069430afe157bec5d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| liquidity          | VARCHAR   | 3725093148415468250258                                             |                                                                                                                        |
| secs               | VARCHAR   | 604800                                                             |                                                                                                                        |

## 5. Table: ConvexFraxPool\_call\_withdrawLocked\_history

| Column               | Type      | Example                                                            | Description                                                                                                            |
| -------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp     | TIMESTAMP | 2023-03-01 06:53:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number        | INTEGER   | 16732114                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash    | VARCHAR   | 0xd51b7ef7bbf9d480ed18dff30216b511205d9bac02eef7ed10d16344fe5f5290 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index   | INTEGER   | 202                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address       | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address          | VARCHAR   | 0x560c7668459221e33ed515d1d17c09ecda1996f5                         | Address of the called contract                                                                                         |
| status               | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| kek\_id              | VARCHAR   | 0x0710b1d529d9c5573507fc04f87a4cae2c0f936418c6a437358514d98ffce84d |                                                                                                                        |
| destination\_address | VARCHAR   | 0x4476147b84ff5de14ca3341cc5f4217b8aa7318e                         |                                                                                                                        |

## 6. Table: ConvexFraxPool\_event\_LockedAdditional\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 20:36:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15977859                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x44020c2bd6c46546bb0138222b332e807bd8f7c6c7af292ec4ba4e97722814fa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5a92ef27f4baa7c766aee6d751f754ebdebd9fae                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xc778a46fd5182b9275353524d00ba6b9f6f85cb8                         |                                                              |
| kek\_id           | VARCHAR   | 0xd67bf7523797964cc64b5f3210b438c32f7afba57dc34f392a4edabb63e4fd03 |                                                              |
| amount            | VARCHAR   | 12399676598194500417111                                            |                                                              |

## 7. Table: ConvexFraxPool\_event\_LockedLonger\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-20 21:49:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17303403                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x074c0b4dd9176ca4f9b41d8a44e07c582306ccae48ca9d7ac9c0916047986268 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 166                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa632fab76fe013199c8271ac22b466b9d11bfe88                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x38f2944e482a050942e5fb1652af4690017cd141                         |                                                              |
| kek\_id           | VARCHAR   | 0xabfa279868a735ce15a09ea09661b87dc75b3e20b423e197cb6df89b23836820 |                                                              |
| new\_secs         | VARCHAR   | 31198237                                                           |                                                              |
| new\_start\_ts    | VARCHAR   | 1684619363                                                         |                                                              |
| new\_end\_ts      | VARCHAR   | 1715817600                                                         |                                                              |

## 8. Table: ConvexFraxPool\_event\_RewardPaid\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-06-01 23:52:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 17389329                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xc4e10af3ca4996c1016b5d5c2c73591d06588b3187f4fa01c7ccd47561765210 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x2f9504988675c91787e188ed928d6e042d9052e9                         | Address of the contract that produced the log                |
| user                 | VARCHAR   | 0xa46a2ec44fbf77e543baa87b8c3e05e6a8798de4                         |                                                              |
| amount               | VARCHAR   | 4953286288896681181                                                |                                                              |
| token\_address       | VARCHAR   | 0x3432b6a60d23ca0dfca7761b7ab56459d9c964d0                         |                                                              |
| destination\_address | VARCHAR   | 0xa46a2ec44fbf77e543baa87b8c3e05e6a8798de4                         |                                                              |

## 9. Table: ConvexFraxPool\_event\_StakeLocked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-25 02:53:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14452842                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0bb33c47a682eb963bfed41a380c77b75ad34439288b410d0b553d4b025e981c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x698137c473bc1f0ea9b85ade45caf64ef2df48d6                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xb1baf9eb336f6795f3373be04b0a90215e08346d                         |                                                              |
| amount            | VARCHAR   | 401871960053524601485600                                           |                                                              |
| secs              | VARCHAR   | 86400                                                              |                                                              |
| kek\_id           | VARCHAR   | 0x26c511163a88c02bac59720e66bce908ec54070cceed06e1a89a2ac32cdeb66a |                                                              |
| source\_address   | VARCHAR   | 0xb1baf9eb336f6795f3373be04b0a90215e08346d                         |                                                              |

## 10. Table: ConvexFraxPool\_event\_WithdrawLocked\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2023-02-07 07:16:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 16575354                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x1f2608ce46824ced35d87fa8dadb887db3297557d957883436c5dcda99f1d9b7 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 1099                                                               | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x2f9504988675c91787e188ed928d6e042d9052e9                         | Address of the contract that produced the log                |
| user                 | VARCHAR   | 0xa0aa34256501a3c8e9c9f775b9ab4ae6366d2826                         |                                                              |
| liquidity            | VARCHAR   | 217666296254868956753553                                           |                                                              |
| kek\_id              | VARCHAR   | 0x1745d6cacf3d5fa95690aa7b27c265486dc330514d8e48fd5163c8628051429d |                                                              |
| destination\_address | VARCHAR   | 0xa0aa34256501a3c8e9c9f775b9ab4ae6366d2826                         |                                                              |

## 11. Table: CrvDepositor\_call\_depositAll\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-17 08:30:20+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14402961                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x35c3b04b64a34443842478e32af8f51b8a5820b577ce304eab04ddd511ff650f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 103                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x8014595f2ab54cd7c604b00e9fb932176fdc86ae                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_lock             | VARCHAR   | true                                                               |                                                                                                                        |
| \_stakeAddress     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                                                                                        |

## 12. Table: CrvDepositor\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-11 00:33:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13591736                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc5f25303818f0ce64233bae3fb9dff95b9c147aa1d46c40811623d89f48c019f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 505                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x8014595f2ab54cd7c604b00e9fb932176fdc86ae                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 24500796280000000000                                               |                                                                                                                        |
| \_lock             | VARCHAR   | true                                                               |                                                                                                                        |

## 13. Table: CurveBooster\_event\_Deposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-03 13:11:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14133213                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2d27cc2e91304c6e7d217472f8cf6a99cdbb072896d89edfc75d97374009b6a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf403c135812408bfbe8713b5a23a04b3d48aae31                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x90e938c50f56aee8ed12d72b3b178bf5c395bdc5                         |                                                              |
| poolid            | VARCHAR   | 6                                                                  |                                                              |
| amount            | VARCHAR   | 65938624324589019433                                               |                                                              |

## 14. Table: CurveBooster\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 11:01:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17385530                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba92dd75ebede1e7cba9703d3896e21988e7604d8ea53c61f16282b90461dde5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf403c135812408bfbe8713b5a23a04b3d48aae31                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xe6df83e180ca343ecffac36d4ede8351eed08df0                         |                                                              |
| poolid            | VARCHAR   | 22                                                                 |                                                              |
| amount            | VARCHAR   | 4464391534733032520213                                             |                                                              |

## 15. Table: CurveVoterProxy\_call\_claimCrv\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-21 19:57:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17743750                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x04849fb87873f17186ceb113742f8075b098df6c10302a4525a49673a8005272 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 52                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_gauge            | VARCHAR   | 0xcfc25170633581bf896cb6cdee170e3e3aa59503                         |                                                                                                                        |

## 16. Table: CurveVoterProxy\_call\_claimFees\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-02 17:33:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16742378                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1b3d311b6f4b05b9dbf03fc9b6191f10b687266561c4f6c5e46835da39a37366 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 22                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_distroContract   | VARCHAR   | 0xa464e6dcda8ac41e03616f95f4bc98a13b8922dc                         |                                                                                                                        |
| \_token            | VARCHAR   | 0x6c3f90f043a72fa612cbac8115ee7e52bde6e490                         |                                                                                                                        |

## 17. Table: CurveVoterProxy\_call\_claimRewards\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-18 01:14:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17716776                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xed3df83e08e9c351e5a36ce157ee339c87ac4479039f666af4f6385c1bffd49d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 6                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4,1,2,0                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_gauge            | VARCHAR   | 0x9582c4adacb3bce56fea3e590f05c3ca2fb9c477                         |                                                                                                                        |

## 18. Table: CurveVoterProxy\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-28 08:24:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17143415                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x73ba9e17d158251b689ff0594160d285b85bce8f394443ce2a0367bc7c745ef6 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 106                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_token            | VARCHAR   | 0x06325440d014e39736583c165c2963ba99faf14e                         |                                                                                                                        |
| \_gauge            | VARCHAR   | 0x182b723a58739a9c974cfdb385ceadb237453c28                         |                                                                                                                        |

## 19. Table: CurveVoterProxy\_call\_withdrawAll\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-17 12:30:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17279365                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x870abed99e5ea81abe62e24f9ce2e6f9b86bfff1ace0f95739f21f4d81ee326f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 59                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,1,0,2,0,0                                                      | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_token            | VARCHAR   | 0xdf5e0e81dff6faf3a7e52ba697820c5e32d806a8                         |                                                                                                                        |
| \_gauge            | VARCHAR   | 0xfa712ee4788c042e2b7bb55e6cb8ec569c4530c1                         |                                                                                                                        |

## 20. Table: CurveVoterProxy\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-11 07:18:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17455342                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xdd6d427cdc24a09520968d6b98f8f433c583234b1beb5ac3623ac67ccd1b756b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 47                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x989aeb4d175e16225e39e87d0d97a3360524ad80                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_token            | VARCHAR   | 0x3f0e7916681452d23cd36b1281457da721f2e5df                         |                                                                                                                        |
| \_gauge            | VARCHAR   | 0x2b917214c5d6f057fbdaf9a3aae201e9f484fdae                         |                                                                                                                        |
| \_amount           | VARCHAR   | 18796380494087798992                                               |                                                                                                                        |

## 21. Table: CvxLockerV1\_event\_KickReward\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-12 11:55:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14191080                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x26ec585224e00f1750771add156e2d874fd1d515b1599563c26ffa4c930d38f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd18140b4b819b895a3dba5442f959fa44994af50                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x6bed2a4c9673c990fa28fbf39488b1d3c92360f7                         |                                                              |
| \_kicked          | VARCHAR   | 0x0be8995d4950cd5f8c077b85d6c7b542c563f726                         |                                                              |
| \_reward          | VARCHAR   | 1251152002632673060                                                |                                                              |

## 22. Table: CvxLockerV1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-06 02:38:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13749692                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x048f7707f56d704784cff49a0d7595068f421c34e623a26ea438cf6c6e43c986 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 565                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd18140b4b819b895a3dba5442f959fa44994af50                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xa3c5a1e09150b75ff251c1a7815a07182c3de2fb                         |                                                              |
| newOwner          | VARCHAR   | 0x98e28afb9c11aa979ae754e1ea2e9877cb0d418c                         |                                                              |

## 23. Table: CvxLockerV1\_event\_Recovered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_token           | VARCHAR   |                                                              |             |
| \_amount          | VARCHAR   |                                                              |             |

## 24. Table: CvxLockerV1\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-31 02:08:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13522079                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x68d416e4a3b1736539e632ef50d3ae21aee39fa42a4553041500a6e895fbd720 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 292                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd18140b4b819b895a3dba5442f959fa44994af50                         | Address of the contract that produced the log                |
| \_token           | VARCHAR   | 0x62b9c7356a2dc64a1969e19c23e4f579f9810aa7                         |                                                              |
| \_reward          | VARCHAR   | 101885625500988270415606                                           |                                                              |

## 25. Table: CvxLockerV1\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-28 19:22:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16070546                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7cd591842102a6091065fd6b03aa99c52c4edb5c8f63468f68f69093764bbe05 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 423                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd18140b4b819b895a3dba5442f959fa44994af50                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x61a9704e6fb36e59e4516b8cea71b2a705a85c94                         |                                                              |
| \_rewardsToken    | VARCHAR   | 0x62b9c7356a2dc64a1969e19c23e4f579f9810aa7                         |                                                              |
| \_reward          | VARCHAR   | 29617782855197638453                                               |                                                              |

## 26. Table: CvxLockerV1\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-07 10:10:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13957705                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xecd6acf7356b238c3de31c64f153119a0684eaa44b48af9b266e033acd6d580f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd18140b4b819b895a3dba5442f959fa44994af50                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0xe4b8c8e33b17ec8517403852d7bb272134a2271a                         |                                                              |
| \_paidAmount      | VARCHAR   | 520784874391988835587                                              |                                                              |
| \_lockedAmount    | VARCHAR   | 520784874391988835587                                              |                                                              |
| \_boostedAmount   | VARCHAR   | 520784874391988835587                                              |                                                              |

## 27. Table: CvxLockerV1\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 19:20:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14354432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x971899710149ea8ec1d331b8fe3d012e0b6bcedfb36f5d208ef35a84d8d758d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd18140b4b819b895a3dba5442f959fa44994af50                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x8dfbb49f8b1127f48b3ffac19f5ee56908e4c365                         |                                                              |
| \_amount          | VARCHAR   | 316776237928063924815                                              |                                                              |
| \_relocked        | VARCHAR   | false                                                              |                                                              |

## 28. Table: CvxLockerV2\_event\_KickReward\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-29 00:14:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17581325                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5c44f9704ae7450bd41e8605422f94ccb3d9e52bbde6eae9cb497d11c160641 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 278                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72a19342e8f1838460ebfccef09f6585e32db86e                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x0bc8332840eec6f16f1fa846214e628b03558caf                         |                                                              |
| \_kicked          | VARCHAR   | 0x417882a0769ac2f46cb8971d92fbac0fd95adcec                         |                                                              |
| \_reward          | VARCHAR   | 2198191353667512852                                                |                                                              |

## 29. Table: CvxLockerV2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-04 13:01:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14320609                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x154d39824166d47226926d46d305d56ff184e5fc5572a048ba3977faa2bda2a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72a19342e8f1838460ebfccef09f6585e32db86e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x947b7742c403f20e5faccdac5e092c943e7d0277                         |                                                              |

## 30. Table: CvxLockerV2\_event\_Recovered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_token           | VARCHAR   |                                                              |             |
| \_amount          | VARCHAR   |                                                              |             |

## 31. Table: CvxLockerV2\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-15 04:35:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17482957                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x05dbc8e907ef9db65d877741a4fde1b62ce817760a9c863c18498b1c36f4251e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72a19342e8f1838460ebfccef09f6585e32db86e                         | Address of the contract that produced the log                |
| \_token           | VARCHAR   | 0x62b9c7356a2dc64a1969e19c23e4f579f9810aa7                         |                                                              |
| \_reward          | VARCHAR   | 249111994247374667649546                                           |                                                              |

## 32. Table: CvxLockerV2\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-16 13:17:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17059686                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x86dd932538145fbde98d90fcbc29552b0d76c2c1bba77fa3c2eb6a812ebe30b2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72a19342e8f1838460ebfccef09f6585e32db86e                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x0dd16c537cdb346826203f3ab762030e7f20c78a                         |                                                              |
| \_rewardsToken    | VARCHAR   | 0x62b9c7356a2dc64a1969e19c23e4f579f9810aa7                         |                                                              |
| \_reward          | VARCHAR   | 352444509027404388                                                 |                                                              |

## 33. Table: CvxLockerV2\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 09:27:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17840722                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45e0b4751ad37682e3f029e17bd92167d0a328fc745f125fd91042d4b0076599 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 168                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72a19342e8f1838460ebfccef09f6585e32db86e                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x3584345caa8990b51885bd722f6b9437d2e08e78                         |                                                              |
| \_epoch           | VARCHAR   | 1691020800                                                         |                                                              |
| \_paidAmount      | VARCHAR   | 39203769419568331770                                               |                                                              |
| \_lockedAmount    | VARCHAR   | 39203769419568331770                                               |                                                              |
| \_boostedAmount   | VARCHAR   | 39203769419568331770                                               |                                                              |

## 34. Table: CvxLockerV2\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-03 12:17:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15465337                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x55ce990f72e9f3e09802c66effc65845f29709eb846553944a92bee34b909576 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 546                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72a19342e8f1838460ebfccef09f6585e32db86e                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x670fbcd11fd54908cabe97384f0d2785d369dcd5                         |                                                              |
| \_amount          | VARCHAR   | 3427818000000000000000                                             |                                                              |
| \_relocked        | VARCHAR   | true                                                               |                                                              |

## 35. Table: FraxBooster\_call\_addPool\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-24 02:11:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17326000                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa59444bbefd609a18051dd2e8f092567986511ae847fae19978c2c7ff1e0a55b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 13                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x569f5b842b5006ec17be02b8b94510ba8e79fbca                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_implementation   | VARCHAR   | 0x7d54c53e6940e88a7ac1970490dafbbf85d982f4                         |                                                                                                                        |
| \_stakingAddress   | VARCHAR   | 0xb8ebc210bcf78be8ef3f09dd0d8e85fa5e252e86                         |                                                                                                                        |
| \_stakingToken     | VARCHAR   | 0xaa236bd1302755937aa46d6f3423655bbc654b02                         |                                                                                                                        |

## 36. Table: FraxBooster\_call\_createVault\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-13 17:10:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17472466                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe8ee2b4de66247010f818d54cd5192e8a79cc6cef4fcc6f6f2c24898de3db733 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 100                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x569f5b842b5006ec17be02b8b94510ba8e79fbca                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_pid              | VARCHAR   | 25                                                                 |                                                                                                                        |

## 37. Table: FxsDepositor\_call\_depositAll\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-20 18:17:08+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14244476                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xed12d23a5c43273232560d0d28ba83484ff4aecaaffbcbb3da13cccb801192cd | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 452                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x8f55d7c21bdff1a51afaa60f3de7590222a3181e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_lock             | VARCHAR   | true                                                               |                                                                                                                        |

## 38. Table: FxsDepositor\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-04 07:34:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17405798                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x23eddcda8a89cc0064e5e86ea05b7e67b9099444ce441025b51aaf2064ecc7f2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 20                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x8f55d7c21bdff1a51afaa60f3de7590222a3181e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 75487052403939030000                                               |                                                                                                                        |
| \_lock             | VARCHAR   | false                                                              |                                                                                                                        |

## 39. Table: cvxCRVRewards\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-08 19:42:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16785681                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e7ef8be29675afc7a4c88fc7c24e962a938093c25074dd06add3a996fab7499 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fe65692bfcd0e6cf84cb1e7d24108e434a7587e                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 315258060004593632238693                                           |                                                              |

## 40. Table: cvxCRVRewards\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 00:21:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17247480                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7084870b9f109ce93c098a2fe9c37e9bcd9577133b37021e155cacfb4cb0a269 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fe65692bfcd0e6cf84cb1e7d24108e434a7587e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3a652f60622d22cde49de3d9b5e9d0dcd4d6c32a                         |                                                              |
| reward            | VARCHAR   | 198726717556788853764                                              |                                                              |

## 41. Table: cvxCRVRewards\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 10:13:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12509374                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x299f156f5771947c6e55d582d68cd9c3c4bf62daf72a2b1a7e163d890e27ecd2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fe65692bfcd0e6cf84cb1e7d24108e434a7587e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0716266cc5d3c443e30b0c4e9c72afa33778e1de                         |                                                              |
| amount            | VARCHAR   | 1530612360820295035570                                             |                                                              |

## 42. Table: cvxCRVRewards\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 12:32:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16904502                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x50e703d996fa24a9b55605c3df98d735e5172e94dd72be468cb6988c64f78019 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 192                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fe65692bfcd0e6cf84cb1e7d24108e434a7587e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x056024339880015b20e7a958b3164f6280a5f1ac                         |                                                              |
| amount            | VARCHAR   | 4268172809880000000000                                             |                                                              |

## 43. Table: cvxFXSRewards\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-05 18:44:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15905683                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x67450dcea64359a60de866b06e345cff7c5bdb1aef53b60c43d87131fa05c9d3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf27afad0142393e4b3e5510abc5fe3743ad669cb                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 122971354677978100035794                                           |                                                              |

## 44. Table: cvxFXSRewards\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-21 01:19:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17304447                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb978b5e4ed3c55a47f49f4633075781c0a57b684798f54310d7556fec6497cc7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 549                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf27afad0142393e4b3e5510abc5fe3743ad669cb                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x719f0226a1adfffc216aa27c0c42ff699972bb6c                         |                                                              |
| reward            | VARCHAR   | 60017340764878747739                                               |                                                              |

## 45. Table: cvxFXSRewards\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-13 20:53:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14958036                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xde71e4447bd79e9c3aa3deb364a714f4030df95726b2cf5affa53267d2078597 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf27afad0142393e4b3e5510abc5fe3743ad669cb                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x484ea27da8d53fb6ae356306d1cefe110769ab10                         |                                                              |
| amount            | VARCHAR   | 237891174148290722554                                              |                                                              |

## 46. Table: cvxFXSRewards\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 18:40:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15491956                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4bfa571e4555b28b3bd80a653b812e025e507e6539cd2d938a40eabc4c0dcc65 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 318                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf27afad0142393e4b3e5510abc5fe3743ad669cb                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1ae7ae4b4605f5335c1739498e6195a45d7ccf47                         |                                                              |
| amount            | VARCHAR   | 200000000000000000000                                              |                                                              |

## 47. Table: cvxRewards\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-07 04:18:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13756432                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeee5ec76d891498e0fed01791609292f98ea74928a39c69611e425409665f1eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcf50b810e57ac33b91dcf525c6ddd9881b139332                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 192253084086489388109926                                           |                                                              |

## 48. Table: cvxRewards\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-02 14:06:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13146697                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdc6a6385e7cdd8bcce81aea2d8011d65177f8fce23e491141cdfc0c3e084eb3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcf50b810e57ac33b91dcf525c6ddd9881b139332                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0443180451b462bdc5e09fc910712f10e90d8a62                         |                                                              |
| reward            | VARCHAR   | 179139101645846016668                                              |                                                              |

## 49. Table: cvxRewards\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 22:10:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16293310                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96d55c76b1e3d7275ed684e5164b7b4b674402c9a0758364dc79cbcd5910fb1b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcf50b810e57ac33b91dcf525c6ddd9881b139332                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xac7d7cb3b8eeb5dd73c54e89f786f7dd64e696eb                         |                                                              |
| amount            | VARCHAR   | 127412917377125638672                                              |                                                              |

## 50. Table: cvxRewards\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-15 21:32:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14393611                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x77fe18073811024f3ce6377de63b703c70dfb1dcc71e7ea43d6880fdf0c09ab8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 327                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcf50b810e57ac33b91dcf525c6ddd9881b139332                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x00f282c40b92bed05f1776cadf1c8b96b9fbaee3                         |                                                              |
| amount            | VARCHAR   | 9119483038986560274860                                             |                                                              |
