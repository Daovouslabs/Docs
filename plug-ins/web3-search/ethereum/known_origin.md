# known\_origin

## 1. Table: KODAV3PrimaryMarketplace\_event\_BuyNowPurchased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 21:50:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15920945                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4fedfab13dd966b34916299b58cae9030e44f8d2206e357ad2484b444e356caf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf11ed77fd65840b64602526ddc38311e9923c81b                         | Address of the contract that produced the log                |
| \_tokenId         | VARCHAR   | 22990014                                                           |                                                              |
| \_buyer           | VARCHAR   | 0xfad4b6298544970540f87d70f459b7a345e0699a                         |                                                              |
| \_currentOwner    | VARCHAR   | 0x3f0cb5cb6069d93243079010dc23813d67208424                         |                                                              |
| \_price           | VARCHAR   | 1000000000000000                                                   |                                                              |

## 2. Table: KODAV3PrimaryMarketplace\_event\_EditionBidAccepted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-11 16:12:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13595900                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xce6e249583e55f59959522ce58f6471806ce3326ada74258384fbcb1fdac3682 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 296                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf11ed77fd65840b64602526ddc38311e9923c81b                         | Address of the contract that produced the log                |
| \_editionId       | VARCHAR   | 4108000                                                            |                                                              |
| \_tokenId         | VARCHAR   | 4108000                                                            |                                                              |
| \_bidder          | VARCHAR   | 0xb00cc17dd23d95dae2eb49140b324fed42fb9d2c                         |                                                              |
| \_amount          | VARCHAR   | 5000000000000000000                                                |                                                              |

## 3. Table: KODAV3SecondaryMarketplace\_event\_BuyNowPurchased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-11 22:40:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16608564                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x66efbbdcf588233f2a021ce360e3a89319866604489193e54523370c02cc355d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0eb65b4c3d3de340e1b15384f8f211784247a37a                         | Address of the contract that produced the log                |
| \_tokenId         | VARCHAR   | 23869004                                                           |                                                              |
| \_buyer           | VARCHAR   | 0x80aa186f646fa560495c4e965aa983b958a47369                         |                                                              |
| \_currentOwner    | VARCHAR   | 0x05d222a877028d6966469bbc3b60f1af8590ffea                         |                                                              |
| \_price           | VARCHAR   | 90000000000000000                                                  |                                                              |

## 4. Table: KODAV3SecondaryMarketplace\_event\_EditionBidAccepted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_editionId       | VARCHAR   |                                                              |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_bidder          | VARCHAR   |                                                              |             |
| \_amount          | VARCHAR   |                                                              |             |

## 5. Table: KnownOriginDigitalAssetV2\_event\_Purchase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-18 08:31:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14409352                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe37fd7659a32430379c3899547870685f018f740c75ff33e6eae9612fffda09 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfbeef911dc5821886e1dda71586d90ed28174b7d                         | Address of the contract that produced the log                |
| \_tokenId         | VARCHAR   | 564204                                                             |                                                              |
| \_editionNumber   | VARCHAR   | 564200                                                             |                                                              |
| \_buyer           | VARCHAR   | 0x0305f3ecec1b0f6a2a181c9747fe914b3f20958a                         |                                                              |
| \_priceInWei      | VARCHAR   | 90000000000000000                                                  |                                                              |

## 6. Table: KnownOriginDigitalAssetV3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-07 10:32:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14158417                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x04fd83385ab42ded5828c7ffd6c1c7cbf95252ab04c8313d67423c17f73c157d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 343                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xabb3738f04dc2ec20f4ae4462c3d069d02ae045b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x38feeadebea93923ebb00ae215984248dad44874                         |                                                              |
| tokenId           | VARCHAR   | 6878000                                                            |                                                              |
