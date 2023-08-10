# arcade

## 1. Table: AssetWrapper\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-01 18:12:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13532687                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x23f31e377822689e477e9ea73f5fa522bab0cc30fc05c68a05a30936b675ba78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f563cdd688ad47b75e474fde74e87c643d129b7                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xd96352d264526e78a92229c83a29b1d7159ce031                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 20                                                                 |                                                              |

## 2. Table: AssetWrapper\_event\_DepositERC1155\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-19 14:40:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14036555                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9462c77a5da3a408534bdee96318dcd3368594f6f78d1fbeb21501d11992649 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 210                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f563cdd688ad47b75e474fde74e87c643d129b7                         | Address of the contract that produced the log                |
| depositor         | VARCHAR   | 0x7c99670ecc3a57cd1a8d1bdfc8e2ff5b4527b382                         |                                                              |
| bundleId          | VARCHAR   | 40                                                                 |                                                              |
| tokenAddress      | VARCHAR   | 0xe4605d46fd0b3f8329d936a8b258d69276cba264                         |                                                              |
| tokenId           | VARCHAR   | 142                                                                |                                                              |
| amount            | VARCHAR   | 1                                                                  |                                                              |

## 3. Table: AssetWrapper\_event\_DepositERC20\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-12 16:28:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13011434                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8495be64d9d55dea8327eb44fe0a16ff030a961dc9dfddb9a4e8f9de4e367797 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f563cdd688ad47b75e474fde74e87c643d129b7                         | Address of the contract that produced the log                |
| depositor         | VARCHAR   | 0x2e2dbda311f6b34a2a17fcdcecff86597c6bdf40                         |                                                              |
| bundleId          | VARCHAR   | 0                                                                  |                                                              |
| tokenAddress      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 100000000000000000                                                 |                                                              |

## 4. Table: AssetWrapper\_event\_DepositERC721\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-31 23:29:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13136280                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f6f4624794bcbe5fb15164fab19e2266358de59648f5e348cf2708f1672c412 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 250                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f563cdd688ad47b75e474fde74e87c643d129b7                         | Address of the contract that produced the log                |
| depositor         | VARCHAR   | 0x2e2dbda311f6b34a2a17fcdcecff86597c6bdf40                         |                                                              |
| bundleId          | VARCHAR   | 8                                                                  |                                                              |
| tokenAddress      | VARCHAR   | 0x2a46f2ffd99e19a89476e2f62270e0a35bbf0756                         |                                                              |
| tokenId           | VARCHAR   | 31308                                                              |                                                              |

## 5. Table: AssetWrapper\_event\_DepositETH\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| depositor         | VARCHAR   |                                                              |             |
| bundleId          | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 6. Table: AssetWrapper\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-19 20:54:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13450445                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa6a9d5933c45f94cf76e4698775dfa5d99673d50962ed55a193145acf7b98460 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f563cdd688ad47b75e474fde74e87c643d129b7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xd96352d264526e78a92229c83a29b1d7159ce031                         |                                                              |
| tokenId           | VARCHAR   | 20                                                                 |                                                              |

## 7. Table: AssetWrapper\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-27 18:44:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13501051                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x97d4afae3b3f3ccd02985bc0260a3b0f20fc57731ced763b1ff68d8df94f08d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f563cdd688ad47b75e474fde74e87c643d129b7                         | Address of the contract that produced the log                |
| withdrawer        | VARCHAR   | 0xc7463a4ac3ed8a87a3e8797f5817c0e412a8da37                         |                                                              |
| bundleId          | VARCHAR   | 23                                                                 |                                                              |

## 8. Table: LoanCoreV2\_call\_LoanClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 23:53:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17709240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2cc10869508747e19f1ed9d24ab2a12496f1956bf1253d23c60701d5b662dffc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 2048                                                               |                                                              |

## 9. Table: LoanCoreV2\_call\_LoanCreated\_history

| Column                  | Type                                                                                                                                                                                | Example                                                      | Description |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP                                                                                                                                                                           | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER                                                                                                                                                                             | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR                                                                                                                                                                             | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER                                                                                                                                                                             | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR                                                                                                                                                                             | Address of the contract that produced the log                |             |
| terms                   | STRUCT\<durationSecs STRING, deadline STRING, numInstallments STRING, interestRate STRING, principal STRING, collateralAddress STRING, collateralId STRING, payableCurrency STRING> |                                                              |             |
| terms.durationSecs      | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.deadline          | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.numInstallments   | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.interestRate      | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.principal         | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.collateralAddress | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.collateralId      | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.payableCurrency   | VARCHAR                                                                                                                                                                             |                                                              |             |
| loanId                  | VARCHAR                                                                                                                                                                             |                                                              |             |

## 10. Table: LoanCoreV2\_call\_LoanRepaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-29 01:41:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17148553                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcbe507688e22a7dd4f1342dce92b1972cc1c677f486483e99944d3c147cbc2a3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 359                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 1603                                                               |                                                              |

## 11. Table: LoanCoreV2\_call\_LoanRolledOver\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-27 09:53:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15838646                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x36c03d0cc10a9117e0a7183c102590a845116bf3adaa946acb0feaa9d24b7ed3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 495                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the contract that produced the log                |
| oldLoanId         | VARCHAR   | 186                                                                |                                                              |
| newLoanId         | VARCHAR   | 268                                                                |                                                              |

## 12. Table: LoanCoreV2\_call\_LoanStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-03 04:42:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16966213                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb580f272561dbe2127b350a73f0a705155878de83c9dbf1aa6c1239a0ed5e10 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 305                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 1485                                                               |                                                              |
| lender            | VARCHAR   | 0xa66515af0dfd9aa7fd5d0d8ee49db19085f884b1                         |                                                              |
| borrower          | VARCHAR   | 0x99b8226ec774c957ffe2747fdfbae8f22741e899                         |                                                              |

## 13. Table: LoanCoreV2\_call\_getFullInterestAmount\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-25 01:34:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17553265                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x28f7f7aac47d5068e9682aeedb1fa4828c9b4fcc16d9a9a8c59874fe16084956 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 92                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| principal          | VARCHAR   | 1240000000000000000                                                |                                                                                                                        |
| interestRate       | VARCHAR   | 11170000000000000000                                               |                                                                                                                        |

## 14. Table: LoanCoreV2\_call\_getLoan\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-10 20:41:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17665700                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2bdb22003fc9c13cd492a49a77ff44c8733147a774bc6a84e608a941479f512c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 120                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| loanId             | VARCHAR   | 1989                                                               |                                                                                                                        |

## 15. Table: LoanCoreV2\_call\_pause\_history

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

## 16. Table: LoanCoreV2\_call\_repayPart\_history

| Column                  | Type      | Example                                                                                                                | Description |
| ----------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp        | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number           | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash       | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index      | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address          | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address             | VARCHAR   | Address of the called contract                                                                                         |             |
| status                  | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error                   | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_loanId                | VARCHAR   |                                                                                                                        |             |
| \_currentMissedPayments | VARCHAR   |                                                                                                                        |             |
| \_paymentToPrincipal    | VARCHAR   |                                                                                                                        |             |
| \_paymentToInterest     | VARCHAR   |                                                                                                                        |             |
| \_paymentToLateFees     | VARCHAR   |                                                                                                                        |             |

## 17. Table: LoanCoreV2\_call\_repay\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-11 19:39:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16607665                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xac944b3df3767425b090bda77c916ab0dd91609bfc37c8f1488d982951736d08 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 84                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 3                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| loanId             | VARCHAR   | 873                                                                |                                                                                                                        |

## 18. Table: LoanCoreV2\_call\_rollover\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-02-13 22:59:47+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 16622975                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x644e155f64b32e612b84373c204f3d67f7c83da5a3b3230b73ee4c7c8d6ddc44                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 41                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | 0,12                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| oldLoanId           | VARCHAR   | 965                                                                                                  |                                                                                                                        |
| borrower            | VARCHAR   | 0xcd126ddb47efd449c9b76886b250be341b1049c0                                                           |                                                                                                                        |
| lender              | VARCHAR   | 0xa9cdfc16685a90074c7ce329fea4fd36b47bb87d                                                           |                                                                                                                        |
| terms               | VARCHAR   | 864000,1676672922,0,112359550561797752800,17800000000,0x6e9B4c2f6Bd57b7b924d29b5dcfCa1273Ecc94A2,583 |                                                                                                                        |
| \_settledAmount     | VARCHAR   | 19017147945                                                                                          |                                                                                                                        |
| \_amountToOldLender | VARCHAR   | 19017147945                                                                                          |                                                                                                                        |
| \_amountToLender    | VARCHAR   | 0                                                                                                    |                                                                                                                        |
| \_amountToBorrower  | VARCHAR   | 0                                                                                                    |                                                                                                                        |

## 19. Table: LoanCoreV2\_call\_startLoan\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-29 09:23:35+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15852797                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9cad98a10c403f78d3e4af3f669958675489651bb1bcb5a369de2d2d7829cf25                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 98                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,5                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| lender             | VARCHAR   | 0x31d75becb2fe9cc60eb4877b44110aa1cdae90a5                                                           |                                                                                                                        |
| borrower           | VARCHAR   | 0x94cf5a2106f1654c2ad2b77151e1ecad482ed75f                                                           |                                                                                                                        |
| terms              | VARCHAR   | 2592000,1668244893,0,164359861591695501700,9248000000000000000,0x6e9B4c2f6Bd57b7b924d29b5dcfCa1273Ec |                                                                                                                        |

## 20. Table: LoanCoreV2\_event\_LoanClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-07 10:34:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16576339                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f759d5231a29f53f82427addc3c12cdac9b4da17ba4d51481acb3a498ec332e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 706                                                                |                                                              |

## 21. Table: LoanCoreV2\_event\_LoanCreated\_history

| Column                  | Type                                                                                                                                                                                | Example                                                      | Description |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp        | TIMESTAMP                                                                                                                                                                           | Timestamp of the block where this event was emitted          |             |
| block\_number           | INTEGER                                                                                                                                                                             | The block number where this event was emitted                |             |
| transaction\_hash       | VARCHAR                                                                                                                                                                             | Hash of the transactions in which this event was emitted     |             |
| log\_index              | INTEGER                                                                                                                                                                             | Integer of the log index position in the block of this event |             |
| contract\_address       | VARCHAR                                                                                                                                                                             | Address of the contract that produced the log                |             |
| terms                   | STRUCT\<durationSecs STRING, deadline STRING, numInstallments STRING, interestRate STRING, principal STRING, collateralAddress STRING, collateralId STRING, payableCurrency STRING> |                                                              |             |
| terms.durationSecs      | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.deadline          | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.numInstallments   | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.interestRate      | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.principal         | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.collateralAddress | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.collateralId      | VARCHAR                                                                                                                                                                             |                                                              |             |
| terms.payableCurrency   | VARCHAR                                                                                                                                                                             |                                                              |             |
| loanId                  | VARCHAR                                                                                                                                                                             |                                                              |             |

## 22. Table: LoanCoreV2\_event\_LoanRepaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 16:13:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15308987                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45ed9a2d8e66211efe35cd3a5146d9f52ef0f1f8033e9e7142495fa5ee23c3db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 26                                                                 |                                                              |

## 23. Table: LoanCoreV2\_event\_LoanRolledOver\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-16 19:04:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16643261                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2caf0f371b20fbb16fbaca51836ff5487fa43ac74e903434878a267a605275dd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 769                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the contract that produced the log                |
| oldLoanId         | VARCHAR   | 794                                                                |                                                              |
| newLoanId         | VARCHAR   | 1093                                                               |                                                              |

## 24. Table: LoanCoreV2\_event\_LoanStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-03 02:34:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16965576                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc20f325846744343bc96f749467a21fc2fb28dfa52c2a5ca5594b786ab6c4d0f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 315                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81b2f8fc75bab64a6b144aa6d2faa127b4fa7fd9                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 1484                                                               |                                                              |
| lender            | VARCHAR   | 0x1308303e56ca1e403f319ffcdfcddcee534c9e45                         |                                                              |
| borrower          | VARCHAR   | 0x572c623bfa16f63c5322375e908ac80bade53b8f                         |                                                              |

## 25. Table: LoanCoreV2\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 26. Table: LoanCore\_call\_claim\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-12 09:24:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15953022                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x331d88ebd54270e930da801085467c43abc764a61617c9be2ebd910592136592 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 11                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7691ee8febd406968d46f9de96cb8cc18fc8b325                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| loanId             | VARCHAR   | 18                                                                 |                                                                                                                        |

## 27. Table: LoanCore\_call\_createLoan\_history

| Column             | Type      | Example                                                                                        | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-02 22:31:23+00:00                                                                      | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14700936                                                                                       | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x0d4f4252e30150910da94db95e0afbd8f733b7f5fa549cf7ac22f1dd3cc81a38                             | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 10                                                                                             | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4                                                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7691ee8febd406968d46f9de96cb8cc18fc8b325                                                     | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                              | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                           | Error in case input parsing failed                                                                                     |
| terms              | VARCHAR   | 10368000,2000000000000000000,250000000000000000,378,0xC02aaA39b223FE8D0A0e5C4F27eAD9083C756Cc2 |                                                                                                                        |

## 28. Table: LoanCore\_call\_getLoan\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-31 16:00:36+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14114573                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xec2a39dc3b3a04706c3cac4a6aa289d28c99c3e5b95e228aa77e58a2b57610b9 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 70                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x59e57f9a313a2eb1c7357ecc331ddca14209f403                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| loanId             | VARCHAR   | 24                                                                 |                                                                                                                        |

## 29. Table: LoanCore\_call\_repay\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-18 13:42:36+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14985280                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x47a8a380cfb58a02d33aaed0f0245e81adb7bcb953079a56ca8db5a1ab8a09e0 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 214                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7691ee8febd406968d46f9de96cb8cc18fc8b325                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| loanId             | VARCHAR   | 34                                                                 |                                                                                                                        |

## 30. Table: LoanCore\_call\_startLoan\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-09-01 02:37:21+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13137161                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xeda246087dc66780d27a09ead6fe700e820a67b8091c0b6f865bc4e87f123507 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 281                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 5                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x59e57f9a313a2eb1c7357ecc331ddca14209f403                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| lender             | VARCHAR   | 0x0370a10714f5528bf7db525e087086f59f5fc7e3                         |                                                                                                                        |
| borrower           | VARCHAR   | 0x2e2dbda311f6b34a2a17fcdcecff86597c6bdf40                         |                                                                                                                        |
| loanId             | VARCHAR   | 3                                                                  |                                                                                                                        |

## 31. Table: LoanCore\_event\_LoanClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-17 20:51:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17068968                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa1c4af3f2cad0c1895acf2941c3eec6fbf01a836a5a4c46911cf2fb67b81d4ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 105                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7691ee8febd406968d46f9de96cb8cc18fc8b325                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 13                                                                 |                                                              |

## 32. Table: LoanCore\_event\_LoanCreated\_history

| Column                  | Type                                                                                                              | Example                                                                                              | Description                                                  |
| ----------------------- | ----------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP                                                                                                         | 2021-12-01 10:20:38+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER                                                                                                           | 13720483                                                                                             | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR                                                                                                           | 0xd04387a1c705507c84b6c3124ba9dca925f8d964db050b22393c80a399f9070d                                   | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER                                                                                                           | 197                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR                                                                                                           | 0x59e57f9a313a2eb1c7357ecc331ddca14209f403                                                           | Address of the contract that produced the log                |
| terms                   | STRUCT\<durationSecs STRING, principal STRING, interest STRING, collateralTokenId STRING, payableCurrency STRING> | {'durationSecs': '7776000', 'principal': '30000000000', 'interest': '2640000000', 'collateralTokenId |                                                              |
| terms.durationSecs      | VARCHAR                                                                                                           | 7776000                                                                                              |                                                              |
| terms.principal         | VARCHAR                                                                                                           | 30000000000                                                                                          |                                                              |
| terms.interest          | VARCHAR                                                                                                           | 2640000000                                                                                           |                                                              |
| terms.collateralTokenId | VARCHAR                                                                                                           | 32                                                                                                   |                                                              |
| terms.payableCurrency   | VARCHAR                                                                                                           | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                                                           |                                                              |
| loanId                  | VARCHAR                                                                                                           | 15                                                                                                   |                                                              |

## 33. Table: LoanCore\_event\_LoanRepaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-22 23:38:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14637662                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x519f81262eb0d0120a38b856cedd7373eba00812a15e0d58b58527c0b967287e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7691ee8febd406968d46f9de96cb8cc18fc8b325                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 15                                                                 |                                                              |

## 34. Table: LoanCore\_event\_LoanStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-04 02:22:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15073324                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0f00efa1c6aa1c15e8d7818b1f519e57147d9aaad14142361f5afb348d24ec27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7691ee8febd406968d46f9de96cb8cc18fc8b325                         | Address of the contract that produced the log                |
| loanId            | VARCHAR   | 39                                                                 |                                                              |
| lender            | VARCHAR   | 0xd4e26683635bf3dc9ead5f31b935c33cc1ce1838                         |                                                              |
| borrower          | VARCHAR   | 0xc997cd38e441841e084c8895b81ee12063e9bbb2                         |                                                              |

## 35. Table: VaultDepositRouter\_call\_depositERC1155Batch\_history

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
| vault              | VARCHAR   |                                                                                                                        |             |
| tokens             | VARCHAR   |                                                                                                                        |             |
| ids                | VARCHAR   |                                                                                                                        |             |
| amounts            | VARCHAR   |                                                                                                                        |             |

## 36. Table: VaultDepositRouter\_call\_depositERC1155\_history

| Column             | Type      | Example                                                                       | Description                                                                                                            |
| ------------------ | --------- | ----------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-28 23:57:59+00:00                                                     | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16929237                                                                      | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x59ae0afa048b038a442a26591a687dfdde4d7d38377ecf7c39e096e6df9b21a4            | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 129                                                                           | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x4b95640d56f81fc851f952793f4e5485e352bed2                                    | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                             | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                          | Error in case input parsing failed                                                                                     |
| vault              | VARCHAR   | 0xaee2b37470156caecbd51da7d6a4dc96f5b049ac                                    |                                                                                                                        |
| token              | VARCHAR   | 0x7e6027a6a84fc1f6db6782c523efe62c923e46ff                                    |                                                                                                                        |
| id                 | VARCHAR   | 57440780210296984802188034416170391862531690240882748609967915435402957019458 |                                                                                                                        |
| amount             | VARCHAR   | 1                                                                             |                                                                                                                        |

## 37. Table: VaultDepositRouter\_call\_depositERC20Batch\_history

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
| vault              | VARCHAR   |                                                                                                                        |             |
| tokens             | VARCHAR   |                                                                                                                        |             |
| amounts            | VARCHAR   |                                                                                                                        |             |

## 38. Table: VaultDepositRouter\_call\_depositERC20\_history

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
| vault              | VARCHAR   |                                                                                                                        |             |
| token              | VARCHAR   |                                                                                                                        |             |
| amount             | VARCHAR   |                                                                                                                        |             |

## 39. Table: VaultDepositRouter\_call\_depositERC721Batch\_history

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
| vault              | VARCHAR   |                                                                                                                        |             |
| tokens             | VARCHAR   |                                                                                                                        |             |
| ids                | VARCHAR   |                                                                                                                        |             |

## 40. Table: VaultDepositRouter\_call\_depositERC721\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-12 21:59:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17034733                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x78ac53d05b70392eecc548390c3a3dacbc516984c613d9d8697dbd72d17d1aae | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 88                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x4b95640d56f81fc851f952793f4e5485e352bed2                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vault              | VARCHAR   | 0xa24a065b6aac8b0babbd0d4ac32d203bf1a50d48                         |                                                                                                                        |
| token              | VARCHAR   | 0x60e4d786628fea6478f785a6d7e704777c86a7c6                         |                                                                                                                        |
| id                 | VARCHAR   | 13452                                                              |                                                                                                                        |

## 41. Table: VaultDepositRouter\_call\_depositPunkBatch\_history

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
| vault              | VARCHAR   |                                                                                                                        |             |
| tokens             | VARCHAR   |                                                                                                                        |             |
| ids                | VARCHAR   |                                                                                                                        |             |

## 42. Table: VaultDepositRouter\_call\_depositPunk\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-22 22:22:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16686912                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf89f928cdfbd825680075b4957fdbacf848693ecbb892b6460c2b7d8ec6a3451 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 184                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xfdda20a20cb4249e73e3356f468ddfdfb61483f6                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vault              | VARCHAR   | 0x3ea75708764f1c44605beb006aba7a830dc369d0                         |                                                                                                                        |
| token              | VARCHAR   | 0xb47e3cd837ddf8e4c57f05d70ab865de6e193bbb                         |                                                                                                                        |
| id                 | VARCHAR   | 8582                                                               |                                                                                                                        |

## 43. Table: VaultFactory\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 14:21:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17792115                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0e7c12830b0d461c2d0572a9238d10d872e4a5aeb5d6a07a06ae3b1ae05691c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 155                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6e9b4c2f6bd57b7b924d29b5dcfca1273ecc94a2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x55016d5d800b17f18244f94817e81b7f88f86c3a                         |                                                              |
| tokenId           | VARCHAR   | 378327629728001414081744602215755560147341444808                   |                                                              |

## 44. Table: VaultFactory\_event\_VaultCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-01 22:35:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16957297                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0906f2f05658f77b47ed0c68013c3452612a2f81d8aefcd96cc157250f607137 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 221                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6e9b4c2f6bd57b7b924d29b5dcfca1273ecc94a2                         | Address of the contract that produced the log                |
| vault             | VARCHAR   | 0xca7daacba7abf44e6c06a301f8548b12b471edee                         |                                                              |
| to                | VARCHAR   | 0x29f088cff86f03036220393c869519329bf69ca7                         |                                                              |
