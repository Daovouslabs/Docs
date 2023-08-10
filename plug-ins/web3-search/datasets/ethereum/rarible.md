# rarible

## 1. Table: ERC1155Sale\_v1\_event\_Buy\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 20:28:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10705739                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63d0c3bb9ce658b2c3cab7f07d6e2c38b3de81e4bde0ec619582dbfd29ffd5ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c530a698b6e83d562db09079bc458d4dad4e6c5                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xd07dc4262bcdbf85190c01c996b4c06a461d2430                         |                                                              |
| tokenId           | VARCHAR   | 3416                                                               |                                                              |
| owner             | VARCHAR   | 0xd06124cf5f968f62fa0cf1e9399eef967b367d3f                         |                                                              |
| price             | VARCHAR   | 1000                                                               |                                                              |
| buyer             | VARCHAR   | 0x0eb9a7ff5cbf719251989caf1599c1270eafb531                         |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 2. Table: ERC1155Sale\_v2\_event\_Buy\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-15 02:52:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11259795                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf748d9134d058f3c60dd9fa627517fe5c494192ff964a2abe71c15f044593f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x93f2a75d771628856f37f256da95e99ea28aafbe                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0xd07dc4262bcdbf85190c01c996b4c06a461d2430                         |                                                              |
| tokenId           | VARCHAR   | 10827                                                              |                                                              |
| owner             | VARCHAR   | 0x4a140bcbf740a9c507049cefeb3e4504d0b82ceb                         |                                                              |
| price             | VARCHAR   | 10000000000000                                                     |                                                              |
| buyer             | VARCHAR   | 0x1a0ea4a609cfaba7fc4df30c139424198607fd50                         |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 3. Table: ERC721Sale\_v1\_event\_Buy\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| tokenId           | VARCHAR   |                                                              |             |
| owner             | VARCHAR   |                                                              |             |
| price             | VARCHAR   |                                                              |             |
| buyer             | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 4. Table: ERC721Sale\_v2\_event\_Buy\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-30 06:11:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10962097                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x071d5b619d7da2a01848eeb07b20d8236dccb60f359ce5dc9f2b9eefd427a832 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 61                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x131aebbfe55bca0c9eaad4ea24d386c5c082dd58                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x60f80121c31a0d46b5279700f9df786054aa5ee5                         |                                                              |
| tokenId           | VARCHAR   | 26892                                                              |                                                              |
| seller            | VARCHAR   | 0x99f0b621c3cb9149bd653ae5fcb79481764eb5f2                         |                                                              |
| buyer             | VARCHAR   | 0xd98a3954353055ab642c9159c7f3b25dac2dc29b                         |                                                              |
| price             | VARCHAR   | 1000000000000000                                                   |                                                              |
| nonce             | VARCHAR   | 1                                                                  |                                                              |

## 5. Table: ExchangeStateV1\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-24 12:23:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12696806                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe2dc030b0945ecb05a9338e93b5a4404d7492cbd6185eab9e404e6c8d920f24c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 253                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed1f5f8724cc185d4e48a71a7fac64fa5216e4a8                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x09eab21c40743b2364b94345419138ef80f39e30                         |                                                              |

## 6. Table: ExchangeStateV1\_event\_OperatorRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 7. Table: ExchangeStateV1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-17 08:57:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11274457                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5eb3020fda82c8f85e4536e275c407adf7ae54e0e5032311d9869794e2559964 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xed1f5f8724cc185d4e48a71a7fac64fa5216e4a8                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x3482549fca7511267c9ef7089507c0f16ea1dcc1                         |                                                              |

## 8. Table: ExchangeV1\_event\_Buy\_history

| Column            | Type      | Example                                                                      | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-06 16:55:48+00:00                                                    | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12187380                                                                     | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x53c236956bbbe2970154d7b3b7120979505b3353b80be883ed0c453de3494a85           | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 382                                                                          | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcd4ec7b66fbc029c116ba9ffb3e59351c20b5b06                                   | Address of the contract that produced the log                |
| sellToken         | VARCHAR   | 0x83c797f35d818a46c28b3b1b7b382d50a5e085a2                                   |                                                              |
| sellTokenId       | VARCHAR   | 1                                                                            |                                                              |
| sellValue         | VARCHAR   | 1                                                                            |                                                              |
| owner             | VARCHAR   | 0x7b192dd0024ab088d6efa2c9a0c56f3b92255805                                   |                                                              |
| buyToken          | VARCHAR   | 0x0000000000000000000000000000000000000000                                   |                                                              |
| buyTokenId        | VARCHAR   | 0                                                                            |                                                              |
| buyValue          | VARCHAR   | 600000000000000000                                                           |                                                              |
| buyer             | VARCHAR   | 0x844fa4379f3c92f79b32f92574ed3694c2b7b49c                                   |                                                              |
| amount            | VARCHAR   | 1                                                                            |                                                              |
| salt              | VARCHAR   | 6849745510712184068461023909360249734494978531413272705151225421971558719910 |                                                              |

## 9. Table: ExchangeV1\_event\_Cancel\_history

| Column            | Type      | Example                                                                      | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-13 10:04:06+00:00                                                    | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13996512                                                                     | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1eedcee593d4e6079b9c45a725ca86abd6f627f9f90ffd81a5d459fa7415fb0d           | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 452                                                                          | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcd4ec7b66fbc029c116ba9ffb3e59351c20b5b06                                   | Address of the contract that produced the log                |
| sellToken         | VARCHAR   | 0x60f80121c31a0d46b5279700f9df786054aa5ee5                                   |                                                              |
| sellTokenId       | VARCHAR   | 59988                                                                        |                                                              |
| owner             | VARCHAR   | 0xe8f74cbaf5be061be421ccf5af5c89e05995e180                                   |                                                              |
| buyToken          | VARCHAR   | 0x0000000000000000000000000000000000000000                                   |                                                              |
| buyTokenId        | VARCHAR   | 0                                                                            |                                                              |
| salt              | VARCHAR   | 3422369057858151502382892178058766454755605847425812324598512611751368486048 |                                                              |

## 10. Table: ExchangeV1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-17 09:11:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11274515                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1de5c585ff18780ae5a7eeb37efe39397daedc576105d376a11b19f525330e02 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcd4ec7b66fbc029c116ba9ffb3e59351c20b5b06                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x3482549fca7511267c9ef7089507c0f16ea1dcc1                         |                                                              |

## 11. Table: ExchangeV2\_event\_Cancel\_history

| Column                   | Type                                    | Example                                                                                              | Description                                                  |
| ------------------------ | --------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp         | TIMESTAMP                               | 2022-06-16 09:42:17+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number            | INTEGER                                 | 14972616                                                                                             | The block number where this event was emitted                |
| transaction\_hash        | VARCHAR                                 | 0xa4f8a6ccbf7affb6acbdded29451318313e8805cc6b43285b935d851116b2649                                   | Hash of the transactions in which this event was emitted     |
| log\_index               | INTEGER                                 | 53                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address        | VARCHAR                                 | 0x9757f2d2b135150bbeb65308d4a91804107cd8d6                                                           | Address of the contract that produced the log                |
| hash                     | VARCHAR                                 | 0xb1ae08d842daa85961de5e101bd1a9659a8ebd39989ce1028df119652b95dace                                   |                                                              |
| maker                    | VARCHAR                                 | 0x58081fd8af76d198cb0584df51d3e1ffd1171746                                                           |                                                              |
| makeAssetType            | STRUCT\<assetClass STRING, data STRING> | {'assetClass': '0x1cdfaa40', 'data': '0x00000000000000000000000058339337d9172e222b97c5d3c0b3fcc7a57e |                                                              |
| makeAssetType.assetClass | VARCHAR                                 | 0x1cdfaa40                                                                                           |                                                              |
| makeAssetType.data       | VARCHAR                                 | 0x00000000000000000000000058339337d9172e222b97c5d3c0b3fcc7a57e230e0000000000000000000000000000000000 |                                                              |
| takeAssetType            | STRUCT\<assetClass STRING, data STRING> | {'assetClass': '0xaaaebeba', 'data': '0x'}                                                           |                                                              |
| takeAssetType.assetClass | VARCHAR                                 | 0xaaaebeba                                                                                           |                                                              |
| takeAssetType.data       | VARCHAR                                 | 0x                                                                                                   |                                                              |

## 12. Table: ExchangeV2\_event\_Match\_history

| Column                | Type                                    | Example                                                                                              | Description                                                  |
| --------------------- | --------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP                               | 2021-10-23 13:10:23+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER                                 | 13473974                                                                                             | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR                                 | 0x634de0c49086342dfb8a999134da2eafa4950b10b3ffc39b3697d9cfe5541444                                   | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER                                 | 267                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR                                 | 0x9757f2d2b135150bbeb65308d4a91804107cd8d6                                                           | Address of the contract that produced the log                |
| leftHash              | VARCHAR                                 | 0x36a60b6803eef70efd0abc36859ac7fbe50959a360426079d5f5595795f43e5d                                   |                                                              |
| rightHash             | VARCHAR                                 | 0xa349c703e95a7ac2e1d5bf3f56c6452441d2a11aa84b2bc45d8a9ff9b7598dcd                                   |                                                              |
| leftMaker             | VARCHAR                                 | 0x4d92ecf1bf623f97956d791d63d2c17fa09c6859                                                           |                                                              |
| rightMaker            | VARCHAR                                 | 0x5c72adc0059454acfb51fb4c1603d2c0f4c086ef                                                           |                                                              |
| newLeftFill           | VARCHAR                                 | 1000000000000000000                                                                                  |                                                              |
| newRightFill          | VARCHAR                                 | 1                                                                                                    |                                                              |
| leftAsset             | STRUCT\<assetClass STRING, data STRING> | {'assetClass': '0xd8f960c1', 'data': '0x000000000000000000000000f6793da657495ffeff9ee6350824910abc21 |                                                              |
| leftAsset.assetClass  | VARCHAR                                 | 0xd8f960c1                                                                                           |                                                              |
| leftAsset.data        | VARCHAR                                 | 0x000000000000000000000000f6793da657495ffeff9ee6350824910abc21356c0000000000000000000000000000000000 |                                                              |
| rightAsset            | STRUCT\<assetClass STRING, data STRING> | {'assetClass': '0xaaaebeba', 'data': '0x'}                                                           |                                                              |
| rightAsset.assetClass | VARCHAR                                 | 0xaaaebeba                                                                                           |                                                              |
| rightAsset.data       | VARCHAR                                 | 0x                                                                                                   |                                                              |

## 13. Table: ExchangeV2\_event\_MatcherChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-05 13:46:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14146346                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x708b81bc91b3095493056e33fa91e77ba699ce07a01bc99c033b6f904a92d526 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9757f2d2b135150bbeb65308d4a91804107cd8d6                         | Address of the contract that produced the log                |
| assetType         | VARCHAR   | 0xf63c2825                                                         |                                                              |
| matcher           | VARCHAR   | 0xfa0607a4ebbb6f3783dcc0967a7bd44dc616f2e0                         |                                                              |

## 14. Table: ExchangeV2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-12 05:23:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12617828                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf8213dcebf3d7ae1804e629365e60f2b956187a4ecc6ec94e9846db1499e75ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9757f2d2b135150bbeb65308d4a91804107cd8d6                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x3482549fca7511267c9ef7089507c0f16ea1dcc1                         |                                                              |

## 15. Table: ExchangeV2\_event\_ProxyChange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-10 14:17:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13588970                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x336230930e1b337e964cb517a6967b929406c1c08845a6ee62234291c1b956db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 314                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9757f2d2b135150bbeb65308d4a91804107cd8d6                         | Address of the contract that produced the log                |
| assetType         | VARCHAR   | 0xa8c6716e                                                         |                                                              |
| proxy             | VARCHAR   | 0xcaaacf1a668446476626ddcad4a237d70c61efa9                         |                                                              |

## 16. Table: ExchangeV2\_event\_Transfer\_history

| Column                     | Type                                                                     | Example                                                                               | Description                                                  |
| -------------------------- | ------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp           | TIMESTAMP                                                                | 2022-08-06 03:44:06+00:00                                                             | Timestamp of the block where this event was emitted          |
| block\_number              | INTEGER                                                                  | 15286414                                                                              | The block number where this event was emitted                |
| transaction\_hash          | VARCHAR                                                                  | 0x6e2d245cadd4f3f220f6e3b4a8a3c63f2b9c9fb89b3c5cf12abbd527f0d663cd                    | Hash of the transactions in which this event was emitted     |
| log\_index                 | INTEGER                                                                  | 393                                                                                   | Integer of the log index position in the block of this event |
| contract\_address          | VARCHAR                                                                  | 0x9757f2d2b135150bbeb65308d4a91804107cd8d6                                            | Address of the contract that produced the log                |
| asset                      | STRUCT\<assetType STRUCT\<assetClass STRING, data STRING>, value STRING> | {'assetType': {'assetClass': '0xaaaebeba', 'data': '0x'}, 'value': '400000000000000'} |                                                              |
| asset.assetType            | STRUCT\<assetClass STRING, data STRING>                                  | {'assetClass': '0xaaaebeba', 'data': '0x'}                                            |                                                              |
| asset.assetType.assetClass | VARCHAR                                                                  | 0xaaaebeba                                                                            |                                                              |
| asset.assetType.data       | VARCHAR                                                                  | 0x                                                                                    |                                                              |
| asset.value                | VARCHAR                                                                  | 400000000000000                                                                       |                                                              |
| from                       | VARCHAR                                                                  | 0x0fc84c11a3b20850720baef3c81195da99b7b2af                                            |                                                              |
| to                         | VARCHAR                                                                  | 0x6c9f99c1e665dbe91a30689ad51145b95b1fa4ba                                            |                                                              |
| transferDirection          | VARCHAR                                                                  | 0xb45a3ba1                                                                            |                                                              |
| transferType               | VARCHAR                                                                  | 0xb3c5c697                                                                            |                                                              |

## 17. Table: TokenSale\_event\_Buy\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-04 10:37:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9213337                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4bc9b8055b2a35e58058a8623589ae97b437c61a7ac03fa45079b2a99e93616f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf2ee97405593bc7b6275682b0331169a48fedec7                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x560de36966bcd0d4691263b115aec64cb34e0281                         |                                                              |
| tokenId           | VARCHAR   | 220                                                                |                                                              |
| seller            | VARCHAR   | 0x13534638007051ca24d92bc10799d4c83dd66f0d                         |                                                              |
| buyer             | VARCHAR   | 0x6ee951568c625dfd0c497d43edb418b228e90c82                         |                                                              |
| price             | VARCHAR   | 300000000000000000                                                 |                                                              |
| nonce             | VARCHAR   | 1                                                                  |                                                              |
