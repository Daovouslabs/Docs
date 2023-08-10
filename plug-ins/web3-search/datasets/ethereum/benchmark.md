# benchmark

## 1. Table: Benchmark\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-19 21:14:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12071545                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4c4ad1e00134bfc4b244cb70ff16d38ac52e931a0a5a7ec9841d6f29374211be | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x67c597624b17b16fb77959217360b7cd18284253                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x0000000089341e263b85d84a0eea39f47c37a9d2                         |                                                              |
| \_spender         | VARCHAR   | 0x049c586132110f6551d758deb50a7c984fc0ec59                         |                                                              |
| \_value           | VARCHAR   | 2333757918802                                                      |                                                              |

## 2. Table: Benchmark\_event\_LogNewRebaseOracle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-21 17:05:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12478923                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa417d81a811169c0c2964812ca728168c1680e37586703e60ce3df6b2d210fab | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 286                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x67c597624b17b16fb77959217360b7cd18284253                         | Address of the contract that produced the log                |
| \_rebaseOracle    | VARCHAR   | 0x67c597624b17b16fb77959217360b7cd18284253                         |                                                              |

## 3. Table: Benchmark\_event\_LogRebase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 22:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11850932                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc67e9d7bc6ac1d9477b4c0171c66ad060bb90e0c0201d95bab8e31238e60d6d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x67c597624b17b16fb77959217360b7cd18284253                         | Address of the contract that produced the log                |
| \_totalSupply     | VARCHAR   | 92823195371505868                                                  |                                                              |

## 4. Table: Benchmark\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-17 23:43:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11278475                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcfbc6078995b1bbde049e04b65fa4e796b0af700f7ee9704b040e42918d3a326 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x67c597624b17b16fb77959217360b7cd18284253                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0xa77364249507f3e55cfb1143e139f931dcc00e9e                         |                                                              |
| \_to              | VARCHAR   | 0x044fd46fd79fbb2bf152c9bf1c39d7aa7259879f                         |                                                              |

## 5. Table: Benchmark\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-10 07:05:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13775926                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7fb9d5d5fed5296237f011fff2790b89cfa12a5603df1f71c898d4827b944d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 304                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x67c597624b17b16fb77959217360b7cd18284253                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x7a250d5630b4cf539739df2c5dacb4c659f2488d                         |                                                              |
| \_to              | VARCHAR   | 0x08506b9da092133b8680b601a917d64e416d3e42                         |                                                              |
| \_value           | VARCHAR   | 95849632498                                                        |                                                              |
