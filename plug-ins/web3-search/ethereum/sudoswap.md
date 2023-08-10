# sudoswap

## 1. Table: ExponentialCurve\_call\_getBuyInfo\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-02-28 00:52:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 16723222                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0x23195fde9bdf54a02e8409124c53d898256a28811c941aa52cb926d6fc91e50c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 20                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | 2,0,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x432f962d8209781da23fb37b6b59ee15de7d9841                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| spotPrice             | VARCHAR   | 23691068467187874                                                  |                                                                                                                        |
| delta                 | VARCHAR   | 1050000000000000000                                                |                                                                                                                        |
| numItems              | VARCHAR   | 1                                                                  |                                                                                                                        |
| feeMultiplier         | VARCHAR   | 0                                                                  |                                                                                                                        |
| protocolFeeMultiplier | VARCHAR   | 5000000000000000                                                   |                                                                                                                        |

## 2. Table: ExponentialCurve\_call\_getSellInfo\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-06-09 10:42:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 17442152                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0xa108c56a33e409e01fba1e3ca377a17b7fb956f01b9dd12ee3a45d5db5cf70c6 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 107                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | 6,0,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x432f962d8209781da23fb37b6b59ee15de7d9841                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| spotPrice             | VARCHAR   | 9475358266123438                                                   |                                                                                                                        |
| delta                 | VARCHAR   | 1025000000000000000                                                |                                                                                                                        |
| numItems              | VARCHAR   | 6                                                                  |                                                                                                                        |
| feeMultiplier         | VARCHAR   | 10000000000000000                                                  |                                                                                                                        |
| protocolFeeMultiplier | VARCHAR   | 5000000000000000                                                   |                                                                                                                        |

## 3. Table: LSSVMPairFactoryV2\_call\_createPairERC1155ERC20\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-23 00:45:35+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17538805                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe38fbcfd477c15680c634dcaea08ef92d41e7ed5b4060c41ca2c7070fd19eb39                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 24                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa020d57ab0448ef74115c112d18a9c231cc86000                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| params             | VARCHAR   | 0x46898f15F99b8887D87669ab19d633F579939ad9,0x1f6A5CF9366F968C205467BD7a9f382b3454dFB3,0xfa056C602aD0 |                                                                                                                        |

## 4. Table: LSSVMPairFactoryV2\_call\_createPairERC1155ETH\_history

| Column              | Type      | Example                                                            | Description                                                                                                            |
| ------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-06-09 16:11:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 17443774                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x29c63a1da33af3b756a0dcdc0c25d1586e48b20a9971a28979a7db478313dbce | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 158                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xa020d57ab0448ef74115c112d18a9c231cc86000                         | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_nft               | VARCHAR   | 0x7daec605e9e2a1717326eedfd660601e2753a057                         |                                                                                                                        |
| \_bondingCurve      | VARCHAR   | 0xfa056c602ad0c0c4ee4385b3233f2cb06730334a                         |                                                                                                                        |
| \_assetRecipient    | VARCHAR   | 0x2357feaad45a61ee4f663c203f660580430e75c6                         |                                                                                                                        |
| \_poolType          | VARCHAR   | 2                                                                  |                                                                                                                        |
| \_delta             | VARCHAR   | 1040000000000000000                                                |                                                                                                                        |
| \_fee               | VARCHAR   | 16900000000000000                                                  |                                                                                                                        |
| \_spotPrice         | VARCHAR   | 478377344048985840                                                 |                                                                                                                        |
| \_nftId             | VARCHAR   | 13                                                                 |                                                                                                                        |
| \_initialNFTBalance | VARCHAR   | 35                                                                 |                                                                                                                        |

## 5. Table: LSSVMPairFactoryV2\_call\_createPairERC721ERC20\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-23 03:10:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17539521                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3fd31be1fa3730eb11867adadf444a1a17c1bc3b7080e9d41afc8282a4722072                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 12                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa020d57ab0448ef74115c112d18a9c231cc86000                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| params             | VARCHAR   | 0x2890dF158D76E584877a1D17A85FEA3aeeB85aa6,0xD3D9ddd0CF0A5F0BFB8f7fcEAe075DF687eAEBaB,0xfa056C602aD0 |                                                                                                                        |

## 6. Table: LSSVMPairFactoryV2\_call\_createPairERC721ETH\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-10 07:20:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17661746                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc3f6b2885450e0d0a3245ca88e978f687852a0f4081e605037f03c2bcbde2a21 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 35                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa020d57ab0448ef74115c112d18a9c231cc86000                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_nft              | VARCHAR   | 0xcb897d3a455f55e38ea192ea85af8cd19ca65239                         |                                                                                                                        |
| \_bondingCurve     | VARCHAR   | 0xfa056c602ad0c0c4ee4385b3233f2cb06730334a                         |                                                                                                                        |
| \_assetRecipient   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                                                                                        |
| \_poolType         | VARCHAR   | 1                                                                  |                                                                                                                        |
| \_delta            | VARCHAR   | 1010000000000000000                                                |                                                                                                                        |
| \_fee              | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_spotPrice        | VARCHAR   | 2058621703754534                                                   |                                                                                                                        |
| \_propertyChecker  | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                                                                                        |
| \_initialNFTIDs    | VARCHAR   | 7067                                                               |                                                                                                                        |

## 7. Table: LSSVMPairFactoryV2\_event\_NewERC1155Pair\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 20:11:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17829614                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6d13d6ae843553a96d5641eb4a82edeb74630d78020b14e049070b176c1ee30f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 192                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa020d57ab0448ef74115c112d18a9c231cc86000                         | Address of the contract that produced the log                |
| poolAddress       | VARCHAR   | 0x0f5089c5af4017d866cec9ad12a46594f991718e                         |                                                              |
| initialBalance    | VARCHAR   | 500000                                                             |                                                              |

## 8. Table: LSSVMPairFactoryV2\_event\_NewERC721Pair\_history

| Column            | Type      | Example                                                                                             | Description                                                  |
| ----------------- | --------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-09 19:13:35+00:00                                                                           | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17658151                                                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa94acb6f556c4448647c445c9ffe4daeed889b4b5828fb32e581f997b5db3f38                                  | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 354                                                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa020d57ab0448ef74115c112d18a9c231cc86000                                                          | Address of the contract that produced the log                |
| poolAddress       | VARCHAR   | 0x3029ab8f76cabf6be5c976452897254532695e78                                                          |                                                              |
| initialIds        | VARCHAR   | 5346,5330,5335,5339,5332,5337,5334,5336,5331,4974,3221,2563,2084,2085,2081,5347,5348,5340,5341,5343 |                                                              |

## 9. Table: LSSVMPairFactory\_call\_createPairERC20\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-12 23:44:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16171989                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb06e17f3deff71852672e6c245b66ef0a18a508b0c0a1e20b93a4bf833c24023                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 26                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| params             | VARCHAR   | 0x6B175474E89094C44Da98b954EedeAC495271d0F,0xeF1a89cbfAbE59397FfdA11Fc5DF293E9bC5Db90,0x5B6aC51d9B1C |                                                                                                                        |

## 10. Table: LSSVMPairFactory\_call\_createPairETH\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-17 09:03:01+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15357820                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xd44f287a0795b6938e46ba29df351895b959f64ec10a8403f18b78fc18540cc8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 449                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_nft              | VARCHAR   | 0xabefbc9fd2f806065b4f3c237d4b59d9a97bcac7                         |                                                                                                                        |
| \_bondingCurve     | VARCHAR   | 0x5b6ac51d9b1cede0068a1b26533cace807f883ee                         |                                                                                                                        |
| \_assetRecipient   | VARCHAR   | 0xf22fee783c5ae9ff7ee7107c6a42819c86303694                         |                                                                                                                        |
| \_poolType         | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_delta            | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_fee              | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_spotPrice        | VARCHAR   | 542000000000000                                                    |                                                                                                                        |
| \_initialNFTIDs    | VARCHAR   |                                                                    |                                                                                                                        |

## 11. Table: LSSVMPairFactory\_event\_BondingCurveStatusUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-29 17:57:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15435538                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa0338a88450351db9c7aedab867a431fb0327c43cd382ec2ce519f9d80575ac8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 568                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| bondingCurve      | VARCHAR   | 0x7942e264e21c5e6cbba45fe50785a15d3beb1da0                         |                                                              |
| isAllowed         | VARCHAR   | true                                                               |                                                              |

## 12. Table: LSSVMPairFactory\_event\_CallTargetStatusUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-23 00:41:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15592534                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd1055d5b7ef24edec278b6b17d779f1c2eb0c815227d03cd442987f615bec934 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| target            | VARCHAR   | 0x9c8ff314c9bc7f6e59a9d9225fb22946427edc03                         |                                                              |
| isAllowed         | VARCHAR   | true                                                               |                                                              |

## 13. Table: LSSVMPairFactory\_event\_NFTDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-28 12:03:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16726534                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94f6f4d5e1f1ef11051094b9173b3176e5dc62a45edb48b5e994847a24089c76 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| poolAddress       | VARCHAR   | 0x3f99a88b6f95cb0573b54c0ec863709a5623a022                         |                                                              |

## 14. Table: LSSVMPairFactory\_event\_NewPair\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-16 02:13:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16638239                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0eb7026e33cfc55db507ff7874fc39a237a51cdd41b103091419f53de97454f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| poolAddress       | VARCHAR   | 0xdea980bf7daa576e80101616b4c747eb71b175ac                         |                                                              |

## 15. Table: LSSVMPairFactory\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-24 06:13:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14645816                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e580c8682e17a49d8bf0d0f97420186d4317a5497ee36d34b6443ddffbde531 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x75d4bdbf6593ed463e9625694272a0ff9a6d346f                         |                                                              |

## 16. Table: LSSVMPairFactory\_event\_ProtocolFeeMultiplierUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-27 06:00:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14664773                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb27739b3c9ec7acc2212065537fc68de8200b82f2c23315d296889d62f34b263 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 92                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| newMultiplier     | VARCHAR   | 5000000000000000                                                   |                                                              |

## 17. Table: LSSVMPairFactory\_event\_ProtocolFeeRecipientUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 21:34:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16522361                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4ffd1a14352468382cf4da6e8d9c16b8b80b7c95af07c90391afdb890136c82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| recipientAddress  | VARCHAR   | 0x6853f8865ba8e9fbd9c8cce3155ce5023fb7eeb0                         |                                                              |

## 18. Table: LSSVMPairFactory\_event\_RouterStatusUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-24 22:24:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14650107                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe51b51c470b1b0b0a7d89d2933ae11326248e2daeded8b501715e23c62ca9fc7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| router            | VARCHAR   | 0xe5763f17cf9668328938b61e282855c04ffb50a4                         |                                                              |
| isAllowed         | VARCHAR   | true                                                               |                                                              |

## 19. Table: LSSVMPairFactory\_event\_TokenDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 23:24:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15720965                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02d321b44b3bc2a49585a03ba68805fbf23b85182bd7855efbb83cfb6353d777 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb16c1342e617a5b6e4b631eb114483fdb289c0a4                         | Address of the contract that produced the log                |
| poolAddress       | VARCHAR   | 0xbaa2c91de65fffaa6bf943a740345273f7c51e4f                         |                                                              |

## 20. Table: LSSVMPairV2ERC1155ERC20\_call\_swapNFTsForToken\_history

| Column                 | Type      | Example                                                            | Description                                                                                                            |
| ---------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp       | TIMESTAMP | 2023-06-23 22:24:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number          | INTEGER   | 17545217                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash      | VARCHAR   | 0xb56c403f5c2bbcc4432d7d7cc28cd27ba3a035d0cb9f9af7e73e07bb1da9a190 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index     | INTEGER   | 121                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address         | VARCHAR   | 0,0,0,4                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address            | VARCHAR   | 0x27120a3afece964221749c2e1f7ac45e2119ef88                         | Address of the called contract                                                                                         |
| status                 | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                  | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs                | VARCHAR   | 1                                                                  |                                                                                                                        |
| minExpectedTokenOutput | VARCHAR   | 23405188743160667                                                  |                                                                                                                        |
| tokenRecipient         | VARCHAR   | 0xe2840826c43c25e88a5ef43ff790d7105889dd6e                         |                                                                                                                        |
| isRouter               | VARCHAR   | false                                                              |                                                                                                                        |
| routerCaller           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                                                                                        |

## 21. Table: LSSVMPairV2ERC1155ERC20\_call\_swapTokenForSpecificNFTs\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-08-03 03:56:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 17831932                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0x28e120c2d0151525d53a3cdb328752fc8fcf39fbfc5ae66b32c5c22ee56f6799 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 16                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x8487e11ff55896f3407ad5a666a50622f99d2e49                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs               | VARCHAR   | 1                                                                  |                                                                                                                        |
| maxExpectedTokenInput | VARCHAR   | 10970873786407766                                                  |                                                                                                                        |
| nftRecipient          | VARCHAR   | 0xafa8387d7083c58b95ba99d06db9cdca9d8098e4                         |                                                                                                                        |
| isRouter              | VARCHAR   | false                                                              |                                                                                                                        |
| routerCaller          | VARCHAR   | 0xafa8387d7083c58b95ba99d06db9cdca9d8098e4                         |                                                                                                                        |

## 22. Table: LSSVMPairV2ERC1155ETH\_call\_swapNFTsForToken\_history

| Column                 | Type      | Example                                                            | Description                                                                                                            |
| ---------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp       | TIMESTAMP | 2023-07-09 13:36:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number          | INTEGER   | 17656487                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash      | VARCHAR   | 0x4092bbe2b1d6166272ad1e08bb86bea342abe71a4c82312b99d1a8644c5b10a1 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index     | INTEGER   | 78                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address         | VARCHAR   | 0,0,0,4                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address            | VARCHAR   | 0x27120a3afece964221749c2e1f7ac45e2119ef88                         | Address of the called contract                                                                                         |
| status                 | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                  | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs                | VARCHAR   | 1                                                                  |                                                                                                                        |
| minExpectedTokenOutput | VARCHAR   | 23405188743160667                                                  |                                                                                                                        |
| tokenRecipient         | VARCHAR   | 0xe2840826c43c25e88a5ef43ff790d7105889dd6e                         |                                                                                                                        |
| isRouter               | VARCHAR   | false                                                              |                                                                                                                        |
| routerCaller           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                                                                                        |

## 23. Table: LSSVMPairV2ERC1155ETH\_call\_swapTokenForSpecificNFTs\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-06-01 21:24:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 17388601                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0xaa0af959a7d20cb416c7bd6a778b593ce9c21dab8d6e6d91cae8ea5de1a7e344 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 41                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x0596dbdd20bba341c5fb5f8b54c777d3a8a0d91f                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs               | VARCHAR   | 1                                                                  |                                                                                                                        |
| maxExpectedTokenInput | VARCHAR   | 13194029850746270                                                  |                                                                                                                        |
| nftRecipient          | VARCHAR   | 0x4206957609f2936d166af8e5d0870a11496302ad                         |                                                                                                                        |
| isRouter              | VARCHAR   | false                                                              |                                                                                                                        |
| routerCaller          | VARCHAR   | 0x4206957609f2936d166af8e5d0870a11496302ad                         |                                                                                                                        |

## 24. Table: LSSVMPairV2ERC1155ETH\_swapNFTsForToken\_history

| Column                 | Type      | Example                                                            | Description                                                                                                            |
| ---------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp       | TIMESTAMP | 2023-06-12 19:18:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number          | INTEGER   | 17465996                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash      | VARCHAR   | 0xf73e980264728d8a34af8360605408689ea035300805092f6ea74d5ccc8735df | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index     | INTEGER   | 83                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address         | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address            | VARCHAR   | 0x27120a3afece964221749c2e1f7ac45e2119ef88                         | Address of the called contract                                                                                         |
| status                 | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                  | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs                | VARCHAR   | 1                                                                  |                                                                                                                        |
| minExpectedTokenOutput | VARCHAR   | 0                                                                  |                                                                                                                        |
| tokenRecipient         | VARCHAR   | 0x18252f28234c010cf3353a82f3cbe71db1b74773                         |                                                                                                                        |
| isRouter               | VARCHAR   | false                                                              |                                                                                                                        |
| routerCaller           | VARCHAR   | 0x18252f28234c010cf3353a82f3cbe71db1b74773                         |                                                                                                                        |

## 25. Table: LSSVMPairV2ERC1155ETH\_swapTokenForSpecificNFTs\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-06-02 21:06:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 17395598                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0x3a16ffdc58f98cb02b7deacd74beffc2c2e2919a7ae5a2b18d9af2ec9aa40e98 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 38                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x255eed18e06a9048f687face64de5e232924a32a                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs               | VARCHAR   | 1                                                                  |                                                                                                                        |
| maxExpectedTokenInput | VARCHAR   | 9951456310679610                                                   |                                                                                                                        |
| nftRecipient          | VARCHAR   | 0x4206957609f2936d166af8e5d0870a11496302ad                         |                                                                                                                        |
| isRouter              | VARCHAR   | false                                                              |                                                                                                                        |
| routerCaller          | VARCHAR   | 0x4206957609f2936d166af8e5d0870a11496302ad                         |                                                                                                                        |

## 26. Table: LSSVMPairV2ERC721ERC20\_call\_swapNFTsForToken\_history

| Column                 | Type      | Example                                                            | Description                                                                                                            |
| ---------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp       | TIMESTAMP | 2023-06-28 21:40:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number          | INTEGER   | 17580557                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash      | VARCHAR   | 0x700a41fcb48cc165234ac0a6d887a657fc312e9e58d3f989b83beb46a2b92d67 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index     | INTEGER   | 29                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address         | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address            | VARCHAR   | 0x538f997819a8f2144f262c24d7a18640ad1f1aac                         | Address of the called contract                                                                                         |
| status                 | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                  | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| nftIds                 | VARCHAR   | 3796                                                               |                                                                                                                        |
| minExpectedTokenOutput | VARCHAR   | 43838349514563103                                                  |                                                                                                                        |
| tokenRecipient         | VARCHAR   | 0x98ccf605c43a0bf9d6795c3cf3b5fed836330511                         |                                                                                                                        |
| isRouter               | VARCHAR   | true                                                               |                                                                                                                        |
| routerCaller           | VARCHAR   | 0x98ccf605c43a0bf9d6795c3cf3b5fed836330511                         |                                                                                                                        |

## 27. Table: LSSVMPairV2ERC721ERC20\_call\_swapTokenForSpecificNFTs\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-07-24 18:01:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 17764615                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0x7c01efc6f1362db9ad4fdf50055cd5e14053f03a97a43e2ae98be3ac3bb12896 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 7                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | 0,2                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0xcdb8f114d2fb28a4b85bb1ab6e09444006ef5385                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| nftIds                | VARCHAR   | 4275,8392,938                                                      |                                                                                                                        |
| maxExpectedTokenInput | VARCHAR   | 2135814787842222169                                                |                                                                                                                        |
| nftRecipient          | VARCHAR   | 0x50a269ff3238db9c60ac2205cf5268e009753de8                         |                                                                                                                        |
| isRouter              | VARCHAR   | true                                                               |                                                                                                                        |
| routerCaller          | VARCHAR   | 0x50a269ff3238db9c60ac2205cf5268e009753de8                         |                                                                                                                        |

## 28. Table: LSSVMPairV2ERC721ETH\_call\_swapNFTsForToken\_history

| Column                 | Type      | Example                                                            | Description                                                                                                            |
| ---------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp       | TIMESTAMP | 2023-07-23 20:38:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number          | INTEGER   | 17758249                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash      | VARCHAR   | 0xc8943e74015a53685595c52c277525384cf90cbc4183ba0f42a0bd9838146426 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index     | INTEGER   | 34                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address         | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address            | VARCHAR   | 0x7722b10101f8015bc29895952fedb16bbb9f7be6                         | Address of the called contract                                                                                         |
| status                 | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                  | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| nftIds                 | VARCHAR   | 3350                                                               |                                                                                                                        |
| minExpectedTokenOutput | VARCHAR   | 49994700000000000                                                  |                                                                                                                        |
| tokenRecipient         | VARCHAR   | 0x012cb3b8d0fca08eb003bb887fd2ae33e06b63bc                         |                                                                                                                        |
| isRouter               | VARCHAR   | true                                                               |                                                                                                                        |
| routerCaller           | VARCHAR   | 0x012cb3b8d0fca08eb003bb887fd2ae33e06b63bc                         |                                                                                                                        |

## 29. Table: LSSVMPairV2ERC721ETH\_call\_swapTokenForSpecificNFTs\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-07-08 04:19:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 17646632                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0xe73073144d01c625edf92522619e71138174566322890aa7a3b4515feccdd53c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 17                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0xcdb8f114d2fb28a4b85bb1ab6e09444006ef5385                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| nftIds                | VARCHAR   | 5743                                                               |                                                                                                                        |
| maxExpectedTokenInput | VARCHAR   | 575999999999999840                                                 |                                                                                                                        |
| nftRecipient          | VARCHAR   | 0xb029ac97043523a6a08b05e125b4f923ed83946e                         |                                                                                                                        |
| isRouter              | VARCHAR   | false                                                              |                                                                                                                        |
| routerCaller          | VARCHAR   | 0xb029ac97043523a6a08b05e125b4f923ed83946e                         |                                                                                                                        |

## 30. Table: LSSVMPair\_call\_assetRecipient\_history

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

## 31. Table: LSSVMPair\_call\_bondingCurve\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-06 05:02:07+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15482103                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb9486e19be8f7bf878008de245698f0c17e2dc0a95ad42475716eb9d6e8064f8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 68                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,3                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xbaaa90fa64a292edcd401dd496e62de5f787bbe8                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 32. Table: LSSVMPair\_call\_call\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-20 21:09:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16871469                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7b3960bb71e33fb8effca925c32f188627ad1ac020bf7925105730c2a12d95c8                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 9                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd32788128d79027b59f89ef06461fa601a66b988                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| target             | VARCHAR   | 0x888888888888660f286a7c06cfa3407d09af44b2                                                           |                                                                                                                        |
| data               | VARCHAR   | 0xa9059cbb000000000000000000000000888888888888660f286a7c06cfa3407d09af44b200000000000000000000000000 |                                                                                                                        |

## 33. Table: LSSVMPair\_call\_changeAssetRecipient\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-03 11:05:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16103875                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x93f96347ab61cabac5b4ca0e19d9eda59355b4dd2d26d194b71793f03c8ea390 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 6                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x09eac0c2d06ed773b1740232e00b9ef5f56e25d3                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newRecipient       | VARCHAR   | 0xa3347ebf96d49084519f510401e679fabf90931b                         |                                                                                                                        |

## 34. Table: LSSVMPair\_call\_changeDelta\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-09 10:05:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17222189                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x805dc83e6f76bf5ce058f25874be9a1fa8052c7c09bae04058c8ca0ca9bb3a5c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 132                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,1                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x63ec9e2a624342398f74a67049351fa08854aa75                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newDelta           | VARCHAR   | 1045000000000000000                                                |                                                                                                                        |

## 35. Table: LSSVMPair\_call\_changeFee\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-12 17:11:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17245531                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x55b45f2b680d3c65c8fea8ebb254c0e34bb64317d821b88ef48d49fbc16fa76a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 25                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0cd63e260554a6f1ed014d89a93e0593553c554d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newFee             | VARCHAR   | 100000000000000000                                                 |                                                                                                                        |

## 36. Table: LSSVMPair\_call\_changeSpotPrice\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-11 00:01:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17233422                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5d2a63ce866967a150f12b28801465c5743fe4de33eafe1b76bc51c26b7ff529 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 59                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd1fae9575aeae06cf9bbd11d99c7a9f111886028                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newSpotPrice       | VARCHAR   | 1498762813715094100                                                |                                                                                                                        |

## 37. Table: LSSVMPair\_call\_delta\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-12 23:46:25+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15523748                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x58e40255cc9be4f0e8415b06e5e4383fc0eb35ef01d2591833f76f80f451d916 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 60                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3bc0c18cfa3846a007457909286d388b851219b2                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 38. Table: LSSVMPair\_call\_factory\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-29 09:46:18+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15433406                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xcebb1d79ef90ffc981a77f4fa8e46f5dad8f74509308be6bbd7dd4b8ec2ed681 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 57                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7b20962a25b72d1468fdcf0ab34d933841841dd2                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 39. Table: LSSVMPair\_call\_fee\_history

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

## 40. Table: LSSVMPair\_call\_getAllHeldIds\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-06 05:02:07+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15482103                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb9486e19be8f7bf878008de245698f0c17e2dc0a95ad42475716eb9d6e8064f8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 68                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,4                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xbaaa90fa64a292edcd401dd496e62de5f787bbe8                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 41. Table: LSSVMPair\_call\_getAssetRecipient\_history

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

## 42. Table: LSSVMPair\_call\_getBuyNFTQuote\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-01 10:57:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17385511                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2ce4b15e0e1d84a1b48ed7547f9e11eed8a1582b9beea715767b00f343f33be1 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,0,1,1,0                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5caf332dca4e6c9e69d52f320c21e74845353db0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs            | VARCHAR   | 1                                                                  |                                                                                                                        |

## 43. Table: LSSVMPair\_call\_getSellNFTQuote\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-23 03:14:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17539542                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc520ebc994b2ce6910bfa681549cde555b49f4e96ef7ab5e3797a9d4e77dabd5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 2                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xff833c79c6d8f8e4234f474f6ddc71e0aa72b312                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs            | VARCHAR   | 12                                                                 |                                                                                                                        |

## 44. Table: LSSVMPair\_call\_initialize\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-22 12:15:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17748605                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xac5cbbad36218536fa5bf18ab08baf119c152bb9569e86137c34be84c573faeb | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 107                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x04330f63777434027366444e508a03fe6ea06901                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_owner            | VARCHAR   | 0x67745f0ef5f262f9f2599c82383aa48398645624                         |                                                                                                                        |
| \_assetRecipient   | VARCHAR   | 0x67745f0ef5f262f9f2599c82383aa48398645624                         |                                                                                                                        |
| \_delta            | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_fee              | VARCHAR   | 0                                                                  |                                                                                                                        |
| \_spotPrice        | VARCHAR   | 99502487562189                                                     |                                                                                                                        |

## 45. Table: LSSVMPair\_call\_multicall\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-11 02:46:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17234237                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x82db57ed04f2ceebf0a90ed0f234468d5b3e1e8a73626f7d34bd4f23998b3cd7                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 30                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0c07eb22fa0251da28af669b7db23c05ab6140a6                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| calls              | VARCHAR   | 0xd8a1890c00000000000000000000000000000000000000000000000002829fdaf4f5b43e,0x6809f664000000000000000 |                                                                                                                        |
| revertOnFail       | VARCHAR   | true                                                                                                 |                                                                                                                        |

## 46. Table: LSSVMPair\_call\_nft\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-20 07:19:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17299113                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x93b87d3a8e62a34663501655dcc32e5a19313228e9f074932553601e9f78bb33 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 69                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,0                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7888fa7d738c4d3f8eb8de0150b6352f195f0167                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 47. Table: LSSVMPair\_call\_owner\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-31 13:56:09+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15446988                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5fc57f3689d795225a7877e5855a4163b91b269e60928b301b3563d2a6e1290d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 66                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 8                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x8dc7b1fe02cfe0d6b7c85b90ecf6a2a1aafb24b2                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 48. Table: LSSVMPair\_call\_pairVariant\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-22 12:12:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15588803                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x57239fc39a62f0c07ae0c77a46d4235a03acc8bec073dc3b7dab3df99619ca73 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 183                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7eec5ae05bc5067c9f74d8d30725cf806084d761                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 49. Table: LSSVMPair\_call\_poolType\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-21 15:01:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15582505                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x36263dd3ece0ba3136f625f3bdd186fd971f561769d49e6d10c5f18d77da9651 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 199                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,5,0,0,0                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x6f493944e494ba555ee2708a3220bd3756ad04d9                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 50. Table: LSSVMPair\_call\_spotPrice\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-16 20:59:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15548705                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xe5673b70152a2121c6992d5899161a4ed5e74a7e758abbca0cd300b620821ad1 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 26                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x562612e8d3a03b488ee2b58f058e757670aca144                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 51. Table: LSSVMPair\_call\_supportsInterface\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-15 22:22:21+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15348609                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x6b807ad32b009804cd7f866a8881c762a0e293b3e61837d995de94499258bdcb | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 190                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x12a0b78a305c988dceca9f1dfb196712b79336cc                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| interfaceId        | VARCHAR   | 0x780e9d63                                                         |                                                                                                                        |

## 52. Table: LSSVMPair\_call\_swapNFTsForToken\_history

| Column                 | Type      | Example                                                            | Description                                                                                                            |
| ---------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp       | TIMESTAMP | 2022-11-07 15:12:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number          | INTEGER   | 15918963                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash      | VARCHAR   | 0x0b988973cbd5a071de268a7ffe89f5c0babd797b8ad77a8a6883ce994bc97e27 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index     | INTEGER   | 33                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address         | VARCHAR   | 3                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address            | VARCHAR   | 0x0282fbdbd83c014c2d689a07b2b229c184950e37                         | Address of the called contract                                                                                         |
| status                 | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                  | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| nftIds                 | VARCHAR   | 1471                                                               |                                                                                                                        |
| minExpectedTokenOutput | VARCHAR   | 0                                                                  |                                                                                                                        |
| tokenRecipient         | VARCHAR   | 0xbf6aba7ab14d98734d67ce05566cd91237deaa72                         |                                                                                                                        |
| isRouter               | VARCHAR   | false                                                              |                                                                                                                        |
| routerCaller           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                                                                                        |

## 53. Table: LSSVMPair\_call\_swapTokenForAnyNFTs\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2022-09-01 06:31:22+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 15451312                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0x0ecad6d1aa728b58d2dffb5ec0b93c1547ec9f7b69c5a2141d890853d4eb13ec | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 41                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x8e073f147dd03309429f194a36299d8d7a866806                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| numNFTs               | VARCHAR   | 2                                                                  |                                                                                                                        |
| maxExpectedTokenInput | VARCHAR   | 5621800244411185                                                   |                                                                                                                        |
| nftRecipient          | VARCHAR   | 0xaf5fa8aa38de4cd35c063022c411f97d7520e0c9                         |                                                                                                                        |
| isRouter              | VARCHAR   | true                                                               |                                                                                                                        |
| routerCaller          | VARCHAR   | 0xaf5fa8aa38de4cd35c063022c411f97d7520e0c9                         |                                                                                                                        |

## 54. Table: LSSVMPair\_call\_swapTokenForSpecificNFTs\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-03-23 14:31:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 16890843                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0xb3b61a798d11be5e686013b57dd42e6a3dc8c39351feab8bc06dd631c33dd219 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 42                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | 2,0,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x56f5fc7ac3649a2c2af70299d64dbd1944df97f7                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| nftIds                | VARCHAR   | 11449                                                              |                                                                                                                        |
| maxExpectedTokenInput | VARCHAR   | 62602991513712301                                                  |                                                                                                                        |
| nftRecipient          | VARCHAR   | 0xae21cfd26ed65dc2e5c2b80b891912d31af83b00                         |                                                                                                                        |
| isRouter              | VARCHAR   | true                                                               |                                                                                                                        |
| routerCaller          | VARCHAR   | 0x04898894a0b6c094a920eafd180ef4ac30f00a43                         |                                                                                                                        |

## 55. Table: LSSVMPair\_call\_transferOwnership\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-24 00:57:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17325637                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1ceac7451100c7818bfa263054a5bf7458ab3ccb01dea55b6738a7dd07d0d47e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 42                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe283ce6f85f74261d8964f791f30dacbfbe93ea9                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newOwner           | VARCHAR   | 0x3bfc3134645ebe0393f90d6a19bcb20bd732964f                         |                                                                                                                        |

## 56. Table: LSSVMPair\_call\_withdrawAllETH\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-07 05:17:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17860919                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9a0dd982734d763e4d4daf5589ae5851be666647ba9fcb33757428c689bc71b8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 92                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x43d1262197ae2d0a6a968343c4478b662c3cdfe3                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 57. Table: LSSVMPair\_call\_withdrawERC1155\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-03 00:07:10+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15462192                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8d9bf4c99dba068a1012de15389b2d61fff751c98cc915f7ede5efdbcb727cb4 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 26                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x520cebd6e7e47550d0d109ecda345b6b13d35324                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| a                  | VARCHAR   | 0xedc227ad7fef4a2c6dbc2303a5732087314a4ce9                         |                                                                                                                        |
| ids                | VARCHAR   | 4                                                                  |                                                                                                                        |
| amounts            | VARCHAR   | 1                                                                  |                                                                                                                        |

## 58. Table: LSSVMPair\_call\_withdrawERC20\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-23 09:04:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17541261                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2e9030b810c6f978c00ad83d9f1ca5f4c470c44ac23773d16b08cf3b512537a8 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 81                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,3                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xe283ce6f85f74261d8964f791f30dacbfbe93ea9                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| a                  | VARCHAR   | 0xddc6625feca10438857dd8660c021cd1088806fb                         |                                                                                                                        |
| amount             | VARCHAR   | 761548057982496111641                                              |                                                                                                                        |

## 59. Table: LSSVMPair\_call\_withdrawERC721\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-31 06:28:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16525018                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x4638a819b1d70813dd90b74c7132c9e4e11f46f3cb8db6af4eca7fbcb3730da2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 130                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc017d1331106b1204de2752751e7484f2ab9d45a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| a                  | VARCHAR   | 0x22d4c35a4f2b229a928b1b569b2f60225976426a                         |                                                                                                                        |
| nftIds             | VARCHAR   | 4223                                                               |                                                                                                                        |

## 60. Table: LSSVMPair\_call\_withdrawETH\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-29 06:46:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17583261                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5d5b832f8254b33058490f7e13159a7364e472f104d415fba1d091a0d8f2b526 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 68                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5953049c8aee9df7575f5d9ca496b31b28ec7ff5                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 5000000000000000                                                   |                                                                                                                        |

## 61. Table: LSSVMPair\_event\_AssetRecipientChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-26 19:29:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15417179                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0854aa14070a2f4d0d3cd7ba664ff98d5a1fe56c926306d58f4605a072bbd5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7653e23230517a145078feff8abd5463e18922e4                         | Address of the contract that produced the log                |
| a                 | VARCHAR   | 0x7653e23230517a145078feff8abd5463e18922e4                         |                                                              |

## 62. Table: LSSVMPair\_event\_DeltaUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-06 01:21:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17418119                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32612fd36d4793599b7685076db50a1239021f4ae63b7946e48f8ae9f51ac2fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 275                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0cd63e260554a6f1ed014d89a93e0593553c554d                         | Address of the contract that produced the log                |
| newDelta          | VARCHAR   | 1100000000000000000                                                |                                                              |

## 63. Table: LSSVMPair\_event\_FeeUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-29 14:09:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17585458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3422955eb870773d7a175f83cd3200ba5bdc547d7da7ebdda3c480b38f2ae4eb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xce561e404cbf2b5635da5ac87bf1bcd63dbc9c3e                         | Address of the contract that produced the log                |
| newFee            | VARCHAR   | 15000000000000000                                                  |                                                              |

## 64. Table: LSSVMPair\_event\_NFTWithdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 01:51:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17382816                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb25fa2cc4adc431704c7515e15ee3bb7d7bbaf8e5305748a3435ad73d3887ddc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x72d91be2f8e32f87ab48961f75a7fbf7a8c62293                         | Address of the contract that produced the log                |

## 65. Table: LSSVMPair\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 17:40:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17394583                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe8a65247a5b9a87068b71aeebf2f697fb8b81cf7de1c062ff705c0efc33cde73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x831c78a9afc0419cf9562e6246b50807cc87423c                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0x98e1c4e34ccded4760ef8da63bcccdf4a75b3c4b                         |                                                              |

## 66. Table: LSSVMPair\_event\_SpotPriceUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-08 14:12:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15925836                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9565e07d110de5e5d08faa16aa41d8a4bfba410fbf08aaae418594da21b441a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 249                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0436be3103584addb6e05cfa138330973e43c35a                         | Address of the contract that produced the log                |
| newSpotPrice      | VARCHAR   | 59726368159203990                                                  |                                                              |

## 67. Table: LSSVMPair\_event\_SwapNFTInPair\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 17:35:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17664776                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa3fbb6006d602b97d6117a667c9a4a48f7f2227c553ac9ae3c95531d43eadbc7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 281                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x226271f15b8d6649bc4a776e6530110de5c24b2c                         | Address of the contract that produced the log                |

## 68. Table: LSSVMPair\_event\_SwapNFTOutPair\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 00:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17028531                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70e1f49c5e0f1bc3ca417e9af1d2b890ac4ca002c998659cd970d64cca4712e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x068194ec0595cd4a7dc4e717ab482e38aead650b                         | Address of the contract that produced the log                |

## 69. Table: LSSVMPair\_event\_TokenDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 10:17:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17470425                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba397e3242b4f09384ce71b250d165498846220d050a86fad9fea9a2c2ec00a9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf87a4c3013e78aa66e45f6b6c684ecb683558fdf                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 70. Table: LSSVMPair\_event\_TokenWithdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 23:32:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15323605                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x33836e93fe3b5e6b5af65ef94a492ace2fe2d053926093e275177f1e3c4bcd38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x031d2229f18ed6f2663711e6f47eed923c957827                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 300000000000000000                                                 |                                                              |

## 71. Table: LSSVMRouter\_call\_pairTransferERC20From\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-11 22:37:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17673382                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x39b7979e79278a0d3aa745316509fcceeb79f2fe0ae80d6c612f141740321542 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 92                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,4                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| token              | VARCHAR   | 0x600000000a36f3cd48407e35eb7c5c910dc1f7a8                         |                                                                                                                        |
| from               | VARCHAR   | 0xf2458bd228d8a39b64bd3b9f84890e957cac3bbc                         |                                                                                                                        |
| to                 | VARCHAR   | 0x472b327a303cb2d4ce47386fdc0a3eaab93fda13                         |                                                                                                                        |
| amount             | VARCHAR   | 68656716417910460000                                               |                                                                                                                        |
| variant            | VARCHAR   | 3                                                                  |                                                                                                                        |

## 72. Table: LSSVMRouter\_call\_pairTransferNFTFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-09 15:01:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17011486                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xabd5c772bc84105e0dd33f3253b598f7b50a459a0b0f83189cc1afe70636202c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 314                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,0,5                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| nft                | VARCHAR   | 0x558bfff0d583416f7c4e380625c7865821b8e95c                         |                                                                                                                        |
| from               | VARCHAR   | 0x892ff98a46e5bd141e2d12618f4b2fe6284debac                         |                                                                                                                        |
| to                 | VARCHAR   | 0xfc0c6b36c2ce96511223fc0254abe4e107b7b3d4                         |                                                                                                                        |
| id                 | VARCHAR   | 3186                                                               |                                                                                                                        |
| variant            | VARCHAR   | 0                                                                  |                                                                                                                        |

## 73. Table: LSSVMRouter\_call\_robustSwapERC20ForAnyNFTs\_history

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
| swapList           | VARCHAR   |                                                                                                                        |             |
| inputAmount        | VARCHAR   |                                                                                                                        |             |
| nftRecipient       | VARCHAR   |                                                                                                                        |             |
| deadline           | VARCHAR   |                                                                                                                        |             |

## 74. Table: LSSVMRouter\_call\_robustSwapERC20ForSpecificNFTsAndNFTsToToken\_history

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
| params             | VARCHAR   |                                                                                                                        |             |

## 75. Table: LSSVMRouter\_call\_robustSwapERC20ForSpecificNFTs\_history

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
| swapList           | VARCHAR   |                                                                                                                        |             |
| inputAmount        | VARCHAR   |                                                                                                                        |             |
| nftRecipient       | VARCHAR   |                                                                                                                        |             |
| deadline           | VARCHAR   |                                                                                                                        |             |

## 76. Table: LSSVMRouter\_call\_robustSwapETHForAnyNFTs\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-30 23:13:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16086003                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc5c43c55e5a682fe354fcb69c8bafb3c2f9ed57d044b6632ef88ff59f7fed733 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 155                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| swapList           | VARCHAR   | 0xcF5c0B18846aCbAB016A4F0D9BadB96d9DA1c77E,1,1000000000000001      |                                                                                                                        |
| ethRecipient       | VARCHAR   | 0xaf5fa8aa38de4cd35c063022c411f97d7520e0c9                         |                                                                                                                        |
| nftRecipient       | VARCHAR   | 0xaf5fa8aa38de4cd35c063022c411f97d7520e0c9                         |                                                                                                                        |
| deadline           | VARCHAR   | 1669850065                                                         |                                                                                                                        |

## 77. Table: LSSVMRouter\_call\_robustSwapETHForSpecificNFTsAndNFTsToToken\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-12 23:42:47+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17247286                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5acdff2ae40f789306b72847225d1b9affba459e6e2bda36675915a2c7633134                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 95                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| params             | VARCHAR   | ,0x319aA0C0b9ac8286eE0a76AA3d9EC1ef524E776D,9270,235407692884963114,0,0xD543A0BE0684f0556786586b83f4 |                                                                                                                        |

## 78. Table: LSSVMRouter\_call\_robustSwapETHForSpecificNFTs\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-01 14:03:03+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15257094                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x65dee260749f6cbbab6bde17a310803a5a35d595d3a63cbfc45823f9fc0e4700                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 183                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swapList           | VARCHAR   | 0xD2a6D0280ff48CcBCD654d5D0Ecc45eF1e1cDBc3,4673,3530,515524500000000032,0xfe754F4cDF4A9985683a4637C6 |                                                                                                                        |
| ethRecipient       | VARCHAR   | 0x00003183f59e825911d98fb509a157cd2abbae25                                                           |                                                                                                                        |
| nftRecipient       | VARCHAR   | 0x00003183f59e825911d98fb509a157cd2abbae25                                                           |                                                                                                                        |
| deadline           | VARCHAR   | 1659366188                                                                                           |                                                                                                                        |

## 79. Table: LSSVMRouter\_call\_robustSwapNFTsForToken\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-18 14:15:59+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15560964                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x440a773345377d06c756ff26dd7971335cc1f5ff6d97c44801929f0de92927b3                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| swapList           | VARCHAR   | 0x63a85521E43F33880962bAfD0aafAC8fD6bCf304,7552,7551,7544,7575,7578,1103165377410735765,0x1da93091d3 |                                                                                                                        |
| tokenRecipient     | VARCHAR   | 0xf3b8e94d8efa79134725e8bb982aeb85391bb456                                                           |                                                                                                                        |
| deadline           | VARCHAR   | 1663514112                                                                                           |                                                                                                                        |

## 80. Table: LSSVMRouter\_call\_swapERC20ForAnyNFTs\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-09-13 07:13:58+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15525625                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc5531fa64ce1e5c609489e734325835471215ad5f8e0972c94b64d12242d97e4 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 39                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| swapList           | VARCHAR   | 0xa3A3358240E5C321a1f4DeaaB9bFA98ff4E3e71C,1                       |                                                                                                                        |
| inputAmount        | VARCHAR   | 60831437150000000000000000                                         |                                                                                                                        |
| nftRecipient       | VARCHAR   | 0x21c025a4e5b47be192b1ccecc3c6fe4128ce94a6                         |                                                                                                                        |
| deadline           | VARCHAR   | 1663056822                                                         |                                                                                                                        |

## 81. Table: LSSVMRouter\_call\_swapERC20ForSpecificNFTs\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-24 09:14:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17328091                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x07e21971e7562f1954f8ba04f4981050ca7e055c7d2ce78de93b19c0aa1a5b4d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 44                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| swapList           | VARCHAR   | 0xE283CE6F85f74261d8964f791F30daCBFBE93ea9,1680                    |                                                                                                                        |
| inputAmount        | VARCHAR   | 132290352867743563460                                              |                                                                                                                        |
| nftRecipient       | VARCHAR   | 0x1b319e3f01805ff2c54234868732f90d3c20e67d                         |                                                                                                                        |
| deadline           | VARCHAR   | 1684923274                                                         |                                                                                                                        |

## 82. Table: LSSVMRouter\_call\_swapETHForAnyNFTs\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-17 03:31:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16645781                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8ff5ed4670259c7b72e440f31ce87fb6401e4a9a226991b7ebc34f8a2b7ae2fd | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 50                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| swapList           | VARCHAR   | 0xD51037FB333241f2D5b18D02e3668cb14Fbf29F8,1                       |                                                                                                                        |
| ethRecipient       | VARCHAR   | 0xb7957fe76c2feae66b57cf3191afd26d99ec5599                         |                                                                                                                        |
| nftRecipient       | VARCHAR   | 0x0c9133fa96d72c2030d63b6b35c3738d6329a313                         |                                                                                                                        |
| deadline           | VARCHAR   | 1676604695                                                         |                                                                                                                        |

## 83. Table: LSSVMRouter\_call\_swapETHForSpecificNFTs\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-21 19:06:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17743494                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x41325e74b1bdef321188ba1310298da605386de7f9461cfc65510fdd9a087352 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 56                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| swapList           | VARCHAR   | 0x451018623F2EA29A625Ac5e051720eEAc2b0E765,1800                    |                                                                                                                        |
| ethRecipient       | VARCHAR   | 0xa97727370e2592f83602bc92975c49c4fea4491f                         |                                                                                                                        |
| nftRecipient       | VARCHAR   | 0x08d2c744fd60f2dca8c1885d3aa03ff6d3fa5d11                         |                                                                                                                        |
| deadline           | VARCHAR   | 1689966969                                                         |                                                                                                                        |

## 84. Table: LSSVMRouter\_call\_swapNFTsForAnyNFTsThroughERC20\_history

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
| trade              | VARCHAR   |                                                                                                                        |             |
| inputAmount        | VARCHAR   |                                                                                                                        |             |
| minOutput          | VARCHAR   |                                                                                                                        |             |
| nftRecipient       | VARCHAR   |                                                                                                                        |             |
| deadline           | VARCHAR   |                                                                                                                        |             |

## 85. Table: LSSVMRouter\_call\_swapNFTsForAnyNFTsThroughETH\_history

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
| trade              | VARCHAR   |                                                                                                                        |             |
| minOutput          | VARCHAR   |                                                                                                                        |             |
| ethRecipient       | VARCHAR   |                                                                                                                        |             |
| nftRecipient       | VARCHAR   |                                                                                                                        |             |
| deadline           | VARCHAR   |                                                                                                                        |             |

## 86. Table: LSSVMRouter\_call\_swapNFTsForSpecificNFTsThroughERC20\_history

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
| trade              | VARCHAR   |                                                                                                                        |             |
| inputAmount        | VARCHAR   |                                                                                                                        |             |
| minOutput          | VARCHAR   |                                                                                                                        |             |
| nftRecipient       | VARCHAR   |                                                                                                                        |             |
| deadline           | VARCHAR   |                                                                                                                        |             |

## 87. Table: LSSVMRouter\_call\_swapNFTsForSpecificNFTsThroughETH\_history

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
| trade              | VARCHAR   |                                                                                                                        |             |
| minOutput          | VARCHAR   |                                                                                                                        |             |
| ethRecipient       | VARCHAR   |                                                                                                                        |             |
| nftRecipient       | VARCHAR   |                                                                                                                        |             |
| deadline           | VARCHAR   |                                                                                                                        |             |

## 88. Table: LSSVMRouter\_call\_swapNFTsForToken\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-17 15:08:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16649216                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb0867307115c035f45ae10744ce0a9cf78cb19ee494598ddafbbe866dde18c34 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 5                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2b2e8cda09bba9660dca5cb6233787738ad68329                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| swapList           | VARCHAR   | 0x03397b4E2E984c695b254ba0b7Ca87865FED3ab7,398                     |                                                                                                                        |
| minOutput          | VARCHAR   | 1                                                                  |                                                                                                                        |
| tokenRecipient     | VARCHAR   | 0x0000008682fa8c3aa14b11894e90e3dcbbff715b                         |                                                                                                                        |
| deadline           | VARCHAR   | 1676646606                                                         |                                                                                                                        |

## 89. Table: LinearCurve\_call\_getBuyInfo\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-02-15 15:57:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 16635180                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0x266999070d6a71c1f5db880b5ce14158d544b12c2273452e03695e376366a215 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 139                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | 0,1,0,0,1                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x5b6ac51d9b1cede0068a1b26533cace807f883ee                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| spotPrice             | VARCHAR   | 686567164179105                                                    |                                                                                                                        |
| delta                 | VARCHAR   | 0                                                                  |                                                                                                                        |
| numItems              | VARCHAR   | 1                                                                  |                                                                                                                        |
| feeMultiplier         | VARCHAR   | 0                                                                  |                                                                                                                        |
| protocolFeeMultiplier | VARCHAR   | 5000000000000000                                                   |                                                                                                                        |

## 90. Table: LinearCurve\_call\_getSellInfo\_history

| Column                | Type      | Example                                                            | Description                                                                                                            |
| --------------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp      | TIMESTAMP | 2023-07-30 05:48:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number         | INTEGER   | 17803869                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash     | VARCHAR   | 0x4bf6a51b02623f67fa48819d1d545045d017840143abaf5f36ef571eda4a03de | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index    | INTEGER   | 83                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address        | VARCHAR   | 0,0,0,2,0,0,1                                                      | Comma separated list of trace address in call tree                                                                     |
| to\_address           | VARCHAR   | 0x5b6ac51d9b1cede0068a1b26533cace807f883ee                         | Address of the called contract                                                                                         |
| status                | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                 | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| spotPrice             | VARCHAR   | 0                                                                  |                                                                                                                        |
| delta                 | VARCHAR   | 100000000000000                                                    |                                                                                                                        |
| numItems              | VARCHAR   | 1                                                                  |                                                                                                                        |
| feeMultiplier         | VARCHAR   | 50000000000000000                                                  |                                                                                                                        |
| protocolFeeMultiplier | VARCHAR   | 5000000000000000                                                   |                                                                                                                        |
