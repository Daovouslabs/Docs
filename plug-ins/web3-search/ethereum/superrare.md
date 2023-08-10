# superrare

## 1. Table: Auction\_event\_AuctionSettled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-11 23:32:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12020250                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ea514e38b672df10242a49ef15463b56a80cad32c98cdd38261f03d8533b7d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c9f364bf7a56ed058fc63ef81c6cf09c833e656                         | Address of the contract that produced the log                |
| \_contractAddress | VARCHAR   | 0xb932a70a57673d89f4acffbe830e8ed7f75fb9e0                         |                                                              |
| \_bidder          | VARCHAR   | 0x6c3675c755c06b236cb10b5acfa0445fd8aad455                         |                                                              |
| \_seller          | VARCHAR   | 0x0b1779abce1f8de2ed53e8d4d74b41c4e9b666f6                         |                                                              |
| \_tokenId         | VARCHAR   | 19206                                                              |                                                              |
| \_amount          | VARCHAR   | 3500000000000000000                                                |                                                              |

## 2. Table: Marketplace\_v1\_event\_AcceptBid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-20 17:24:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8969615                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8d17b65362b8f5e7345c40233ca40d8f36d12dc56ce3242668b7644d5ca246a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 235                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2947f98c42597966a0ec25e92843c09ac17fbaa7                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0xb932a70a57673d89f4acffbe830e8ed7f75fb9e0                         |                                                              |
| \_bidder          | VARCHAR   | 0x14287e62b859a3a5e19b3c2d59ed1f12ac94ba4c                         |                                                              |
| \_seller          | VARCHAR   | 0x2e0b873d26f6d90f347757ed0d041bc65e02a89f                         |                                                              |
| \_amount          | VARCHAR   | 170000000000000000                                                 |                                                              |
| \_tokenId         | VARCHAR   | 5339                                                               |                                                              |

## 3. Table: Marketplace\_v1\_event\_Sold\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-01 21:49:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8855144                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdde0024a3b312a73db5be420b41db1b6f449898079d8450a03ea359db4880d37 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 108                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2947f98c42597966a0ec25e92843c09ac17fbaa7                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0xb932a70a57673d89f4acffbe830e8ed7f75fb9e0                         |                                                              |
| \_buyer           | VARCHAR   | 0x9af481276b075e036bc23e887a8bd275e69ef74c                         |                                                              |
| \_seller          | VARCHAR   | 0xdc546f477f273bcf327297bf4adcb671b5f20be1                         |                                                              |
| \_amount          | VARCHAR   | 500000000000000000                                                 |                                                              |
| \_tokenId         | VARCHAR   | 4999                                                               |                                                              |

## 4. Table: Marketplace\_v2\_event\_AcceptBid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-19 00:08:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12853724                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0923d1a6e8f51b1d638b2ce165e787353d815b09a6cdb8f178630fa432fe741 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 287                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65b49f7aee40347f5a90b714be4ef086f3fe5e2c                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0xb932a70a57673d89f4acffbe830e8ed7f75fb9e0                         |                                                              |
| \_bidder          | VARCHAR   | 0x99d46eb671bfb7f367ebf9d5fc76b99587277de5                         |                                                              |
| \_seller          | VARCHAR   | 0xdfc6b16343f92c1347b6e9700aa6c5d9e34794a1                         |                                                              |
| \_amount          | VARCHAR   | 80000000000000000                                                  |                                                              |
| \_tokenId         | VARCHAR   | 20824                                                              |                                                              |

## 5. Table: Marketplace\_v2\_event\_Sold\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-19 15:59:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12665730                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x66053a0bf93e5eb7972c1fbd46985fe29af75c3a272aed025251e978c0aed632 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x65b49f7aee40347f5a90b714be4ef086f3fe5e2c                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0xb932a70a57673d89f4acffbe830e8ed7f75fb9e0                         |                                                              |
| \_buyer           | VARCHAR   | 0xe703f231ab056ecb99c92a1232cc1020acfc72f8                         |                                                              |
| \_seller          | VARCHAR   | 0xe351d72b95bcba150a15d8d34cfa11b434448d7c                         |                                                              |
| \_amount          | VARCHAR   | 2900000000000000000                                                |                                                              |
| \_tokenId         | VARCHAR   | 20771                                                              |                                                              |

## 6. Table: SupeRare\_event\_AcceptBid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-08-19 18:09:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6176887                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6b88c5d46b8f7f85b1ee26fcaf3c728c67fbda388430ef278790b2d2e7490467 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| \_bidder          | VARCHAR   | 0x6853a596d6d7264d3622546da3b891b6fe17eb82                         |                                                              |
| \_seller          | VARCHAR   | 0x77350e1152efd5f2d807a6124015c629a907155e                         |                                                              |
| \_amount          | VARCHAR   | 175000000000000000                                                 |                                                              |
| \_tokenId         | VARCHAR   | 604                                                                |                                                              |

## 7. Table: SupeRare\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-19 14:50:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11289087                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5a8c6b0e5e0a6987ae8d04b981f4ce0bae5810a6c4e0e9f8db36bd883bfea4e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x50ff838cf414dbbb4e019b8b9cad46513eedcb41                         |                                                              |
| \_approved        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_tokenId         | VARCHAR   | 1271                                                               |                                                              |

## 8. Table: SupeRare\_event\_Bid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-29 01:40:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6791525                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c3f6c4726d8e3b0c732e7892dc4b4e3b5144a260e8ba713715adbc06a9aaff9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| \_bidder          | VARCHAR   | 0x335e19b3f5dcfa2e398ee7d5ff430a1f8ccc88b2                         |                                                              |
| \_amount          | VARCHAR   | 250000000000000000                                                 |                                                              |
| \_tokenId         | VARCHAR   | 953                                                                |                                                              |

## 9. Table: SupeRare\_event\_CancelBid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-13 15:53:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13218282                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x795eab3c3893b18a213c41b56373dbcfca604177aa8db7ac146ed9e11f0ddcd5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 318                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| \_bidder          | VARCHAR   | 0x8213985ee0904c659efc64859a9759cc222eb259                         |                                                              |
| \_amount          | VARCHAR   | 1000000000000000000                                                |                                                              |
| \_tokenId         | VARCHAR   | 762                                                                |                                                              |

## 10. Table: SupeRare\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-08-06 18:47:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6100189                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc94319d2854b38b90c6c8a5d0ccabf6d23d01aecdfcf71dca4fbaeb055ea7cbc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x4ce80560ede7d0c8800292f9517988ef479e6ee6                         |                                                              |
| newOwner          | VARCHAR   | 0x2a5ecfde059e54606a885516f14635a6d25bb316                         |                                                              |

## 11. Table: SupeRare\_event\_SalePriceSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 08:01:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13235579                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0dd3d3ff64d013cf56c88826049b1170baa41b283f2c9daf4b2ed0a851295f96 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| \_tokenId         | VARCHAR   | 2450                                                               |                                                              |
| \_price           | VARCHAR   | 1000000000000000000                                                |                                                              |

## 12. Table: SupeRare\_event\_Sold\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-03 13:49:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9044000                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe6c9cf84c444ec3c8fd8f039ab6295697a55e4f7f986a2f1bd163c7f7a2084fc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| \_buyer           | VARCHAR   | 0x4059457092cc3812d56676df6a75fd21204fbe2f                         |                                                              |
| \_seller          | VARCHAR   | 0xf8b32d30ac6ab3030595432533d7836fd76b078d                         |                                                              |
| \_amount          | VARCHAR   | 1000000000000000000                                                |                                                              |
| \_tokenId         | VARCHAR   | 2085                                                               |                                                              |

## 13. Table: SupeRare\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-17 12:45:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6348365                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x00e7152d0c0e8b09dae819025a459c2d3fc47ad5a3eddd25f33d8a16935753bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_to              | VARCHAR   | 0x89add8c2d24467410e60e2c24aba31b8ab9e05d8                         |                                                              |
| \_tokenId         | VARCHAR   | 696                                                                |                                                              |

## 14. Table: SupeRare\_event\_WhitelistCreator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-05 16:30:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6648974                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2509228a5ce5037a2b6e0658a0c826c290881c199ddc5b419bb18872662a565 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x41a322b28d0ff354040e2cbc676f0320d8c8850d                         | Address of the contract that produced the log                |
| \_creator         | VARCHAR   | 0x874ddff8ac72db190cacad4ba22baf9b07039649                         |                                                              |

## 15. Table: SuperRareBazaar\_event\_AcceptOffer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-06 08:26:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16768121                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc925ce8ee97fc6241a6a860c43ae2857b17c83c07293b0bb14b4291897eb24ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0xb932a70a57673d89f4acffbe830e8ed7f75fb9e0                         |                                                              |
| \_bidder          | VARCHAR   | 0x8a90f7679506b79a9175bcf6cb755ecba8e905f0                         |                                                              |
| \_seller          | VARCHAR   | 0x5e8799ccd95d91374c59f5926cc66ceef2bd9d8e                         |                                                              |
| \_currencyAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_amount          | VARCHAR   | 250000000000000000                                                 |                                                              |
| \_tokenId         | VARCHAR   | 43258                                                              |                                                              |
| \_splitAddresses  | VARCHAR   | 0x5e8799cCD95D91374C59f5926CC66cEEF2bD9d8E                         |                                                              |
| \_splitRatios     | VARCHAR   | 100                                                                |                                                              |

## 16. Table: SuperRareBazaar\_event\_AuctionBid\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-08-03 19:56:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17836695                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x5008d042beb40b457f7e97a802913e9342a7eca50d3f2e12557c2fe7dcb8f658 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 539                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_contractAddress  | VARCHAR   | 0x8a1521398214a61bef23e0a2f2909a6a152f9341                         |                                                              |
| \_bidder           | VARCHAR   | 0x732bb12525961f5853154deb9d0a4aacd2eb240f                         |                                                              |
| \_tokenId          | VARCHAR   | 73                                                                 |                                                              |
| \_currencyAddress  | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_amount           | VARCHAR   | 69000000000000000                                                  |                                                              |
| \_startedAuction   | VARCHAR   | true                                                               |                                                              |
| \_newAuctionLength | VARCHAR   | 0                                                                  |                                                              |
| \_previousBidder   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 17. Table: SuperRareBazaar\_event\_AuctionSettled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-02 19:06:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15460897                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x36f5e499aaca6ba1556acf19140a4a3c1b26d420e25a15236bdd989dd2cf2c33 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_contractAddress | VARCHAR   | 0xb932a70a57673d89f4acffbe830e8ed7f75fb9e0                         |                                                              |
| \_bidder          | VARCHAR   | 0x782c1b1d149b2d2cd6cadb91cc41b8bb8f148537                         |                                                              |
| \_seller          | VARCHAR   | 0xd75cd3dfea2d1688961e62b08b333692df0e66ec                         |                                                              |
| \_tokenId         | VARCHAR   | 35796                                                              |                                                              |
| \_currencyAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_amount          | VARCHAR   | 150000000000000000                                                 |                                                              |

## 18. Table: SuperRareBazaar\_event\_CancelAuction\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 12:59:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17741670                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3748518605bd64a2a31fb9612dfec6892d7ccd5c272897fb2576ccdc4308174f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 513                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_contractAddress | VARCHAR   | 0xb37f64b8f181b24d6adbf017ec19e2ce34f88c7f                         |                                                              |
| \_tokenId         | VARCHAR   | 12                                                                 |                                                              |
| \_auctionCreator  | VARCHAR   | 0x0ac30c6aaf2ffc01938d92aca03f71f913636134                         |                                                              |

## 19. Table: SuperRareBazaar\_event\_CancelOffer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-26 15:35:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17564523                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x118e4d544f7c497b9aaf00c877a01183dc7ef60a484d74f903a9ab5d07bbe4a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0x4592fdca89c5ea194f548e6ee688156c29db01a4                         |                                                              |
| \_bidder          | VARCHAR   | 0xf64d8825599ec70473df54909ec236e4df44add5                         |                                                              |
| \_currencyAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_amount          | VARCHAR   | 281000000000000000                                                 |                                                              |
| \_tokenId         | VARCHAR   | 70                                                                 |                                                              |

## 20. Table: SuperRareBazaar\_event\_NewAuction\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 20:48:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17858397                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf02135d13c9e2dcd838811995db4189314263b7cc5d42bfb6441295e9f99e682 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 250                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_contractAddress | VARCHAR   | 0xe23b7861a432b5560f8d494b0832c020c5fef3f6                         |                                                              |
| \_tokenId         | VARCHAR   | 1                                                                  |                                                              |
| \_auctionCreator  | VARCHAR   | 0x4a05a4e44f7f4de0c10a477121f83acf19527c71                         |                                                              |
| \_currencyAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_startingTime    | VARCHAR   | 0                                                                  |                                                              |
| \_minimumBid      | VARCHAR   | 350000000000000000                                                 |                                                              |
| \_lengthOfAuction | VARCHAR   | 86400                                                              |                                                              |

## 21. Table: SuperRareBazaar\_event\_OfferPlaced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-26 19:06:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17345236                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x47c11537b8f32c7e279ea576749a2dc29034ec46b8ffe2879df0b0593d4d8592 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0xb932a70a57673d89f4acffbe830e8ed7f75fb9e0                         |                                                              |
| \_bidder          | VARCHAR   | 0x3c3685eeec9bf31057b1d4dc0f7c9603c1eb9aae                         |                                                              |
| \_currencyAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_amount          | VARCHAR   | 28800000000000000000                                               |                                                              |
| \_tokenId         | VARCHAR   | 34459                                                              |                                                              |
| \_convertible     | VARCHAR   | false                                                              |                                                              |

## 22. Table: SuperRareBazaar\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-08 17:57:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14166874                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9dd17227173b4d1d58a0f2d8778f304ed083fee33df105daca60fd382125245f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 426                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0bbf6fbb27645d6e587f63a260917ecd9b19b22f                         |                                                              |
| newOwner          | VARCHAR   | 0x860a80d33e85e97888f1f0c75c6e5bbd60b48da9                         |                                                              |

## 23. Table: SuperRareBazaar\_event\_SetSalePrice\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-09 19:58:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16792873                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd8afd44df46c675e735ccfb10c2df4cd656ad5799005b8444892385b6fdf2dd9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 517                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0x0e3fb30965eaec2f590c7caea280a30bde6f9e03                         |                                                              |
| \_currencyAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_target          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_amount          | VARCHAR   | 583000000000000000                                                 |                                                              |
| \_tokenId         | VARCHAR   | 42                                                                 |                                                              |
| \_splitRecipients | VARCHAR   | 0x240ad467a71210629D71D4dE22ebde27951c83Fc                         |                                                              |
| \_splitRatios     | VARCHAR   | 100                                                                |                                                              |

## 24. Table: SuperRareBazaar\_event\_Sold\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-29 14:38:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16076297                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76b430f35db221d290edc35002cc188a80359b140b847ad25dd8c2701301ecee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 32                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d7c44773c52d396f43c2d511b81aa168e9a7a42                         | Address of the contract that produced the log                |
| \_originContract  | VARCHAR   | 0xca34d13b685722ad49377e757f0c9e099b9538f0                         |                                                              |
| \_buyer           | VARCHAR   | 0x87395a1a46f75c206d09f18b988c72accd939a78                         |                                                              |
| \_seller          | VARCHAR   | 0xa66bf5d22d48b69a08746d28c711f6d56d44480e                         |                                                              |
| \_currencyAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_amount          | VARCHAR   | 75000000000000000                                                  |                                                              |
| \_tokenId         | VARCHAR   | 2                                                                  |                                                              |
