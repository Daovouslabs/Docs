# kalao

## 1. Table: KalaoAuctionHouse\_event\_AuctionCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-27 14:12:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11464741                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x848b28c4851970e79e4d6efcc81b0a1fd5705c394068e15861ac04cc163a651a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36d69b62b5c312d27790751814b7099f1e3245b2                         | Address of the contract that produced the log                |
| position          | VARCHAR   | 6821                                                               |                                                              |

## 2. Table: KalaoAuctionHouse\_event\_AuctionEnded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-10 08:45:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14504788                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x13d191cb05fc85cd0a782ec5ba88dc19ade96aa5bf4609ca9a86b905d655f8ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36d69b62b5c312d27790751814b7099f1e3245b2                         | Address of the contract that produced the log                |
| winner            | VARCHAR   | 0x542178f0addef219e01eded384ba4d8657fabd61                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |
| kalaoPart         | VARCHAR   | 0                                                                  |                                                              |
| royaltyAmount     | VARCHAR   | 0                                                                  |                                                              |
| position          | VARCHAR   | 8584                                                               |                                                              |

## 3. Table: KalaoAuctionHouse\_event\_AuctionStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-30 08:07:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16706383                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8c4521799c8720a77b423affed4b928d05de8d14a9fffda6a4440cb93d857000 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36d69b62b5c312d27790751814b7099f1e3245b2                         | Address of the contract that produced the log                |
| sellerAddress     | VARCHAR   | 0x0a76178985388d86bc8ac57c52ed3909b24288ee                         |                                                              |
| tokenAddress      | VARCHAR   | 0xdec892443ee64876df5ba1c72b8e3e442d7076fd                         |                                                              |
| tokenId           | VARCHAR   | 61                                                                 |                                                              |
| startingPrice     | VARCHAR   | 6161000000000000000000                                             |                                                              |
| duration          | VARCHAR   | 777600                                                             |                                                              |
| position          | VARCHAR   | 9042                                                               |                                                              |
| royalty           | VARCHAR   | true                                                               |                                                              |

## 4. Table: KalaoAuctionHouse\_event\_BidClaimed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| position          | VARCHAR   |                                                              |             |

## 5. Table: KalaoAuctionHouse\_event\_BidWithdrawn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| bidder            | VARCHAR   |                                                              |             |

## 6. Table: KalaoAuctionHouse\_event\_HighestBidIncreased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-27 07:47:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10115562                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3515a6090441d4848062bdeed6ecfada3b527d61cf64e70f8ead0db665042332 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36d69b62b5c312d27790751814b7099f1e3245b2                         | Address of the contract that produced the log                |
| bidder            | VARCHAR   | 0x3d03ed4fe448b9539bd909c959f8b0252818d195                         |                                                              |
| amount            | VARCHAR   | 5850000000000000000                                                |                                                              |
| endTime           | VARCHAR   | 1643305749                                                         |                                                              |
| claimTime         | VARCHAR   | 1644515349                                                         |                                                              |
| postion           | VARCHAR   | 3169                                                               |                                                              |

## 7. Table: KalaoAuctionHouse\_event\_NFTClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-18 22:50:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12281846                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x84fd8b1f5b508483e896b5440d8c087fe4b340e312925a1f9be26aa518fad7c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36d69b62b5c312d27790751814b7099f1e3245b2                         | Address of the contract that produced the log                |
| position          | VARCHAR   | 6693                                                               |                                                              |

## 8. Table: KalaoDirect\_event\_NftSold\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-25 19:40:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13893410                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdac8d81c8bcdb51c4e481dcd116506b253d4f9a9437dbd8b9328322806e8d853 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11ac3118309a7215c6d87c7c396e2df333ae3a9c                         | Address of the contract that produced the log                |
| position          | VARCHAR   | 182473                                                             |                                                              |
| buyer             | VARCHAR   | 0x764cd4606320ad7a4bfaad4269a923345abd11e8                         |                                                              |
| royalties         | VARCHAR   | 0                                                                  |                                                              |

## 9. Table: KalaoDirect\_event\_SaleCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 15:36:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13499532                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17944f24ff5d92e77bf29b3cca0289a3cb9bd60ea4d69c31c1ee2b4b185bb102 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11ac3118309a7215c6d87c7c396e2df333ae3a9c                         | Address of the contract that produced the log                |
| position          | VARCHAR   | 176788                                                             |                                                              |

## 10. Table: KalaoDirect\_event\_SaleStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-27 07:47:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11453149                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe98705640a0627ef81aa8c72ea3ef87838dfe0a66bb2cce4f212600e2e2d83c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x11ac3118309a7215c6d87c7c396e2df333ae3a9c                         | Address of the contract that produced the log                |
| sellerAddress     | VARCHAR   | 0x2475a5fc03f0de0f055d420d6ee11d7c5cf8937f                         |                                                              |
| tokenAddres       | VARCHAR   | 0x005000ab65015391d2f35d147a8376d6b2354d2e                         |                                                              |
| tokenId           | VARCHAR   | 1595                                                               |                                                              |
| price             | VARCHAR   | 500000000000000000                                                 |                                                              |
| position          | VARCHAR   | 142067                                                             |                                                              |
| royalty           | VARCHAR   | false                                                              |                                                              |
