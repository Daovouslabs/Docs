# foundation

## 1. Table: CollectionContract\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 14:36:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17237741                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9840724f0de432998b1bfb444d2fa68e48dc3c755b688ad10bda88e1a841dff1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 248                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4c0cd9517c259058c21405ce328efd104ffd894                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe0e3e6b95ef101f72f46107a2f86199c7caa8159                         |                                                              |
| to                | VARCHAR   | 0x15f4b11e24bbb578026f3b38ad5a8b7cf5799343                         |                                                              |
| tokenId           | VARCHAR   | 1                                                                  |                                                              |

## 2. Table: FNDCollectionFactory\_event\_CollectionCreated\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-12-29 20:07:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 13902306                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xb0ed1e87333471404048148767a9a75b42c31fc82b50692df34485354d0138b7 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 397                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x3b612a5b49e025a6e4ba4ee4fb1ef46d13588059                         | Address of the contract that produced the log                |
| collectionContract | VARCHAR   | 0xb74a9bbe56f2daba63576e1663e3e5dfbdd3bbf0                         |                                                              |
| creator            | VARCHAR   | 0x0e4c05aa246826628b89741170795ec05b1350a3                         |                                                              |
| version            | VARCHAR   | 1                                                                  |                                                              |
| name               | VARCHAR   | Aliens of Nichols Canyon                                           |                                                              |
| symbol             | VARCHAR   | ALIENS                                                             |                                                              |
| nonce              | VARCHAR   | 1044771048932852                                                   |                                                              |

## 3. Table: FNDNFT721\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 15:48:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17671362                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4043b59b4f7116960f232aabf60bf3a5f2ad9bcaecee7be6adb40ab03fa7578e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xfeae88b979ec76ff83f96dfbb5cfca42b92b6a1f                         |                                                              |
| operator          | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 4. Table: FNDNFT721\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 21:29:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15820628                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x63d609f38ee392d9a8e87818384f65afb1cce6ea4fa8a056f4cd5238af0a9e6f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 206                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x087ed99eebf62c3424b106834bf424d44632dd59                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 72149                                                              |                                                              |

## 5. Table: FNDNFT721\_event\_BaseURIUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-10 18:35:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17231808                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4660aafefee2e014880dc4166c6d321f33c3e3a0f71c67850a4c58e005618c48 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 457                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| baseURI           | VARCHAR   | ipfs://                                                            |                                                              |

## 6. Table: FNDNFT721\_event\_Minted\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-04-19 05:31:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12268667                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x5808d0f2e09508a861407a99461b265ba7f66f008f127e25805f4c3ef4667d94 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| creator              | VARCHAR   | 0x645d2b4bfb047566ff60e2e7112373885935eac4                         |                                                              |
| tokenId              | VARCHAR   | 26054                                                              |                                                              |
| indexedTokenIPFSPath | VARCHAR   | 0x8daa50318a61d4319e69c7a6aaea20fd7dd43050a4c9e435756e71da95903faa |                                                              |
| tokenIPFSPath        | VARCHAR   | QmP9TFAeVeU6jMR286UA6pzdrqz81Xskr8XTARnZy5nqEX/metadata.json       |                                                              |

## 7. Table: FNDNFT721\_event\_NFTCreatorMigrated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-16 22:06:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13038861                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab77745b73c52ac43cf245cd47c77bf2b99daaa5ec138591b97fb0548240255a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 43110                                                              |                                                              |
| originalAddress   | VARCHAR   | 0x6395c0e1d7c4bbf512f756a53d1f188fafb1c1ec                         |                                                              |
| newAddress        | VARCHAR   | 0xd3cf52047ac44aad6e770ad88a94f3798d02e8c5                         |                                                              |

## 8. Table: FNDNFT721\_event\_NFTMarketUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-13 20:00:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11648722                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c869ef2cd4d5e8ee227da1dc8ddfc0483f5971003cc4512a2f444a87cfffbca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| nftMarket         | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         |                                                              |

## 9. Table: FNDNFT721\_event\_NFTMetadataUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-13 20:00:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11648722                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c869ef2cd4d5e8ee227da1dc8ddfc0483f5971003cc4512a2f444a87cfffbca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| name              | VARCHAR   | FND NFT                                                            |                                                              |
| symbol            | VARCHAR   | FNDNFT                                                             |                                                              |
| baseURI           | VARCHAR   | https://ipfs.foundation.app/ipfs/                                  |                                                              |

## 10. Table: FNDNFT721\_event\_NFTOwnerMigrated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-06 21:25:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12973789                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x79d05c31f6264f47395c80a6e15d26ea5d0aab7dc1b27d7490ebcfcc1f88833d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 60993                                                              |                                                              |
| originalAddress   | VARCHAR   | 0x6a669af21699f2296bb7848718387e6f0f7a0574                         |                                                              |
| newAddress        | VARCHAR   | 0x8a48debdd94c9b19e74fdad114ec0fe568fd0500                         |                                                              |

## 11. Table: FNDNFT721\_event\_PaymentAddressMigrated\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-10-01 20:01:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 13335495                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x177e813c20f00b83c993c3fad067844acac8698012294621b9c1a8797b19fda1 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| tokenId                | VARCHAR   | 46421                                                              |                                                              |
| originalAddress        | VARCHAR   | 0xa23f7917b29c9a238ab324da043893b05ebcbf09                         |                                                              |
| newAddress             | VARCHAR   | 0xf0556eae3130c5d31cb4cd342f5b112c7bfc7416                         |                                                              |
| originalPaymentAddress | VARCHAR   | 0x000b39a4ef4b40354921a9262c02740102b1109f                         |                                                              |
| newPaymentAddress      | VARCHAR   | 0x1004ffa172ccbc563c9e30720dc0cf015698ecbe                         |                                                              |

## 12. Table: FNDNFT721\_event\_ProxyCallContractUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-23 22:28:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13084268                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbf7d6af58f0e9114cb7c0df43bf75ea76e224bddccea20e81829c2844a9f120b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| proxyCallContract | VARCHAR   | 0x461aa494426e04fb2449068bad5948a0d720aef2                         |                                                              |

## 13. Table: FNDNFT721\_event\_TokenCreatorPaymentAddressSet\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-08-18 12:01:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 13049084                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x835f3a59dd50ddda6f062711b93a6feaa48c27720cf315846912e2397ebdd82a | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| fromPaymentAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| toPaymentAddress   | VARCHAR   | 0x12ee14f3c62494328033c35519e119201919c499                         |                                                              |
| tokenId            | VARCHAR   | 73888                                                              |                                                              |

## 14. Table: FNDNFT721\_event\_TokenCreatorUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-26 22:20:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11734055                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8bd7ac8e7618f339418b3a2b57ffd1547ff0cd87c8e8c9ed5d35cad1fe86d339 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| fromCreator       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| toCreator         | VARCHAR   | 0xe7bd51dc30d4bdc9fddd42ea7c0a283590c9d416                         |                                                              |
| tokenId           | VARCHAR   | 29                                                                 |                                                              |

## 15. Table: FNDNFT721\_event\_TokenIPFSPathUpdated\_history

| Column               | Type      | Example                                                      | Description |
| -------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp     | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number        | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash    | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index           | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address    | VARCHAR   | Address of the contract that produced the log                |             |
| tokenId              | VARCHAR   |                                                              |             |
| indexedTokenIPFSPath | VARCHAR   |                                                              |             |
| tokenIPFSPath        | VARCHAR   |                                                              |             |

## 16. Table: FNDNFT721\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 21:21:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17708493                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f197a2b8a030a62c1da8ca1d46a135a870cea9fccce8b577cd58b1846bf7999 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 254                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x58136e0909b71981f1a37f1f87859c562ed3657a                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 66765                                                              |                                                              |

## 17. Table: FNDNFTMarket\_event\_BuyPriceAccepted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 09:14:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14569873                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5479611d902841282d918d4c97d575effaf3053bd7b983ca1e40466968435c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| nftContract       | VARCHAR   | 0xe63664db23b1dbb77731eaff034979a51926f357                         |                                                              |
| tokenId           | VARCHAR   | 24                                                                 |                                                              |
| seller            | VARCHAR   | 0xdebf50ad78b027c8c79272d7bb7905d20bd637a7                         |                                                              |
| buyer             | VARCHAR   | 0x5c112c552c19db682e7d30ad06169138b5c90317                         |                                                              |
| totalFees         | VARCHAR   | 500000000000000                                                    |                                                              |
| creatorRev        | VARCHAR   | 9500000000000000                                                   |                                                              |
| sellerRev         | VARCHAR   | 0                                                                  |                                                              |

## 18. Table: FNDNFTMarket\_event\_MarketFeesUpdated\_history

| Column                            | Type      | Example                                                            | Description                                                  |
| --------------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp                  | TIMESTAMP | 2021-05-06 15:25:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                     | INTEGER   | 12381512                                                           | The block number where this event was emitted                |
| transaction\_hash                 | VARCHAR   | 0x77b576463654f873568cb24429e5655cd65af172c70e35a14f8c566d730b1ae4 | Hash of the transactions in which this event was emitted     |
| log\_index                        | INTEGER   | 317                                                                | Integer of the log index position in the block of this event |
| contract\_address                 | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| primaryFoundationFeeBasisPoints   | VARCHAR   | 1500                                                               |                                                              |
| secondaryFoundationFeeBasisPoints | VARCHAR   | 500                                                                |                                                              |
| secondaryCreatorFeeBasisPoints    | VARCHAR   | 1000                                                               |                                                              |

## 19. Table: FNDNFTMarket\_event\_OfferAccepted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 07:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17790092                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9af01d5d2800529639688b6bc92c535bc72f339c736d20dc79366302005c538 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| nftContract       | VARCHAR   | 0xa36780ab0a40ef4d26aca43f59682d56ec0317f9                         |                                                              |
| tokenId           | VARCHAR   | 3                                                                  |                                                              |
| buyer             | VARCHAR   | 0x9fae8562dc4fbcdd9d26d6d10a7fb88ce60a028e                         |                                                              |
| seller            | VARCHAR   | 0x261c0003f3b51bc56da9957ecc83a714b5d9623e                         |                                                              |
| totalFees         | VARCHAR   | 32500000000000000                                                  |                                                              |
| creatorRev        | VARCHAR   | 617500000000000000                                                 |                                                              |
| sellerRev         | VARCHAR   | 0                                                                  |                                                              |

## 20. Table: FNDNFTMarket\_event\_PrivateSaleFinalized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-26 22:38:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13103762                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x54e9dd94c4ac615e05f149f72678e867f40e9dac75a91fbd6849ccb788759451 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| nftContract       | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         |                                                              |
| tokenId           | VARCHAR   | 76796                                                              |                                                              |
| seller            | VARCHAR   | 0x0c734fd6f48a02c05155ee4b2cddf73ac386f622                         |                                                              |
| buyer             | VARCHAR   | 0xbefb79854e5073077b6204357a2b48d2dfde8c43                         |                                                              |
| f8nFee            | VARCHAR   | 12547500000000000                                                  |                                                              |
| creatorFee        | VARCHAR   | 0                                                                  |                                                              |
| ownerRev          | VARCHAR   | 71102500000000000                                                  |                                                              |
| deadline          | VARCHAR   | 1630102578                                                         |                                                              |

## 21. Table: FNDNFTMarket\_event\_ReserveAuctionBidPlaced\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 12:51:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17663376                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80b2d316155ca0f9667ab41868d2c8e6d89ec2d7dadd70e6488f5c62409a9f99 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 244                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| auctionId         | VARCHAR   | 153614                                                             |                                                              |
| bidder            | VARCHAR   | 0xad1f1d998f7282cf561b0b8d4310eb7ade363664                         |                                                              |
| amount            | VARCHAR   | 50000000000000000                                                  |                                                              |
| endTime           | VARCHAR   | 1688997779                                                         |                                                              |

## 22. Table: FNDNFTMarket\_event\_ReserveAuctionCanceledByAdmin\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-19 23:53:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13451253                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbc1a1f89ed7e3d36ca4198ac35473a46d1cb464b8de68797d2dfb5d328b52eb1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 252                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| auctionId         | VARCHAR   | 102327                                                             |                                                              |
| reason            | VARCHAR   | Copyright violation                                                |                                                              |

## 23. Table: FNDNFTMarket\_event\_ReserveAuctionCanceled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 22:16:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17858832                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3db0b5bb6f1cc7e221a3161889d20c5e0af4550d481352e5e67be690149fc2d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| auctionId         | VARCHAR   | 344995                                                             |                                                              |

## 24. Table: FNDNFTMarket\_event\_ReserveAuctionConfigUpdated\_history

| Column                           | Type      | Example                                                            | Description                                                  |
| -------------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp                 | TIMESTAMP | 2021-01-21 20:08:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                    | INTEGER   | 11700877                                                           | The block number where this event was emitted                |
| transaction\_hash                | VARCHAR   | 0x731f358d3857efa3c56daa19d5f3a5fd0a5abb2f4f319f076aef36f066753eef | Hash of the transactions in which this event was emitted     |
| log\_index                       | INTEGER   | 229                                                                | Integer of the log index position in the block of this event |
| contract\_address                | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| minPercentIncrementInBasisPoints | VARCHAR   | 1000                                                               |                                                              |
| maxBidIncrementRequirement       | VARCHAR   | 100000000000000000                                                 |                                                              |
| duration                         | VARCHAR   | 86400                                                              |                                                              |
| extensionDuration                | VARCHAR   | 900                                                                |                                                              |
| goLiveDate                       | VARCHAR   | 1614618000                                                         |                                                              |

## 25. Table: FNDNFTMarket\_event\_ReserveAuctionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-28 01:07:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11942781                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39e90354440f6f6a6776bb87ef0181394a75208905e9b1aaeb852fbe4d4304e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x3f2d121417675c4a69ba6f3c616b5f1706b4bf82                         |                                                              |
| nftContract       | VARCHAR   | 0x3b3ee1931dc30c1957379fac9aba94d1c48a5405                         |                                                              |
| tokenId           | VARCHAR   | 1577                                                               |                                                              |
| duration          | VARCHAR   | 86400                                                              |                                                              |
| extensionDuration | VARCHAR   | 900                                                                |                                                              |
| reservePrice      | VARCHAR   | 100000000000000000                                                 |                                                              |
| auctionId         | VARCHAR   | 1449                                                               |                                                              |

## 26. Table: FNDNFTMarket\_event\_ReserveAuctionFinalized\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 07:09:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14138081                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1290e13b6e4731e33f7d68b46ce9c97ad4e8f14d901d256eed10c4a1f05a5d87 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| auctionId         | VARCHAR   | 148700                                                             |                                                              |
| seller            | VARCHAR   | 0xb2060351a3244e296b55db646caa07294ec0ccc8                         |                                                              |
| bidder            | VARCHAR   | 0x4569f94387508feb0c6b901e79bf859d14041d20                         |                                                              |
| f8nFee            | VARCHAR   | 15000000000000000                                                  |                                                              |
| creatorFee        | VARCHAR   | 85000000000000000                                                  |                                                              |
| ownerRev          | VARCHAR   | 0                                                                  |                                                              |

## 27. Table: FNDNFTMarket\_event\_ReserveAuctionSellerMigrated\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2021-07-06 21:56:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 12776437                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x44fe423bb88695a3d9f3408ae5073d475638177eb9a34d3c80b66859358d6db1 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 286                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| auctionId             | VARCHAR   | 54019                                                              |                                                              |
| originalSellerAddress | VARCHAR   | 0x4756aa3d5f88a5af125cbd9b4beeef1644339858                         |                                                              |
| newSellerAddress      | VARCHAR   | 0xbe8729909bdd4fcd82be44901a27de9dcb46b20f                         |                                                              |

## 28. Table: FNDNFTMarket\_event\_ReserveAuctionUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 13:00:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17834630                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc5e4c4b05eb97e87e4131b0076c5d3fad4f61eb66826fe8ee4d2b81e8ea5ebed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 332                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| auctionId         | VARCHAR   | 271439                                                             |                                                              |
| reservePrice      | VARCHAR   | 15000000000000000                                                  |                                                              |

## 29. Table: FNDNFTMarket\_event\_WithdrawPending\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-01 20:19:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12350435                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2ee42b42547981e5a17c41977b4bfa6e7539abd730ed78c076a28e9bd81eaeb8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x67df244584b67e8c51b10ad610aaffa9a402fdb6                         |                                                              |
| amount            | VARCHAR   | 15000000000000000                                                  |                                                              |

## 30. Table: FNDNFTMarket\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-07 00:03:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12584104                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1dccae97939e5bb83927073bf7c42091d9498bad0fa20ec5d28589bf6bf39c78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcda72070e455bb31c7690a170224ce43623d0b6f                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3bc78d96b17868bd57b5f4148e9418e0a123cadc                         |                                                              |
| amount            | VARCHAR   | 4250000000000000000                                                |                                                              |
