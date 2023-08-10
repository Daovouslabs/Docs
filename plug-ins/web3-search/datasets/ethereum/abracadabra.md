# abracadabra

## 1. Table: BentoBoxMarkets\_call\_cook\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-12 19:43:46+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14572737                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x421008f5a3120639133bfc0f1142ff2976248c193aee9dc8400ff5541a12aa43                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 109                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa16c84206a6b69c01833101133cc78a47602349d                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| actions            | VARCHAR   | 3,21                                                                                                 |                                                                                                                        |
| values             | VARCHAR   | 0,0                                                                                                  |                                                                                                                        |
| datas              | VARCHAR   | 0x000000000000000000000000000000000000000000000241ea9748cbcdcf49aa0000000000000000000000004a7f852a60 |                                                                                                                        |

## 2. Table: BentoBoxMarkets\_call\_liquidateV3\_4\_history

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
| users              | VARCHAR   |                                                                                                                        |             |
| maxBorrowParts     | VARCHAR   |                                                                                                                        |             |
| to                 | VARCHAR   |                                                                                                                        |             |
| swapper            | VARCHAR   |                                                                                                                        |             |
| swapperData        | VARCHAR   |                                                                                                                        |             |

## 3. Table: BentoBoxMarkets\_call\_liquidate\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-27 22:20:27+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14090362                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf86cec632e9650962396e4c175678714e6abbe4fd879cccf019b23bb6d148826                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 36                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3410297d89dcdaf4072b805efc1ef701bb3dd9bf                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| users              | VARCHAR   | 0x0530539d9546843C61166639D4362040B1107d05,0xD696F6B81377417E2844448C97459C0cC0621800,0x220c12268c6f |                                                                                                                        |
| maxBorrowParts     | VARCHAR   | 13337948903884067544562,3900465300843188173042,1570586349658039439368,1297619259830340036365         |                                                                                                                        |
| to                 | VARCHAR   | 0x125238b61064ab2c00c3b22acb4b3b6e4732ae90                                                           |                                                                                                                        |
| swapper            | VARCHAR   | 0x125238b61064ab2c00c3b22acb4b3b6e4732ae90                                                           |                                                                                                                        |

## 4. Table: BentoBoxMarkets\_event\_LogAccrue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 00:54:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17028508                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5caa6c372fd8a558167c44e20e1295e1c49c89b6933a6ceb1aad1ffdca1f5839 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4eaed76c3a388f4a841e9c765560bbe7b3e4b3a0                         | Address of the contract that produced the log                |
| accruedAmount     | VARCHAR   | 7451957700619373677                                                |                                                              |

## 5. Table: BentoBoxMarkets\_event\_LogAddCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-20 02:28:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12668579                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90681362b3f2ec8afe929988ab57097764b5f31786b52656aee0d47af3d1565a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x049a59ce3e69bd9b37d534a1182ba2871b196281                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc13be966b238239d3205aad3c58d656211df8cae                         |                                                              |
| to                | VARCHAR   | 0xc13be966b238239d3205aad3c58d656211df8cae                         |                                                              |
| share             | VARCHAR   | 500000000000000000000                                              |                                                              |

## 6. Table: BentoBoxMarkets\_event\_LogBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-17 23:36:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13438415                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39604611862e268f6687291ca0c7ce9909668ffded57fe277e831cf6329fcfef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 272                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x003d5a75d284824af736df51933be522de9eed0f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xf352e5320291298be60d00a015b27d3960f879fa                         |                                                              |
| to                | VARCHAR   | 0x985486e621c28452f444bbcc8c84868bda920922                         |                                                              |
| amount            | VARCHAR   | 1204798629731390392000                                             |                                                              |
| part              | VARCHAR   | 1194604744625404523510                                             |                                                              |

## 7. Table: BentoBoxMarkets\_event\_LogChangeBorrowLimit\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newLimit          | VARCHAR   |                                                              |             |
| perAddressPart    | VARCHAR   |                                                              |             |

## 8. Table: BentoBoxMarkets\_event\_LogExchangeRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-01 12:51:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12741885                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab2869d63cc768fbf5ad76cf0a9d37895e62546e02ff40de5594d85fe9507633 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x551a7cff4de931f32893c928bbc3d25bf1fc5147                         | Address of the contract that produced the log                |
| rate              | VARCHAR   | 989107                                                             |                                                              |

## 9. Table: BentoBoxMarkets\_event\_LogFeeTo\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newFeeTo          | VARCHAR   |                                                              |             |

## 10. Table: BentoBoxMarkets\_event\_LogInterestChange\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldInterestRate   | VARCHAR   |                                                              |             |
| newInterestRate   | VARCHAR   |                                                              |             |

## 11. Table: BentoBoxMarkets\_event\_LogLiquidation\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| collateralShare   | VARCHAR   |                                                              |             |
| borrowAmount      | VARCHAR   |                                                              |             |
| borrowPart        | VARCHAR   |                                                              |             |

## 12. Table: BentoBoxMarkets\_event\_LogRemoveCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-28 20:43:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12331164                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5a000a7e6f8dff53b50aa525f9539db89a8823f81799c0fd09793e81fea6860c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 230                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb7b45754167d65347c93f3b28797887b4b6cd2f3                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x1488c8fe2a9a54e56ed6c5905bf7ae4a2629aede                         |                                                              |
| to                | VARCHAR   | 0x1488c8fe2a9a54e56ed6c5905bf7ae4a2629aede                         |                                                              |
| share             | VARCHAR   | 10000000000000000000                                               |                                                              |

## 13. Table: BentoBoxMarkets\_event\_LogRepayForAll\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| amount            | VARCHAR   |                                                              |             |
| previousElastic   | VARCHAR   |                                                              |             |
| newElastic        | VARCHAR   |                                                              |             |

## 14. Table: BentoBoxMarkets\_event\_LogRepay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-20 02:37:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12860809                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x82ba4469b32a064ecc605af71e97fb057be0b8594a4a4f4c63e53a4505885908 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 322                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x17fb5f39c55903de60e63543067031ce2b2659ee                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x967352beb80d3a28d06252248d5d6b56921ba081                         |                                                              |
| to                | VARCHAR   | 0x967352beb80d3a28d06252248d5d6b56921ba081                         |                                                              |
| amount            | VARCHAR   | 22837447482                                                        |                                                              |
| part              | VARCHAR   | 22434464470                                                        |                                                              |

## 15. Table: BentoBoxMarkets\_event\_LogWithdrawFees\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-05-10 23:51:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 14751523                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x8a9a315f6f136c6fea497ff49c9799002df694456411399a8486e5fc4310b1a4 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xc1879bf24917ebe531fbaa20b0d05da027b592ce                         | Address of the contract that produced the log                |
| feeTo              | VARCHAR   | 0xb2c3a9c577068479b1e5119f6b7da98d25ba48f4                         |                                                              |
| feesEarnedFraction | VARCHAR   | 1294425799584651568                                                |                                                              |

## 16. Table: BentoBoxV1\_event\_LogDeploy\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-15 14:40:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14391738                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ce182f7d82bbcb81cae184aeb3e68c4e3e1efc2b3baaa68e16a367ccde1a1f0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 308                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5bce5077908a1b7370b9ae04adc565ebd643966                         | Address of the contract that produced the log                |
| masterContract    | VARCHAR   | 0xca5d427af96e9846f7d192e64034f0666431fdce                         |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |
| cloneAddress      | VARCHAR   | 0xdc59fe9b4ac5f7705a43136a59735fa0350edaae                         |                                                              |

## 17. Table: BentoBoxV1\_event\_LogDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-05 21:09:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15906404                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x81d0c10124c2731a12c95555d5c4aa3e4f850b3e181e943ea2d22d53717839d6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 161                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5bce5077908a1b7370b9ae04adc565ebd643966                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| from              | VARCHAR   | 0x51a93fe2d844e1df7a9299e68517e222efebcbfa                         |                                                              |
| to                | VARCHAR   | 0x51a93fe2d844e1df7a9299e68517e222efebcbfa                         |                                                              |
| amount            | VARCHAR   | 470000000000000000000                                              |                                                              |
| share             | VARCHAR   | 470000000000000000000                                              |                                                              |

## 18. Table: BentoBoxV1\_event\_LogFlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 07:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16117231                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc25c5f613f9bf34134517d897cf18f40af9b8dd9736f493587c1cc7b43e2a5f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5bce5077908a1b7370b9ae04adc565ebd643966                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0xf2bdcb1ec8810c35bf9b947371820c199bd775db                         |                                                              |
| token             | VARCHAR   | 0x0000000000085d4780b73119b644ae5ecd22b376                         |                                                              |
| amount            | VARCHAR   | 1373937137973350445440                                             |                                                              |
| feeAmount         | VARCHAR   | 686968568986675222                                                 |                                                              |
| receiver          | VARCHAR   | 0xf2bdcb1ec8810c35bf9b947371820c199bd775db                         |                                                              |

## 19. Table: BentoBoxV1\_event\_LogWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-15 06:16:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14389492                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa28de60367641335bc718b0b78c55b16b5b17fee9c58733df3f8e68892c8bbe3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 444                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5bce5077908a1b7370b9ae04adc565ebd643966                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0bc529c00c6401aef6d220be8c6ea1667f6ad93e                         |                                                              |
| from              | VARCHAR   | 0x8d9b3114c952a067e8577f7a10aac0ca18e18588                         |                                                              |
| to                | VARCHAR   | 0x8d9b3114c952a067e8577f7a10aac0ca18e18588                         |                                                              |
| amount            | VARCHAR   | 5219540000000000                                                   |                                                              |
| share             | VARCHAR   | 5219540000000000                                                   |                                                              |

## 20. Table: DegenBoxMarkets\_call\_cook\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-06 16:01:35+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17422458                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x000f6bd784db6645f0cd52ff579b430a82cf272206b2bf9344ed46adb783930d                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 137                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7259e152103756e1616a77ae982353c3751a6a90                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| actions            | VARCHAR   | 20,7,2                                                                                               |                                                                                                                        |
| values             | VARCHAR   | 0,0,0                                                                                                |                                                                                                                        |
| datas              | VARCHAR   | 0x00000000000000000000000099d8a9c45b2eca8864373a26d1459e3dff1e17f30000000000000000000000002a48d3be1b |                                                                                                                        |

## 21. Table: DegenBoxMarkets\_call\_liquidateV3\_4\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-11 19:14:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16607539                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3b45e798942598db7d0ddfb651ab6b132d9225201fcb71135179c61546b75844 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 74                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7259e152103756e1616a77ae982353c3751a6a90                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| users              | VARCHAR   | 0x95dBA087a364c1169fa0697893d4f76103802c24                         |                                                                                                                        |
| maxBorrowParts     | VARCHAR   | 10815814193854734383857                                            |                                                                                                                        |
| to                 | VARCHAR   | 0xefa260f4af84b50b1af14888b86825ae2d4cfe26                         |                                                                                                                        |
| swapper            | VARCHAR   | 0xefa260f4af84b50b1af14888b86825ae2d4cfe26                         |                                                                                                                        |
| swapperData        | VARCHAR   | 0x                                                                 |                                                                                                                        |

## 22. Table: DegenBoxMarkets\_call\_liquidate\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-23 05:23:34+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13668981                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x4be5210339455a47dbb79812c796269a115ebe092789136835b5f3558ee3a59b                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 198                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xcfc571f3203756319c231d3bc643cee807e74636                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| users              | VARCHAR   | 0x06c64b65Ce7e07AF2Dd7Ca4B87ED6AE2a4dEF45E,0x04ECbf6EcEecf07f5BB8E58Db27285385D9c734B |                                                                                                                        |
| maxBorrowParts     | VARCHAR   | 37100742389609577536,10859217697096056962823                                          |                                                                                                                        |
| to                 | VARCHAR   | 0xef633d1af20ed99a69b7cf46da5be63da07ed5ee                                            |                                                                                                                        |
| swapper            | VARCHAR   | 0xef633d1af20ed99a69b7cf46da5be63da07ed5ee                                            |                                                                                                                        |

## 23. Table: DegenBoxMarkets\_event\_LogAccrue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 11:23:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17662938                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb8b63e67a901eac59056f70264a7b53ffc674183f8ee10c5a82d4876a1417ed8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x390db10e65b5ab920c19149c919d970ad9d18a41                         | Address of the contract that produced the log                |
| accruedAmount     | VARCHAR   | 0                                                                  |                                                              |

## 24. Table: DegenBoxMarkets\_event\_LogAddCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-26 01:57:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14078449                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96c8e9b28727c611babc73be7e975b91e01b470d96342e30b20e34c9494b1d11 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 349                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x59e9082e068ddb27fc5ef1690f9a9f22b32e573f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x5466c62cd467da0bb5082a8336e263cefc19b684                         |                                                              |
| to                | VARCHAR   | 0x5466c62cd467da0bb5082a8336e263cefc19b684                         |                                                              |
| share             | VARCHAR   | 358628275934184613337085                                           |                                                              |

## 25. Table: DegenBoxMarkets\_event\_LogBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-06 04:48:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14913072                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6a56c548eb3e8337fbb2b8ba24e1da24fdaa8b2a73ea648f4fdae1eed006845e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 539                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x390db10e65b5ab920c19149c919d970ad9d18a41                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xf2f5c604ade75c3d07d8b973a0d430d1d05e2c72                         |                                                              |
| to                | VARCHAR   | 0x205d52e9ea8e42659ac5c7f83863b18d27d7e0f5                         |                                                              |
| amount            | VARCHAR   | 19378224624264844278513                                            |                                                              |
| part              | VARCHAR   | 19378224624264844278513                                            |                                                              |

## 26. Table: DegenBoxMarkets\_event\_LogChangeBorrowLimit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-20 08:49:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17733295                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x95a069604853128e2d9eb641aa2cd38365977f52163c93b1e8a2c6dd20882359 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x207763511da879a900973a5e092382117c3c1588                         | Address of the contract that produced the log                |
| newLimit          | VARCHAR   | 0                                                                  |                                                              |
| perAddressPart    | VARCHAR   | 0                                                                  |                                                              |

## 27. Table: DegenBoxMarkets\_event\_LogExchangeRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-22 14:58:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15589626                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fcfa41619d71005d96ffde9289907fe267ed7fd2ca3d86ce940732a56aaafd3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 355                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x390db10e65b5ab920c19149c919d970ad9d18a41                         | Address of the contract that produced the log                |
| rate              | VARCHAR   | 787866850502265                                                    |                                                              |

## 28. Table: DegenBoxMarkets\_event\_LogFeeTo\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newFeeTo          | VARCHAR   |                                                              |             |

## 29. Table: DegenBoxMarkets\_event\_LogInterestChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-09 15:35:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15933399                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7fc897b318887ae8730a15d58e4c014c0eaf173679a7ba46f288b221dc024f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 384                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7ce7d9ed62b9a6c5ace1c6ec9aeb115fa3064757                         | Address of the contract that produced the log                |
| oldInterestRate   | VARCHAR   | 317097920                                                          |                                                              |
| newInterestRate   | VARCHAR   | 554921359                                                          |                                                              |

## 30. Table: DegenBoxMarkets\_event\_LogLiquidation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-03 01:33:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16744742                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9c74dfd0d9af75d3ea38483925b047de4940c9cfe099f0d48439696de0fcedde | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7259e152103756e1616a77ae982353c3751a6a90                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3a528be77583b840afed1a6a6621a14b8c91b7d4                         |                                                              |
| user              | VARCHAR   | 0x634c594de9d4154ed93251e6c0692fe00a4b9797                         |                                                              |
| to                | VARCHAR   | 0x94985eb543d3c83c71f51163175f3405803711c8                         |                                                              |
| collateralShare   | VARCHAR   | 20795528888897304473                                               |                                                              |
| borrowAmount      | VARCHAR   | 20317660626552857321566                                            |                                                              |
| borrowPart        | VARCHAR   | 20222309042092515123101                                            |                                                              |

## 31. Table: DegenBoxMarkets\_event\_LogRemoveCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 18:34:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15562246                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x59fd479d1854d2926ba343d0d7a2bc69b6758fd3fcecf207f806d13b5a1ff033 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x390db10e65b5ab920c19149c919d970ad9d18a41                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x62081e1f2c12b0f0062c70c7910d0268629f9715                         |                                                              |
| to                | VARCHAR   | 0xa38a86a72fd68549aedf69fc8c3bad2b115711ba                         |                                                              |
| share             | VARCHAR   | 1502379682529326212                                                |                                                              |

## 32. Table: DegenBoxMarkets\_event\_LogRepayForAll\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| amount            | VARCHAR   |                                                              |             |
| previousElastic   | VARCHAR   |                                                              |             |
| newElastic        | VARCHAR   |                                                              |             |

## 33. Table: DegenBoxMarkets\_event\_LogRepay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 21:32:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13641767                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf31bf4efdd5cc0545a30e284bfd100ef60ffec9b623d6d454da7e030802f56fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbc36fde44a7fd8f545d459452ef9539d7a14dd63                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x8d0dc685785236f0f23c273b114ee15f1b5de807                         |                                                              |
| to                | VARCHAR   | 0x8d0dc685785236f0f23c273b114ee15f1b5de807                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |
| part              | VARCHAR   | 0                                                                  |                                                              |

## 34. Table: DegenBoxMarkets\_event\_LogWithdrawFees\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-07-17 11:25:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17712668                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xb2fe7e27c4afe545bd42e07c0ddf00b002fd62365e96f4f91216fbef9e3c946a | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 191                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x5ec47ee69bede0b6c2a2fc0d9d094df16c192498                         | Address of the contract that produced the log                |
| feeTo              | VARCHAR   | 0x2c9f65bd1a501cb406584f5532ce57c28829b131                         |                                                              |
| feesEarnedFraction | VARCHAR   | 0                                                                  |                                                              |

## 35. Table: DegenBox\_event\_LogDeploy\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-24 15:54:23+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16477693                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b86f88bd4168124e06937c515fd6ccd800d2768b078c16561fa5addbf7e35d9                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd96f48665a1410c0cd669a88898eca36b9fc2cce                                                           | Address of the contract that produced the log                |
| masterContract    | VARCHAR   | 0x369d81cf263abc7ee567d8836a39234141d4da07                                                           |                                                              |
| data              | VARCHAR   | 0x00000000000000000000000038ea452219524bb87e18de1c24d3bb59510bd783000000000000000000000000abb326cd92 |                                                              |
| cloneAddress      | VARCHAR   | 0x1062eb452f8c7a94276437ec1f4aaca9b1495b72                                                           |                                                              |

## 36. Table: DegenBox\_event\_LogDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 18:15:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14756387                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x321e217af878655d8b1b94edc46803cc03c3adb91b52bdbddfea772bdd0d7246 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd96f48665a1410c0cd669a88898eca36b9fc2cce                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x090185f2135308bad17527004364ebcc2d37e5f6                         |                                                              |
| from              | VARCHAR   | 0x0df6242b6b88c5ed789f5c8994a80ffc6979eb4b                         |                                                              |
| to                | VARCHAR   | 0x0df6242b6b88c5ed789f5c8994a80ffc6979eb4b                         |                                                              |
| amount            | VARCHAR   | 7000000000000000000000000                                          |                                                              |
| share             | VARCHAR   | 7000000000000000000000000                                          |                                                              |

## 37. Table: DegenBox\_event\_LogFlashLoan\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-29 22:14:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16935837                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe460ff9f3b2728cdc433ee7f0d94c6359aa1922b1624ba3d1c1717517aee272d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd96f48665a1410c0cd669a88898eca36b9fc2cce                         | Address of the contract that produced the log                |
| borrower          | VARCHAR   | 0x6d00a82b1273cf3ca825f04ad5377deaf565d363                         |                                                              |
| token             | VARCHAR   | 0xd533a949740bb3306d119cc777fa900ba034cd52                         |                                                              |
| amount            | VARCHAR   | 300000000000000000000000                                           |                                                              |
| feeAmount         | VARCHAR   | 150000000000000000000                                              |                                                              |
| receiver          | VARCHAR   | 0x6d00a82b1273cf3ca825f04ad5377deaf565d363                         |                                                              |

## 38. Table: DegenBox\_event\_LogWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-14 14:27:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14584067                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c7460d943be40a4f820c984e38474b222edab0f4b6b601c1c6011dc30c618d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 518                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd96f48665a1410c0cd669a88898eca36b9fc2cce                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x090185f2135308bad17527004364ebcc2d37e5f6                         |                                                              |
| from              | VARCHAR   | 0xef633d1af20ed99a69b7cf46da5be63da07ed5ee                         |                                                              |
| to                | VARCHAR   | 0xb5de0c3753b6e1b4dba616db82767f17513e6d4e                         |                                                              |
| amount            | VARCHAR   | 3876713623701094649732112                                          |                                                              |
| share             | VARCHAR   | 3876713623701094649732112                                          |                                                              |

## 39. Table: MagicInternetMoneyV1\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 21:29:34+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15373661                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c7cb55903147345800e63903a48b0bf3886b343f8d55886d6d209d5eee96f74             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 89                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x99d8a9c45b2eca8864373a26d1459e3dff1e17f3                                     | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x1ae6912e08bb3e105a4f0a60f666376d3c7af380                                     |                                                              |
| \_spender         | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                                     |                                                              |
| \_value           | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 40. Table: MagicInternetMoneyV1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-25 22:05:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12506070                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcea51fd586ad0cbd97a6de264e6d30b014ee73704dfb691404b25ff6d41ea1c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x99d8a9c45b2eca8864373a26d1459e3dff1e17f3                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xb4efda6daf5ef75d08869a0f9c0213278fb43b6c                         |                                                              |
| newOwner          | VARCHAR   | 0xfddfe525054efaad204600d00ca86adb1cc2ea8a                         |                                                              |

## 41. Table: MagicInternetMoneyV1\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 08:21:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14138412                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x247ddf1c4213a181a449c33effff628d7d6f06b86736b2c53433c1e737ff686d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x99d8a9c45b2eca8864373a26d1459e3dff1e17f3                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x3c92ca4364972c3736437dcb17236cdb4096303f                         |                                                              |
| \_to              | VARCHAR   | 0x3e5a6af33cc70646bc46aff0af4b930d92856b18                         |                                                              |
| \_value           | VARCHAR   | 2615300799716587465924                                             |                                                              |

## 42. Table: Markets\_event\_LogAccrue\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 10:01:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14158267                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x68d3c4ff6ccd10f22d1168e75703b541f4919ca4ab3d6f0d9fbb9efa21cb9803 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x003d5a75d284824af736df51933be522de9eed0f                         | Address of the contract that produced the log                |
| accruedAmount     | VARCHAR   | 28886366947475813785                                               |                                                              |

## 43. Table: Markets\_event\_LogAddCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-11 07:06:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13982758                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23455cd0803760f5f8a304576d3bd7042e913f8d0c0bc94074fd33726e00edf7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x003d5a75d284824af736df51933be522de9eed0f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xf9db11765b958562287d8bc00e773a6d43923308                         |                                                              |
| to                | VARCHAR   | 0xf9db11765b958562287d8bc00e773a6d43923308                         |                                                              |
| share             | VARCHAR   | 824538263683891275                                                 |                                                              |

## 44. Table: Markets\_event\_LogBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-22 00:46:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13851886                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb4e8cfb2c5b529a0a8cee9e48ff99028070044ae2dffaa7a46649582f4cb51df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x05500e2ee779329698df35760bedcaac046e7c27                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x5c6a63800abf1dc4594b4243a819ae3ddd04aa56                         |                                                              |
| to                | VARCHAR   | 0x5c6a63800abf1dc4594b4243a819ae3ddd04aa56                         |                                                              |
| amount            | VARCHAR   | 1079431422585000000000                                             |                                                              |
| part              | VARCHAR   | 1076176578561685855468                                             |                                                              |

## 45. Table: Markets\_event\_LogChangeBorrowLimit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-10 14:52:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14749193                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b4f8fcd3b427c50917d3f79b976fddcdd227a454a2f2903a54176ec5ecb025f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 161                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc6b2b3fe7c3d7a6f823d9106e22e66660709001e                         | Address of the contract that produced the log                |
| newLimit          | VARCHAR   | 200000000000000000000000000                                        |                                                              |
| perAddressPart    | VARCHAR   | 2000000000000000000000000                                          |                                                              |

## 46. Table: Markets\_event\_LogExchangeRate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-25 15:28:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14456253                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e73fa4a70c06a6a67e1d787a4b383972281ca97bb7131c78ebc26dd3680433e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x05500e2ee779329698df35760bedcaac046e7c27                         | Address of the contract that produced the log                |
| rate              | VARCHAR   | 721943560438044767                                                 |                                                              |

## 47. Table: Markets\_event\_LogFeeTo\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newFeeTo          | VARCHAR   |                                                              |             |

## 48. Table: Markets\_event\_LogInterestChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-09 15:35:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15933399                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7fc897b318887ae8730a15d58e4c014c0eaf173679a7ba46f288b221dc024f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 384                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7ce7d9ed62b9a6c5ace1c6ec9aeb115fa3064757                         | Address of the contract that produced the log                |
| oldInterestRate   | VARCHAR   | 317097920                                                          |                                                              |
| newInterestRate   | VARCHAR   | 554921359                                                          |                                                              |

## 49. Table: Markets\_event\_LogLiquidation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-11 04:46:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16802563                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08fae2f9960996efa573d921163e29bcdaf9642cf8a033ef51310059889fed05 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 35                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd31e19a0574dbf09310c3b06f3416661b4dc7324                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0edc1e3a69ff68cf34bdffa83f2f69d2c48170a1                         |                                                              |
| user              | VARCHAR   | 0x91b0263b945d9f17207ba168921a25ec7c0d361a                         |                                                              |
| to                | VARCHAR   | 0xe5f62c9f0923c1305c4547dfbb2d96b5ea6e1bdf                         |                                                              |
| collateralShare   | VARCHAR   | 48804155093                                                        |                                                              |
| borrowAmount      | VARCHAR   | 46932162668923562480242                                            |                                                              |
| borrowPart        | VARCHAR   | 46753122069775653011456                                            |                                                              |

## 50. Table: Markets\_event\_LogRemoveCollateral\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 21:24:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17431136                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0065c759a29f55c074042b6bf579267007921708146df8d25ff92f5e1bb54af | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 320                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x390db10e65b5ab920c19149c919d970ad9d18a41                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x454c24b6044ad7cbe1040577127316615857f7e1                         |                                                              |
| to                | VARCHAR   | 0x454c24b6044ad7cbe1040577127316615857f7e1                         |                                                              |
| share             | VARCHAR   | 223782635412033682                                                 |                                                              |

## 51. Table: Markets\_event\_LogRepay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-29 09:56:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13899513                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x038ca9fbe0f6dfe31c7af541b8e66fd33c972b18084a9e16527734a5362f41f7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x003d5a75d284824af736df51933be522de9eed0f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x04b7e92c47e265a9efc327ac00b6831bed4f66af                         |                                                              |
| to                | VARCHAR   | 0x04b7e92c47e265a9efc327ac00b6831bed4f66af                         |                                                              |
| amount            | VARCHAR   | 34983100627999999999999                                            |                                                              |
| part              | VARCHAR   | 34310839876250451891794                                            |                                                              |

## 52. Table: Markets\_event\_LogWithdrawFees\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-09-17 13:24:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 13243428                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x4cf21b84d7ee019eaccc8681e6f54c8d86b5253e6f825a4702c0fd18b76e216e | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 453                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x920d9bd936da4eafb5e25c6bdc9f6cb528953f9f                         | Address of the contract that produced the log                |
| feeTo              | VARCHAR   | 0xd9a89aa4dab9d1033f97890b7ffa6ae1564bf026                         |                                                              |
| feesEarnedFraction | VARCHAR   | 5147406070338423598100                                             |                                                              |
