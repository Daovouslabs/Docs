# mintable

## 1. Table: MintableExchange\_event\_NFTSold\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2020-12-08 12:20:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 11412115                                                           | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x99f7e683b3c0c424985f69dd2156feb83b12e2140d87d0fa3611849d72564c12 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 223                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x974b10a997de02e2c14c439f95eeaa58090a0ca1                         | Address of the contract that produced the log                |
| \_contract\_address | VARCHAR   | 0x9201a886740d193e315f1f1b2b193321d6701d07                         |                                                              |
| tokenId             | VARCHAR   | 43                                                                 |                                                              |
| buyer               | VARCHAR   | 0x02a522d98ec2d2c3bbe91acc29ee7fd32ab880ab                         |                                                              |
| seller              | VARCHAR   | 0x500364d2bbdc7ca29c9b936b0877d3d1d1f47594                         |                                                              |

## 2. Table: MintableExchange\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 3. Table: MintableNFT\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-17 00:54:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12448840                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcf267d1873d9e6b3816e81c5dce5dde6e5d0016d308a1e73d4944ec2c8ea3f5e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 300                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c5acf6dbd24c66e6fd44d4a4c3d7a2d955aaad2                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xeb865dd1fee2a11bd9767e0e2d52cf89ada64aba                         |                                                              |
| operator          | VARCHAR   | 0x4fee7b061c97c9c496b01dbce9cdb10c02f0a0be                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 4. Table: MintableNFT\_event\_Approval\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-04 07:50:07+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13937753                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa7dab93720c8b55632f19b9c9350b9d0b9a30bf27e0ab9f582eb285d42ef9fd5            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 231                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c5acf6dbd24c66e6fd44d4a4c3d7a2d955aaad2                                    | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x7abca3cbc8aa182d10f742f72e2e8bc68c4a8839                                    |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                                    |                                                              |
| tokenId           | VARCHAR   | 27964339865592756430076624915131963380151013737351769051234987370060600349557 |                                                              |

## 5. Table: MintableNFT\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-20 02:41:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11689631                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0995376d857bf444f5da7a7d27fdc1be12d518231136a27d3dec69c4a712b2ae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c5acf6dbd24c66e6fd44d4a4c3d7a2d955aaad2                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x02a522d98ec2d2c3bbe91acc29ee7fd32ab880ab                         |                                                              |

## 6. Table: MintableNFT\_event\_RecievedRoyalties\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| creator           | VARCHAR   |                                                              |             |
| buyer             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 7. Table: MintableNFT\_event\_SeriesMade\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| creator           | VARCHAR   |                                                              |             |
| price             | VARCHAR   |                                                              |             |
| amount\_made      | VARCHAR   |                                                              |             |

## 8. Table: MintableNFT\_event\_SeriesPurchased\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| buyer             | VARCHAR   |                                                              |             |
| token\_id         | VARCHAR   |                                                              |             |
| price             | VARCHAR   |                                                              |             |

## 9. Table: MintableNFT\_event\_TransferFee\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| to                | VARCHAR   |                                                              |             |
| fee               | VARCHAR   |                                                              |             |

## 10. Table: MintableNFT\_event\_TransferPayment\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 11. Table: MintableNFT\_event\_Transfer\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 23:01:16+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15323463                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa236b640545c29543cfbb2931f0880bc8c186f6bf9e5bdc233f90433b25034c3            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c5acf6dbd24c66e6fd44d4a4c3d7a2d955aaad2                                    | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x8cd983c839053cfa00f63cba4fdb0f5c55210142                                    |                                                              |
| to                | VARCHAR   | 0x480d8600b0b2d0e2b772eb68f25d32c7e6d91b7b                                    |                                                              |
| tokenId           | VARCHAR   | 63708114141479922257155156246030295845183310287355417599556337928551232073794 |                                                              |
