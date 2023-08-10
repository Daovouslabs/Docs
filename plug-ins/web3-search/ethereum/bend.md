# bend

## 1. Table: InterestRate\_call\_calculateInterestRates\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-29 04:22:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16288000                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x34a561bcbef8a7575ed7d91850d1827b99104ddccd6d7123797844662be0dd1c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 77                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,5,0,0,10                                                         | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2a41398b89d1b9a3919d5b0feb4cc582f5b48c64                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| reserve            | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                                                                                        |
| bToken             | VARCHAR   | 0xed1840223484483c0cb050e6fc344d1ebf0778a9                         |                                                                                                                        |
| liquidityAdded     | VARCHAR   | 3119269302613592659                                                |                                                                                                                        |
| liquidityTaken     | VARCHAR   | 0                                                                  |                                                                                                                        |
| totalVariableDebt  | VARCHAR   | 17200535940716154489135                                            |                                                                                                                        |
| reserveFactor      | VARCHAR   | 3000                                                               |                                                                                                                        |

## 2. Table: LendPoolLoan\_event\_LoanCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-19 01:17:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15778820                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd1b84dec5bb8479439afff5d76ffb97ccea0f354197be95fb26107b7e31f7f5c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f6ac80cdb9e87f3cfa6a90e5140b9a16a361d5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x6a4fecb4c83d1cdcce7ff17f20952ae5cdcda580                         |                                                              |
| loanId            | VARCHAR   | 4371                                                               |                                                              |
| nftAsset          | VARCHAR   | 0x49cf6f5d44e70224e2e23fdcdd2c053f30ada28b                         |                                                              |
| nftTokenId        | VARCHAR   | 19386                                                              |                                                              |
| reserveAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 2438300000000000000                                                |                                                              |
| borrowIndex       | VARCHAR   | 1146564406294761943015818121                                       |                                                              |

## 3. Table: LendPoolLoan\_event\_LoanLiquidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-17 08:50:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15357754                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fda889e12703a2c60878949a21350867486831c9bb3dd4b9c44b9cc5259457d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 444                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f6ac80cdb9e87f3cfa6a90e5140b9a16a361d5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x680e19a60fb02cfe4ffaba98bf9f1c6ee4ecd808                         |                                                              |
| loanId            | VARCHAR   | 777                                                                |                                                              |
| nftAsset          | VARCHAR   | 0xed5af388653567af2f388e6224dc7c4b3241c544                         |                                                              |
| nftTokenId        | VARCHAR   | 1730                                                               |                                                              |
| reserveAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 6094587908743338581                                                |                                                              |
| borrowIndex       | VARCHAR   | 1075281517550596567873465623                                       |                                                              |

## 4. Table: LendPoolLoan\_event\_LoanRedeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-16 19:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17061645                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8046b6e1a24009823044e6ac0d5854c2e793b8510d803d82c1de2f42fad6db6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 292                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f6ac80cdb9e87f3cfa6a90e5140b9a16a361d5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| loanId            | VARCHAR   | 2992                                                               |                                                              |
| nftAsset          | VARCHAR   | 0x620b70123fb810f6c653da7644b5dd0b6312e4d8                         |                                                              |
| nftTokenId        | VARCHAR   | 820                                                                |                                                              |
| reserveAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amountTaken       | VARCHAR   | 1830200000000000000                                                |                                                              |
| borrowIndex       | VARCHAR   | 1315887092939987662125052220                                       |                                                              |

## 5. Table: LendPoolLoan\_event\_LoanRepaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 15:08:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16905270                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x992c1a38b7ddbe942bb12c7800508b803219ce77925b4986a8fd143d76a4c92f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f6ac80cdb9e87f3cfa6a90e5140b9a16a361d5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| loanId            | VARCHAR   | 8712                                                               |                                                              |
| nftAsset          | VARCHAR   | 0x60e4d786628fea6478f785a6d7e704777c86a7c6                         |                                                              |
| nftTokenId        | VARCHAR   | 14788                                                              |                                                              |
| reserveAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 28982526129743898                                                  |                                                              |
| borrowIndex       | VARCHAR   | 1293273837152885236344939429                                       |                                                              |

## 6. Table: LendPool\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 10:22:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17748046                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x30dbc1bc8c354aa2527bfec4418ef4e4e7f0abbb4076b14e0477e67850522188 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 390                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70b97a0da65c15dfb0ffa02aee6fa36e507c2762                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 6800000000000000000                                                |                                                              |
| nftAsset          | VARCHAR   | 0x08f5f0126af89b4fd5499e942891d904a027624b                         |                                                              |
| nftTokenId        | VARCHAR   | 9723                                                               |                                                              |
| onBehalfOf        | VARCHAR   | 0xcf0b4de4296e768960f04324a390af94f81192b5                         |                                                              |
| borrowRate        | VARCHAR   | 258778314534795475049716972                                        |                                                              |
| loanId            | VARCHAR   | 11024                                                              |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 7. Table: LendPool\_event\_Liquidate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-12 00:44:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16609181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x886ac9bc134608d9f0771e2651fd92d4b94c66aa2cb3fcb3b484088dbfdf9d15 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70b97a0da65c15dfb0ffa02aee6fa36e507c2762                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xf33eb2b631cdecf4b09dacd7e6c5b1713a6e890c                         |                                                              |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| repayAmount       | VARCHAR   | 4443789099531691755                                                |                                                              |
| remainAmount      | VARCHAR   | 155710900468308245                                                 |                                                              |
| nftAsset          | VARCHAR   | 0x8a90cab2b38dba80c64b7734e58ee1db38b8992e                         |                                                              |
| nftTokenId        | VARCHAR   | 898                                                                |                                                              |
| borrower          | VARCHAR   | 0x4b6892cc49dfa267894443591284b007ce1cea8f                         |                                                              |
| loanId            | VARCHAR   | 2079                                                               |                                                              |

## 8. Table: LendPool\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-23 19:55:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16892452                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa5df1891ce639c7b4515c7532dd37f071487ba63c5f99d82901fd5ca8b053440 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70b97a0da65c15dfb0ffa02aee6fa36e507c2762                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| borrowAmount      | VARCHAR   | 5030818199172312303                                                |                                                              |
| fineAmount        | VARCHAR   | 497605910283796518                                                 |                                                              |
| nftAsset          | VARCHAR   | 0x60e4d786628fea6478f785a6d7e704777c86a7c6                         |                                                              |
| nftTokenId        | VARCHAR   | 4852                                                               |                                                              |
| borrower          | VARCHAR   | 0xf70243aa38eadfe37483ceda98843c206d0b8b52                         |                                                              |
| loanId            | VARCHAR   | 6145                                                               |                                                              |

## 9. Table: LendPool\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-14 23:04:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15749516                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70f033f9e5b9ad561afee2bd3ee750dfd076d1fa6834e32a03e31ecaa6b42700 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 329                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70b97a0da65c15dfb0ffa02aee6fa36e507c2762                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 3457759414720071602                                                |                                                              |
| nftAsset          | VARCHAR   | 0xed5af388653567af2f388e6224dc7c4b3241c544                         |                                                              |
| nftTokenId        | VARCHAR   | 7390                                                               |                                                              |
| borrower          | VARCHAR   | 0x113ee41d97416d0afb2915e9c4ed6d4a4e9c299b                         |                                                              |
| loanId            | VARCHAR   | 3484                                                               |                                                              |

## 10. Table: bend\_InterestRate\_call\_calculateInterestRates\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-21 18:39:44+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14431361                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3a366c86ce013e36d645d573dad9cffa547d289e5c09722f0676dd68a7a7c7d3 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 93                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2,0,3                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xba061eecd101daeed3eb87504903702a6b5708cd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| reserve            | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                                                                                        |
| bToken             | VARCHAR   | 0xed1840223484483c0cb050e6fc344d1ebf0778a9                         |                                                                                                                        |
| liquidityAdded     | VARCHAR   | 50000000000000000000                                               |                                                                                                                        |
| liquidityTaken     | VARCHAR   | 0                                                                  |                                                                                                                        |
| totalVariableDebt  | VARCHAR   | 0                                                                  |                                                                                                                        |
| reserveFactor      | VARCHAR   | 3000                                                               |                                                                                                                        |

## 11. Table: bend\_LendPoolLoan\_event\_LoanCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 00:57:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15921871                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ddcd60b76ac9075e4533d2e3eee00e1eddf1d9cb71fd69053a90a5b18f91a68 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f6ac80cdb9e87f3cfa6a90e5140b9a16a361d5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| onBehalfOf        | VARCHAR   | 0x0c5caf4ae0af3f2f3ddbe02a8022e62c38d5370b                         |                                                              |
| loanId            | VARCHAR   | 4584                                                               |                                                              |
| nftAsset          | VARCHAR   | 0xb7f7f6c52f2e2fdb1963eab30438024864c313f6                         |                                                              |
| nftTokenId        | VARCHAR   | 7987                                                               |                                                              |
| reserveAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 14104500000000000000                                               |                                                              |
| borrowIndex       | VARCHAR   | 1164049239818119678730535488                                       |                                                              |

## 12. Table: bend\_LendPoolLoan\_event\_LoanLiquidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 04:47:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15973144                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf31f3847063c5e2672aa7ce44b74b8e2a366fec99d75625b39759495c06922f0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 207                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f6ac80cdb9e87f3cfa6a90e5140b9a16a361d5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x916cddd297fb6daf63fab22f9d7fe86c0ce12876                         |                                                              |
| loanId            | VARCHAR   | 1142                                                               |                                                              |
| nftAsset          | VARCHAR   | 0x60e4d786628fea6478f785a6d7e704777c86a7c6                         |                                                              |
| nftTokenId        | VARCHAR   | 15002                                                              |                                                              |
| reserveAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 8435598459371342369                                                |                                                              |
| borrowIndex       | VARCHAR   | 1170732519715552193938627441                                       |                                                              |

## 13. Table: bend\_LendPoolLoan\_event\_LoanRedeemed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 21:09:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17523482                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98595cd03c341b60450689d5bf64de10539ecb7c73a9a845dc49da776a5d75a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 193                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f6ac80cdb9e87f3cfa6a90e5140b9a16a361d5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| loanId            | VARCHAR   | 6625                                                               |                                                              |
| nftAsset          | VARCHAR   | 0x60e4d786628fea6478f785a6d7e704777c86a7c6                         |                                                              |
| nftTokenId        | VARCHAR   | 17790                                                              |                                                              |
| reserveAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amountTaken       | VARCHAR   | 3295308624633570762                                                |                                                              |
| borrowIndex       | VARCHAR   | 1380864182018266034345729611                                       |                                                              |

## 14. Table: bend\_LendPoolLoan\_event\_LoanRepaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 14:21:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16140553                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b5b4e639d1f664234cb967de2feaae35bde26ca10a0d3fd9063311a19c0156e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f6ac80cdb9e87f3cfa6a90e5140b9a16a361d5c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| loanId            | VARCHAR   | 5210                                                               |                                                              |
| nftAsset          | VARCHAR   | 0x49cf6f5d44e70224e2e23fdcdd2c053f30ada28b                         |                                                              |
| nftTokenId        | VARCHAR   | 18715                                                              |                                                              |
| reserveAsset      | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 500001453845539666                                                 |                                                              |
| borrowIndex       | VARCHAR   | 1191101368703862772743529184                                       |                                                              |

## 15. Table: bend\_LendPool\_event\_Borrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-08 20:20:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16142338                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x192c7f305cab74f2b8d1fab3230007689eda4f2d8520470adc5f933df8e37ffc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70b97a0da65c15dfb0ffa02aee6fa36e507c2762                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 408700000000000000                                                 |                                                              |
| nftAsset          | VARCHAR   | 0x49cf6f5d44e70224e2e23fdcdd2c053f30ada28b                         |                                                              |
| nftTokenId        | VARCHAR   | 18241                                                              |                                                              |
| onBehalfOf        | VARCHAR   | 0x9f47cb203803c58d2dd138ece9f139fa283776a7                         |                                                              |
| borrowRate        | VARCHAR   | 273295382301806507630789852                                        |                                                              |
| loanId            | VARCHAR   | 5138                                                               |                                                              |
| referral          | VARCHAR   | 0                                                                  |                                                              |

## 16. Table: bend\_LendPool\_event\_Liquidate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-24 13:54:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15403291                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8509e04b6c60fabb64f936d14828e44804a1f9845f28ae0cd41f07582c71e83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70b97a0da65c15dfb0ffa02aee6fa36e507c2762                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| repayAmount       | VARCHAR   | 12056637853360551226                                               |                                                              |
| remainAmount      | VARCHAR   | 1693362146639448774                                                |                                                              |
| nftAsset          | VARCHAR   | 0x60e4d786628fea6478f785a6d7e704777c86a7c6                         |                                                              |
| nftTokenId        | VARCHAR   | 4737                                                               |                                                              |
| borrower          | VARCHAR   | 0x05689959dc890cfced4830094b4b45e85828bfcd                         |                                                              |
| loanId            | VARCHAR   | 130                                                                |                                                              |

## 17. Table: bend\_LendPool\_event\_Redeem\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-22 03:51:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17099321                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf659373d28a0909e25682c97befc50d48a04f1316a82dba5ed599444e3d63d7b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 240                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70b97a0da65c15dfb0ffa02aee6fa36e507c2762                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| borrowAmount      | VARCHAR   | 4016828076117899455                                                |                                                              |
| fineAmount        | VARCHAR   | 397299104237712406                                                 |                                                              |
| nftAsset          | VARCHAR   | 0x60e4d786628fea6478f785a6d7e704777c86a7c6                         |                                                              |
| nftTokenId        | VARCHAR   | 935                                                                |                                                              |
| borrower          | VARCHAR   | 0x2711d9ad032d36e1c34bbd28a6b6e369b8ad5232                         |                                                              |
| loanId            | VARCHAR   | 219                                                                |                                                              |

## 18. Table: bend\_LendPool\_event\_Repay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-22 03:10:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15586117                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce76e7afdcf09b77c920ed0b8c6cef8f44169cc35353760a5836cd4b3f979858 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x70b97a0da65c15dfb0ffa02aee6fa36e507c2762                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b968d2d299b895a5fcf3bba7a64ad0f566e6f88                         |                                                              |
| reserve           | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| amount            | VARCHAR   | 1264586513267092666                                                |                                                              |
| nftAsset          | VARCHAR   | 0x49cf6f5d44e70224e2e23fdcdd2c053f30ada28b                         |                                                              |
| nftTokenId        | VARCHAR   | 17691                                                              |                                                              |
| borrower          | VARCHAR   | 0xa87efc5d6ff2849a4aa638f9db7cd70af3a552b5                         |                                                              |
| loanId            | VARCHAR   | 3902                                                               |                                                              |
