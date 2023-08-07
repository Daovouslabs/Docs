# treasure

## 1. Table: TreasureMarketplaceProxy\_event\_BidAccepted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 12:38:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 90276094                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9938c8d74c9bde28208ecd1ea0a66764deeb850b1a7ffbf601701f381624259f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09986b4e255b3c548041a30a2ee312fe176731c2                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x2fc148e0490971e0ecca5c0ba65610e0f1fb5cae                         |                                                              |
| bidder            | VARCHAR   | 0xa2225b86ccb530ac9a81d41a3d17ab643a9f7c8c                         |                                                              |
| nftAddress        | VARCHAR   | 0x37865fe8a9c839f330f35104eed08d4e8136c339                         |                                                              |
| tokenId           | VARCHAR   | 124                                                                |                                                              |
| quantity          | VARCHAR   | 4                                                                  |                                                              |
| pricePerItem      | VARCHAR   | 3000000000000000000                                                |                                                              |
| paymentToken      | VARCHAR   | 0x539bde0d7dbd336b79148aa742883198bbf60342                         |                                                              |
| bidType           | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: TreasureMarketplaceProxy\_event\_ItemSoldWithPaymentToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-11 13:59:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 110133387                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8e5588488f98f6f72c986e186a0b290cf1265fca0b15e502a701cb526af32778 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09986b4e255b3c548041a30a2ee312fe176731c2                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x791bf46d6aa1132f809665302b3c1069986ee0fe                         |                                                              |
| buyer             | VARCHAR   | 0x7ba6bc71dde89be985198ce0e2f8efe1ad683ba8                         |                                                              |
| nftAddress        | VARCHAR   | 0xbfeba04384cecfaf0240b49163ed418f82e43d3a                         |                                                              |
| tokenId           | VARCHAR   | 1                                                                  |                                                              |
| quantity          | VARCHAR   | 8                                                                  |                                                              |
| pricePerItem      | VARCHAR   | 119000000000000000000                                              |                                                              |
| paymentToken      | VARCHAR   | 0x539bde0d7dbd336b79148aa742883198bbf60342                         |                                                              |

## 3. Table: TreasureMarketplaceProxy\_event\_ItemSold\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-16 20:12:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12254626                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31e8feae9975eb5a2e4210246cebf76ddb937f3c9a63848d6676f088ccf620ab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x09986b4e255b3c548041a30a2ee312fe176731c2                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x5a7ce9daa15e7732832791f4d604a9fdf3a8e9eb                         |                                                              |
| buyer             | VARCHAR   | 0xa871b0e6607fbf7708dae03168f56f09dabdcb13                         |                                                              |
| nftAddress        | VARCHAR   | 0x00000000016c35e3613ad3ed484aa48f161b67fd                         |                                                              |
| tokenId           | VARCHAR   | 6406                                                               |                                                              |
| quantity          | VARCHAR   | 1                                                                  |                                                              |
| pricePerItem      | VARCHAR   | 10490000000000000000                                               |                                                              |

## 4. Table: TreasureMarketplace\_event\_ItemCanceled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-04 02:04:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7384455                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58935e4f4f238c7ab3a5c0af585542f21289c335bd6370f0a6236f7254d31ea9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x1c8f0c22f4c93aeb52c91ea0856f671106817195                         |                                                              |
| nftAddress        | VARCHAR   | 0x0af85a5624d24e2c6e7af3c0a0b102a28e36cea3                         |                                                              |
| tokenId           | VARCHAR   | 24251                                                              |                                                              |

## 5. Table: TreasureMarketplace\_event\_ItemListed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-11 07:21:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4554736                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6ace72450c654e18d56c6161ef638ce826b73fd3543a60a78729fadf9feff98 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x8a7e09e142907d013ef084fc736cf2c9ba0d9ecb                         |                                                              |
| nftAddress        | VARCHAR   | 0x17dacad7975960833f374622fad08b90ed67d1b5                         |                                                              |
| tokenId           | VARCHAR   | 3035                                                               |                                                              |
| quantity          | VARCHAR   | 1                                                                  |                                                              |
| pricePerItem      | VARCHAR   | 2419000000000000000000                                             |                                                              |
| expirationTime    | VARCHAR   | 1642482951375                                                      |                                                              |

## 6. Table: TreasureMarketplace\_event\_ItemSold\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-28 02:10:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7073730                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7852b588727b297663b866d5fc4362aa81170e3a6c8f27fb01b7d5f936d4e7e8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0xcba19876ee8225cc54a1b5b3dcc660b40d2dcd66                         |                                                              |
| buyer             | VARCHAR   | 0x812cda2181ed7c45a35a691e0c85e231d218e273                         |                                                              |
| nftAddress        | VARCHAR   | 0xae0d0c4cc3335fd49402781e406adf3f02d41bca                         |                                                              |
| tokenId           | VARCHAR   | 1664                                                               |                                                              |
| quantity          | VARCHAR   | 1                                                                  |                                                              |
| pricePerItem      | VARCHAR   | 80000000000000000000                                               |                                                              |

## 7. Table: TreasureMarketplace\_event\_ItemUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-24 05:52:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6787620                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1bfbafba556d0e0e91261c1775695c9d7df9c7554e3d63d45633dc91eac268b7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| seller            | VARCHAR   | 0x1e7920ed028e4b9e0e18ad5b0ba33bfffd8aa732                         |                                                              |
| nftAddress        | VARCHAR   | 0xf3d00a2559d84de7ac093443bcaada5f4ee4165c                         |                                                              |
| tokenId           | VARCHAR   | 1                                                                  |                                                              |
| quantity          | VARCHAR   | 27                                                                 |                                                              |
| pricePerItem      | VARCHAR   | 135000000000000000000                                              |                                                              |
| expirationTime    | VARCHAR   | 1653367978263                                                      |                                                              |

## 8. Table: TreasureMarketplace\_event\_NftWhitelistAdd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 23:43:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2983484                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd2eaf8afae3b01a71b6795ebcbf411dfdc7860495d0a4bde98544ae9a7f71dae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| nft               | VARCHAR   | 0x21e1969884d477afd2afd4ad668864a0eebd644c                         |                                                              |

## 9. Table: TreasureMarketplace\_event\_NftWhitelistRemove\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| nft               | VARCHAR   |                                                              |             |

## 10. Table: TreasureMarketplace\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-03 00:46:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7322418                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0afb70b86927b6b07f465c988c4e13fb0d0930198a4164828813bdcfaa0ffb83 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xdb6ab450178babcf0e467c1f3b436050d907e233                         |                                                              |
| newOwner          | VARCHAR   | 0xb13acf48136773de53aac51faf52b81b7a98582a                         |                                                              |

## 11. Table: TreasureMarketplace\_event\_UpdateFeeRecipient\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 23:43:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2983469                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0190080661f8bb4b14b524411e8bbaa3d76bacfac7b341f1d7bc07e5f997f27e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| feeRecipient      | VARCHAR   | 0xdb6ab450178babcf0e467c1f3b436050d907e233                         |                                                              |

## 12. Table: TreasureMarketplace\_event\_UpdateFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 23:43:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2983469                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0190080661f8bb4b14b524411e8bbaa3d76bacfac7b341f1d7bc07e5f997f27e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 500                                                                |                                                              |

## 13. Table: TreasureMarketplace\_event\_UpdateOracle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 23:43:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2983469                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0190080661f8bb4b14b524411e8bbaa3d76bacfac7b341f1d7bc07e5f997f27e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| oracle            | VARCHAR   | 0xb40bc8bf5f4df00b0b32c56e8d3ecd802656cce4                         |                                                              |

## 14. Table: TreasureMarketplace\_event\_UpdatePaymentToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 23:43:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2983469                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0190080661f8bb4b14b524411e8bbaa3d76bacfac7b341f1d7bc07e5f997f27e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2e3b85f85628301a0bce300dee3a6b04195a15ee                         | Address of the contract that produced the log                |
| paymentToken      | VARCHAR   | 0x539bde0d7dbd336b79148aa742883198bbf60342                         |                                                              |
