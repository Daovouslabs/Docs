# decentraland

## 1. Table: Marketplace\_event\_AuctionSuccessful\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-27 14:35:05+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8822152                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c50123eb73ca473f97ecd2d65fbcc9f21602f9b9af2b36e7188939c2141449e             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3bca6f5052c7e24726b44da7403b56a8a1b98f8                                     | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x83d511509afea83bd4997f466c8e01f88243eff7f360b4aca356c824227114af             |                                                              |
| assetId           | VARCHAR   | 115792089237316195423570985008687907843061513658012410135556345784960083296204 |                                                              |
| seller            | VARCHAR   | 0x7bbd3ad2cad123c3991670e52634b6d620048c28                                     |                                                              |
| totalPrice        | VARCHAR   | 45000000000000000000000                                                        |                                                              |
| winner            | VARCHAR   | 0xf68ed19598a05fbbafdafec65cb05e1fa4b5f97b                                     |                                                              |

## 2. Table: Marketplace\_event\_OrderSuccessful\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-04 05:07:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9047579                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfad44ee1a8ddac8fc0a2cb32567538a5f128805246769a7b56022fa415f13447 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 27                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8e5660b4ab70168b5a6feea0e0315cb49c8cd539                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0x1ef9fea8f270f7333e2a8408c9b2a169cf18ccd292d654f34c0969743c8cf1c3 |                                                              |
| assetId           | VARCHAR   | 3062541302288446171170371466885913903128                           |                                                              |
| seller            | VARCHAR   | 0xf68ed19598a05fbbafdafec65cb05e1fa4b5f97b                         |                                                              |
| nftAddress        | VARCHAR   | 0xf87e31492faf9a91b02ee0deaad50d51d56d5d4d                         |                                                              |
| totalPrice        | VARCHAR   | 20999000000000000000000                                            |                                                              |
| buyer             | VARCHAR   | 0x3534baa62caab80824ad5584579fce4fe9f7a789                         |                                                              |
