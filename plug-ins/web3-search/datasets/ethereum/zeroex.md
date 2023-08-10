# zeroex

## 1. Table: Exchange\_v1\_0\_event\_LogCancel\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2018-06-22 06:45:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 5832834                                                            | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x6ac8d2dae9176af211939bf2c1f29ad58ae8dd7d65c01e7e643fe93ad88422eb | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0x12459c951127e0c374ff9105dda097662a027093                         | Address of the contract that produced the log                |
| maker                     | VARCHAR   | 0x05e82be3577dec7b5e6a84dbe0bbb40cfae5589b                         |                                                              |
| feeRecipient              | VARCHAR   | 0x5e150a33ffa97a8d22f59c77ae5487b089ef62e9                         |                                                              |
| makerToken                | VARCHAR   | 0x2859021ee7f2cb10162e67f33af2d22764b31aff                         |                                                              |
| takerToken                | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| cancelledMakerTokenAmount | VARCHAR   | 100000000                                                          |                                                              |
| cancelledTakerTokenAmount | VARCHAR   | 10000000000000000                                                  |                                                              |
| tokens                    | VARCHAR   | 0x1a7affc81362005918063e4bc7588ea00e27d870cb53d32623a35ae4ed530732 |                                                              |
| orderHash                 | VARCHAR   | 0x1e1c51feed7ac98d302f5c4466f757b08ded120c7941fe9517d0e15f3e67db1b |                                                              |

## 2. Table: Exchange\_v1\_0\_event\_LogError\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-06-21 11:25:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5828099                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe131d32df9f0df36244794a6622d9d446376c561a6e47ad640d13ddd34ad92d0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x12459c951127e0c374ff9105dda097662a027093                         | Address of the contract that produced the log                |
| errorId           | VARCHAR   | 0                                                                  |                                                              |
| orderHash         | VARCHAR   | 0x185e602dce9a09dee319b914b3676444f22f629d2451ac6990d9d8cced852dd4 |                                                              |

## 3. Table: Exchange\_v1\_0\_event\_LogFill\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2019-07-18 05:28:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 8172784                                                            | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xabc6a4a5a2c9ee972c918d039cc4943546032c86bf138ab038f21c67d1f6de81 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 137                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x12459c951127e0c374ff9105dda097662a027093                         | Address of the contract that produced the log                |
| maker                  | VARCHAR   | 0x1ff2e262aeca4e06d5a8d0310d5db926701fa442                         |                                                              |
| taker                  | VARCHAR   | 0xf63d69fedcc4486114ae3e667336137576f6c938                         |                                                              |
| feeRecipient           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| makerToken             | VARCHAR   | 0x1de2d8319da51022df2e560acaeb5c2c8b81ccd2                         |                                                              |
| takerToken             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| filledMakerTokenAmount | VARCHAR   | 1                                                                  |                                                              |
| filledTakerTokenAmount | VARCHAR   | 1000000000000000                                                   |                                                              |
| paidMakerFee           | VARCHAR   | 0                                                                  |                                                              |
| paidTakerFee           | VARCHAR   | 0                                                                  |                                                              |
| tokens                 | VARCHAR   | 0x5650f2bbca573f695bd4d76c4198c77127149fa4560221d527f96ed8cad4a414 |                                                              |
| orderHash              | VARCHAR   | 0x37faf8673190fdd3612b68060f2586bc8c9466e731cd4dc9c57f43a37213cad2 |                                                              |

## 4. Table: Exchange\_v2\_0\_event\_AssetProxyRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-09-04 17:47:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6271593                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfe61ce507816a77441839c199bc2c6603fdda3d3034c4194f4894f32f384f413 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f833a24e1f95d70f028921e27040ca56e09ab0b                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xf47261b0                                                         |                                                              |
| assetProxy        | VARCHAR   | 0x2240dab907db71e64d3e0dba4800c83b5c502d4e                         |                                                              |

## 5. Table: Exchange\_v2\_0\_event\_CancelUpTo\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-05 16:41:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8092427                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5f89d26f9292b7d6d2be48b33474734d17fd36a94b2c19cb404f6248438334db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f833a24e1f95d70f028921e27040ca56e09ab0b                         | Address of the contract that produced the log                |
| makerAddress      | VARCHAR   | 0x0f8aa39a58adcc3df98d826ac798ab837cc0833c                         |                                                              |
| senderAddress     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| orderEpoch        | VARCHAR   | 1562344861843                                                      |                                                              |

## 6. Table: Exchange\_v2\_0\_event\_Cancel\_history

| Column              | Type      | Example                                                                    | Description                                                  |
| ------------------- | --------- | -------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2018-11-16 16:46:50+00:00                                                  | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 6716263                                                                    | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x83ed13257ae40eb0ef970f92f8b4d8efc2f56a8a59f2c17db5f42727467c8e1b         | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 74                                                                         | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x4f833a24e1f95d70f028921e27040ca56e09ab0b                                 | Address of the contract that produced the log                |
| makerAddress        | VARCHAR   | 0x02716dc9c0b30b9c7349657069fb3d77e1f3def4                                 |                                                              |
| feeRecipientAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                                 |                                                              |
| senderAddress       | VARCHAR   | 0x02716dc9c0b30b9c7349657069fb3d77e1f3def4                                 |                                                              |
| orderHash           | VARCHAR   | 0x79f480a0908b415ad1150ee510f4735ab6a78e4ebf8a368d7d59f69765b1c74e         |                                                              |
| makerAssetData      | VARCHAR   | 0xf47261b0000000000000000000000000c02aaa39b223fe8d0a0e5c4f27ead9083c756cc2 |                                                              |
| takerAssetData      | VARCHAR   | 0xf47261b00000000000000000000000000d8775f648430679a709e98d2b0cb6250d2887ef |                                                              |

## 7. Table: Exchange\_v2\_0\_event\_Fill\_history

| Column                 | Type      | Example                                                                    | Description                                                  |
| ---------------------- | --------- | -------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2018-12-16 17:27:49+00:00                                                  | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 6898478                                                                    | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x75e3171ca47130d848fff9b60934247f414f7a9291ac77a9752c9c8709da1f12         | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 5                                                                          | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x4f833a24e1f95d70f028921e27040ca56e09ab0b                                 | Address of the contract that produced the log                |
| makerAddress           | VARCHAR   | 0x128b7034b41c3e07ed42ad5d26ca37fd87341411                                 |                                                              |
| feeRecipientAddress    | VARCHAR   | 0x0000000000000000000000000000000000000000                                 |                                                              |
| takerAddress           | VARCHAR   | 0xd2045edc40199019e221d71c0913343f7908d0d5                                 |                                                              |
| senderAddress          | VARCHAR   | 0xd2045edc40199019e221d71c0913343f7908d0d5                                 |                                                              |
| makerAssetFilledAmount | VARCHAR   | 140133000                                                                  |                                                              |
| takerAssetFilledAmount | VARCHAR   | 140124911523240000000                                                      |                                                              |
| makerFeePaid           | VARCHAR   | 0                                                                          |                                                              |
| takerFeePaid           | VARCHAR   | 0                                                                          |                                                              |
| orderHash              | VARCHAR   | 0xb2324eef8aa93f6c8757a8a6f507f224f5d802abd6e53c0513f6eb20c79437b3         |                                                              |
| makerAssetData         | VARCHAR   | 0xf47261b0000000000000000000000000a0b86991c6218b36c1d19d4a2e9eb0ce3606eb48 |                                                              |
| takerAssetData         | VARCHAR   | 0xf47261b000000000000000000000000089d24a6b4ccb1b6faa2625fe562bdd9a23260359 |                                                              |

## 8. Table: Exchange\_v2\_1\_call\_executeTransaction\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-05-05 20:49:18+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14719409                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xcfe4d9f22efad579e9d4274e363dcaca96fc4e624a460d9436071f4942bf3cb5                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,4                                                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x080bf510fcbf18b91105470639e9561022937712                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| salt               | VARCHAR   | 41169815668057528679896548652453087554569716596739191168511965814811749764538                        |                                                                                                                        |
| signerAddress      | VARCHAR   | 0x8d90113a1e286a5ab3e496fbd1853f265e5913c6                                                           |                                                                                                                        |
| data               | VARCHAR   | 0x64a3bc15000000000000000000000000000000000000000000000000000000000000006000000000000000000000000000 |                                                                                                                        |
| signature          | VARCHAR   | 0x                                                                                                   |                                                                                                                        |

## 9. Table: Exchange\_v2\_1\_event\_AssetProxyRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-17 17:10:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8369262                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xde1125f45eabe99a6b41012dd252066025424964485aed9bf2a5f07a229fbb31 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x080bf510fcbf18b91105470639e9561022937712                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xc339d10a                                                         |                                                              |
| assetProxy        | VARCHAR   | 0x3517b88c19508c08650616019062b898ab65ed29                         |                                                              |

## 10. Table: Exchange\_v2\_1\_event\_CancelUpTo\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 04:11:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12726748                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe137956a627678b27c60b1266fa8e25d7d4784bd9269cc8cec8087e8fa73c7d1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 304                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x080bf510fcbf18b91105470639e9561022937712                         | Address of the contract that produced the log                |
| makerAddress      | VARCHAR   | 0xe7dae42dee2bb6c1ef3c65e68d3e605fabca875d                         |                                                              |
| senderAddress     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| orderEpoch        | VARCHAR   | 1624939786541                                                      |                                                              |

## 11. Table: Exchange\_v2\_1\_event\_Cancel\_history

| Column              | Type      | Example                                                                    | Description                                                  |
| ------------------- | --------- | -------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-10-12 00:13:13+00:00                                                  | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 8723505                                                                    | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x0694685054a9a5e98d293b1ead09ab4fd1728e23cfd8157549761db94ad590a0         | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 99                                                                         | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x080bf510fcbf18b91105470639e9561022937712                                 | Address of the contract that produced the log                |
| makerAddress        | VARCHAR   | 0x06e614481c8300020fb82c93d54a6e2e051f49fb                                 |                                                              |
| feeRecipientAddress | VARCHAR   | 0x4524baa98f9a3b9dec57caae7633936ef96bd708                                 |                                                              |
| senderAddress       | VARCHAR   | 0x06e614481c8300020fb82c93d54a6e2e051f49fb                                 |                                                              |
| orderHash           | VARCHAR   | 0x29b56cced706d87aba29b9bb84cf0ad598b03601f11c67fb8edb9187d1ad7232         |                                                              |
| makerAssetData      | VARCHAR   | 0xf47261b0000000000000000000000000a4ec83c8907888d006a37debf755ee39766f38ae |                                                              |
| takerAssetData      | VARCHAR   | 0xf47261b000000000000000000000000086fa049857e0209aa7d9e616f7eb3b3b78ecfdb0 |                                                              |

## 12. Table: Exchange\_v2\_1\_event\_Fill\_history

| Column                 | Type      | Example                                                                                              | Description                                                  |
| ---------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2023-06-01 07:30:59+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 17384492                                                                                             | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xe34fe1fd070b7aa261d9ab93a59fa68e81488ec76407e758b8ef4821b94b71b4                                   | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 170                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x080bf510fcbf18b91105470639e9561022937712                                                           | Address of the contract that produced the log                |
| makerAddress           | VARCHAR   | 0xca26c23a4887a7fb3609cfff5cbfeb1f31be3200                                                           |                                                              |
| feeRecipientAddress    | VARCHAR   | 0x4e2f98c96e2d595a83afa35888c4af58ac343e44                                                           |                                                              |
| takerAddress           | VARCHAR   | 0xa706082f3edb8c3638ca8fa214b9083620e23d55                                                           |                                                              |
| senderAddress          | VARCHAR   | 0xa706082f3edb8c3638ca8fa214b9083620e23d55                                                           |                                                              |
| makerAssetFilledAmount | VARCHAR   | 1                                                                                                    |                                                              |
| takerAssetFilledAmount | VARCHAR   | 1                                                                                                    |                                                              |
| makerFeePaid           | VARCHAR   | 0                                                                                                    |                                                              |
| takerFeePaid           | VARCHAR   | 0                                                                                                    |                                                              |
| orderHash              | VARCHAR   | 0x1a3d3337b4f1bd9203d1bf410eca0845458affbda6d0e47e86a19aea5607b2a4                                   |                                                              |
| makerAssetData         | VARCHAR   | 0x94cfcdd7000000000000000000000000000000000000000000000000000000000000004000000000000000000000000000 |                                                              |
| takerAssetData         | VARCHAR   | 0x94cfcdd7000000000000000000000000000000000000000000000000000000000000004000000000000000000000000000 |                                                              |

## 13. Table: Exchange\_v3\_0\_event\_AssetProxyRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-17 19:03:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8952147                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfece293adade681c11731ea77ff88775c5b28af48b8101f6be96b9818c21c540 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x61935cbdd02287b511119ddb11aeb42f1593b7ef                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 0xf47261b0                                                         |                                                              |
| assetProxy        | VARCHAR   | 0x95e6f48254609a6ee006f7d493c8e5fb97094cef                         |                                                              |

## 14. Table: Exchange\_v3\_0\_event\_CancelUpTo\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2020-04-21 23:19:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 9918721                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x0c65fc011a563373656f19e6de0c89bb32490804b3cd5f7a6b87e308f49ab4b5 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x61935cbdd02287b511119ddb11aeb42f1593b7ef                         | Address of the contract that produced the log                |
| makerAddress       | VARCHAR   | 0x0f8aa39a58adcc3df98d826ac798ab837cc0833c                         |                                                              |
| orderSenderAddress | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| orderEpoch         | VARCHAR   | 1587511150184                                                      |                                                              |

## 15. Table: Exchange\_v3\_0\_event\_Cancel\_history

| Column              | Type      | Example                                                                                              | Description                                                  |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-03-25 07:51:23+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 14454182                                                                                             | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x38908cbfb209a1b5cfed1a0183cd7b4061d6400a5751166deb99fe826380d5f2                                   | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 47                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x61935cbdd02287b511119ddb11aeb42f1593b7ef                                                           | Address of the contract that produced the log                |
| makerAddress        | VARCHAR   | 0x5fcb773c93e8d72a00a8510cd7d8f53a31a45f19                                                           |                                                              |
| feeRecipientAddress | VARCHAR   | 0xb60922d30d595fc1ea9baa46df2891c0fb3d8dfc                                                           |                                                              |
| makerAssetData      | VARCHAR   | 0x02571792000000000000000000000000c9154424b823b10579895ccbe442d41b9abd96edb60922d30d595fc1ea9baa46df |                                                              |
| takerAssetData      | VARCHAR   | 0xf47261b0000000000000000000000000c02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                           |                                                              |
| senderAddress       | VARCHAR   | 0x5fcb773c93e8d72a00a8510cd7d8f53a31a45f19                                                           |                                                              |
| orderHash           | VARCHAR   | 0x22f9fb5a76340183b4241f761a43fb3cb287a4d3b53202cbaa9b339b58f0b669                                   |                                                              |

## 16. Table: Exchange\_v3\_0\_event\_Fill\_history

| Column                 | Type      | Example                                                                    | Description                                                  |
| ---------------------- | --------- | -------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-06-29 14:03:26+00:00                                                  | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 12729368                                                                   | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x8a0137cc421243fb086b5741fcc475e2f692dcd8fbddaa33375dac8bdd035f0a         | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 55                                                                         | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x61935cbdd02287b511119ddb11aeb42f1593b7ef                                 | Address of the contract that produced the log                |
| makerAddress           | VARCHAR   | 0x13bb0ae230504a389989fd00df6dae9e2a873d5e                                 |                                                              |
| feeRecipientAddress    | VARCHAR   | 0x0000000000000000000000000000000000000000                                 |                                                              |
| makerAssetData         | VARCHAR   | 0xf47261b0000000000000000000000000c02aaa39b223fe8d0a0e5c4f27ead9083c756cc2 |                                                              |
| takerAssetData         | VARCHAR   | 0xf47261b00000000000000000000000006b175474e89094c44da98b954eedeac495271d0f |                                                              |
| makerFeeAssetData      | VARCHAR   | 0x                                                                         |                                                              |
| takerFeeAssetData      | VARCHAR   | 0x                                                                         |                                                              |
| orderHash              | VARCHAR   | 0x6d0af99b42c9fd9e9ef63238e18fa4214456acfbf5eb1e6deb336fdac07d0495         |                                                              |
| takerAddress           | VARCHAR   | 0x000000000000006f6502b7f2bbac8c30a3f67e9a                                 |                                                              |
| senderAddress          | VARCHAR   | 0x000000000000006f6502b7f2bbac8c30a3f67e9a                                 |                                                              |
| makerAssetFilledAmount | VARCHAR   | 10023499045334719416                                                       |                                                              |
| takerAssetFilledAmount | VARCHAR   | 22240367245306053801584                                                    |                                                              |
| makerFeePaid           | VARCHAR   | 0                                                                          |                                                              |
| takerFeePaid           | VARCHAR   | 0                                                                          |                                                              |
| protocolFeePaid        | VARCHAR   | 3360000000000000                                                           |                                                              |

## 17. Table: Exchange\_v3\_0\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-29 23:44:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9023765                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80d6701d25e9dcc54c3578a5585f5ac4562a445359d9af868fbc130914783016 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x61935cbdd02287b511119ddb11aeb42f1593b7ef                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x3b39078f2a3e1512eecc8d6792fdc7f33e1cd2cf                         |                                                              |
| newOwner          | VARCHAR   | 0x7d3455421bbc5ed534a83c88fd80387dc8271392                         |                                                              |

## 18. Table: Exchange\_v3\_0\_event\_ProtocolFeeCollectorAddress\_history

| Column                      | Type      | Example                                                            | Description                                                  |
| --------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP | 2019-11-17 20:58:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER   | 8952583                                                            | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR   | 0xab47abd6617e16b1869ed671707cd28ec6af55559ef5e8472d6d11c3f50beb66 | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR   | 0x61935cbdd02287b511119ddb11aeb42f1593b7ef                         | Address of the contract that produced the log                |
| oldProtocolFeeCollector     | VARCHAR   | 0x9c427e553a1754ed39a61df90c1d6d7ff6f7ce12                         |                                                              |
| updatedProtocolFeeCollector | VARCHAR   | 0xa26e80e7dea86279c6d778d702cc413e6cffa777                         |                                                              |

## 19. Table: Exchange\_v3\_0\_event\_ProtocolFeeMultiplier\_history

| Column                       | Type      | Example                                                            | Description                                                  |
| ---------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp             | TIMESTAMP | 2019-11-17 19:02:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                | INTEGER   | 8952145                                                            | The block number where this event was emitted                |
| transaction\_hash            | VARCHAR   | 0x08ce4a6e5c625d079f28467af3d338e233d9dd5f39d7cc8e1f21a2df0220b0c5 | Hash of the transactions in which this event was emitted     |
| log\_index                   | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address            | VARCHAR   | 0x61935cbdd02287b511119ddb11aeb42f1593b7ef                         | Address of the contract that produced the log                |
| oldProtocolFeeMultiplier     | VARCHAR   | 0                                                                  |                                                              |
| updatedProtocolFeeMultiplier | VARCHAR   | 150000                                                             |                                                              |

## 20. Table: Exchange\_v3\_0\_event\_TransactionExecution\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-16 08:47:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9493114                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x700d3f97b42f0709c50bd30546093c3bd701eef9672c77f6507496d7f47bdfdf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x61935cbdd02287b511119ddb11aeb42f1593b7ef                         | Address of the contract that produced the log                |
| transactionHash   | VARCHAR   | 0xac0fd1155145021bc0aa6ae6421610400a2c68c7ea88aaca9093dfc475ffd17f |                                                              |

## 21. Table: Exchange\_v4\_0\_event\_ERC1155OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-18 14:06:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14799264                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8bbc27dc7286a219acb668f8de8e7093ddac29d37e2eb5d2370599f34a8755c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 63                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x0a3d11162e55109232deda35d703b2ce4b1f0e22                         | The maker of the order.                                      |
| nonce             | VARCHAR   | 1652839516120                                                      | The nonce of the order that was cancelled.                   |

## 22. Table: Exchange\_v4\_0\_event\_ERC1155OrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-19 03:59:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16216210                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8af4b489b9d304e3364c94053ef04fa0c2bb43d6f3bb80b1f0974df6ff32d544 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 76                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         | Address of the contract that produced the log                |
| direction         | VARCHAR   | 0                                                                  | Whether the order is selling or buying the ERC1155 token.    |
| maker             | VARCHAR   | 0x0dbdd4420560dbd239de62a0dacec15e5f9b13c4                         | The maker of the order.                                      |
| taker             | VARCHAR   | 0xc154dec1d80f94ae67576c35877286251d4144c5                         | The taker of the order.                                      |
| nonce             | VARCHAR   | 1671110136706                                                      | The unique maker nonce in the order.                         |
| erc20Token        | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         | The address of the ERC20 token.                              |
| erc20FillAmount   | VARCHAR   | 90000000000000                                                     | The amount of ERC20 token filled.                            |
| erc1155Token      | VARCHAR   | 0x99a6163b390a2b06b99b93a1829b55c5793d0fdf                         | The address of the ERC1155 token.                            |
| erc1155TokenId    | VARCHAR   | 28                                                                 | The ID of the ERC1155 asset.                                 |
| erc1155FillAmount | VARCHAR   | 1                                                                  | The amount of ERC1155 asset filled.                          |
| matcher           | VARCHAR   | 0x0000000000000000000000000000000000000000                         | Currently unused.                                            |

## 23. Table: Exchange\_v4\_0\_event\_ERC721OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-12 20:27:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14572934                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4e21eb80adc58f0eed403d65d54f4f183c2381355f11fe9347edfe74093e276 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         | Address of the contract that produced the log                |
| maker             | VARCHAR   | 0x4e5e60fb2dae775c7c3a91db58e8700e05825042                         | The maker of the order.                                      |
| nonce             | VARCHAR   | 1649792460572                                                      | The nonce of the order that was cancelled.                   |

## 24. Table: Exchange\_v4\_0\_event\_ERC721OrderFilled\_history

| Column            | Type      | Example                                                            | Description                                                                                                                                    |
| ----------------- | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp  | TIMESTAMP | 2023-02-17 11:08:11+00:00                                          | Timestamp of the block where this event was emitted                                                                                            |
| block\_number     | INTEGER   | 16648038                                                           | The block number where this event was emitted                                                                                                  |
| transaction\_hash | VARCHAR   | 0xb718380d584ab5c57f40d6b6c01f8917820deb52eb119311558570218ab58a7c | Hash of the transactions in which this event was emitted                                                                                       |
| log\_index        | INTEGER   | 68                                                                 | Integer of the log index position in the block of this event                                                                                   |
| contract\_address | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         | Address of the contract that produced the log                                                                                                  |
| direction         | VARCHAR   | 0                                                                  | Whether the order is selling or buying the ERC721 token.                                                                                       |
| maker             | VARCHAR   | 0x118ee757dd8841f81903e1c1d7d7aa88e376cc39                         | The maker of the order                                                                                                                         |
| taker             | VARCHAR   | 0x3e9a8f4ec87bc9e2170688c593f42b2934b92f71                         | The taker of the order                                                                                                                         |
| nonce             | VARCHAR   | 227648463280172197287870538270184661753                            | The unique maker nonce in the order.                                                                                                           |
| erc20Token        | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         | The address of the ERC20 token.                                                                                                                |
| erc20TokenAmount  | VARCHAR   | 190000000000000                                                    | The amount of ERC20 token to sell or buy.                                                                                                      |
| erc721Token       | VARCHAR   | 0xe362e7265aebc0dd25c1eb7de339692c20a869b0                         | The address of the ERC721 token.                                                                                                               |
| erc721TokenId     | VARCHAR   | 239                                                                | The ID of the ERC721 asset.                                                                                                                    |
| matcher           | VARCHAR   | 0x0000000000000000000000000000000000000000                         | If this order was matched with another using `matchERC721Orders()`, this will be the address of the caller. If not, this will be `address(0)`. |

## 25. Table: Exchange\_v4\_0\_event\_LimitOrderFilled\_history

| Column                    | Type      | Example                                                            | Description                                                  |
| ------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2022-09-18 19:00:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 15562377                                                           | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0xa54fc8fa9ee1b2e815ce8eec26d08eb3e7f55e9f3ed80a06fa1f3b046669511f | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         | Address of the contract that produced the log                |
| orderHash                 | VARCHAR   | 0xc3e476f6d1a2f942cbe6f223f1032e2846f9c83721451eb4fe46e62a91f9021f |                                                              |
| maker                     | VARCHAR   | 0x1321e7ceffdb1d83f65a1c882af23925def42092                         |                                                              |
| taker                     | VARCHAR   | 0x00000000c2cf7648c169b25ef1c217864bfa38cc                         |                                                              |
| feeRecipient              | VARCHAR   | 0x86003b044f70dac0abc80ac8957305b6370893ed                         |                                                              |
| makerToken                | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| takerToken                | VARCHAR   | 0x00c2999c8b2adf4abc835cc63209533973718eb1                         |                                                              |
| takerTokenFilledAmount    | VARCHAR   | 2342579915317924797758832640                                       |                                                              |
| makerTokenFilledAmount    | VARCHAR   | 398238585                                                          |                                                              |
| takerTokenFeeFilledAmount | VARCHAR   | 0                                                                  |                                                              |
| protocolFeePaid           | VARCHAR   | 0                                                                  |                                                              |
| pool                      | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |

## 26. Table: Exchange\_v4\_0\_event\_LiquidityProviderSwap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 11:15:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17385597                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa8a898fbf24b65077b4e0debe91eb85ee489a54c2b3b8b72cb6cbb77a5272b67 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 279                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         | Address of the contract that produced the log                |
| inputToken        | VARCHAR   | 0x99d8a9c45b2eca8864373a26d1459e3dff1e17f3                         |                                                              |
| outputToken       | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| inputTokenAmount  | VARCHAR   | 28056224206866227712000                                            |                                                              |
| outputTokenAmount | VARCHAR   | 28025949690736130997698                                            |                                                              |
| provider          | VARCHAR   | 0x561b94454b65614ae3db0897b74303f4acf7cc75                         |                                                              |
| recipient         | VARCHAR   | 0x93652ae25d0ba757c3c92a4deb0b05dd1d4efe35                         |                                                              |

## 27. Table: Exchange\_v4\_0\_event\_OtcOrderFilled\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-09-18 21:09:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 15563013                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x395aff4f7f520b9506a861cdf676f40f2f2229310435fb07f08509c1f0657bbb | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         | Address of the contract that produced the log                |
| orderHash              | VARCHAR   | 0x313b4352cc111cbf4c92954966fa6285adf75260baa30e56e2b3fd7539e52f10 |                                                              |
| maker                  | VARCHAR   | 0x00000000ae347930bd1e7b0f35588b92280f9e75                         |                                                              |
| taker                  | VARCHAR   | 0x2333fcc3833d2e951ce8e821235ed3b729141996                         |                                                              |
| makerToken             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| takerToken             | VARCHAR   | 0x1f9840a85d5af5bf1d1762f925bdaddc4201f984                         |                                                              |
| makerTokenFilledAmount | VARCHAR   | 235302767950462304                                                 |                                                              |
| takerTokenFilledAmount | VARCHAR   | 56272457070144292883                                               |                                                              |

## 28. Table: Exchange\_v4\_0\_event\_RfqOrderFilled\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2021-05-26 05:29:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 12508096                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x9e6238a710f24d17f640c8ab281d7499af99e20e09937a58cff08acfc551d59a | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 146                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         | Address of the contract that produced the log                |
| orderHash              | VARCHAR   | 0x7e186f61032f93557221a4a4ba8d26a841137b6b8a8703b28be65a2bf0caa489 |                                                              |
| maker                  | VARCHAR   | 0x0000006daea1723962647b7e189d311d757fb793                         |                                                              |
| taker                  | VARCHAR   | 0x22f9dcf4647084d6c31b2765f6910cd85c178c18                         |                                                              |
| makerToken             | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| takerToken             | VARCHAR   | 0xba11d00c5f74255f56a5e366f4f77f5a186d7f55                         |                                                              |
| takerTokenFilledAmount | VARCHAR   | 4461095686073492451218                                             |                                                              |
| makerTokenFilledAmount | VARCHAR   | 14019655766588106430                                               |                                                              |
| pool                   | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
