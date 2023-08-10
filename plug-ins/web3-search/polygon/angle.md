# angle

## 1. Table: ANGLE\_call\_deposit\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| user               | VARCHAR   |                                                                                                                        |             |
| depositData        | VARCHAR   |                                                                                                                        |             |

## 2. Table: ANGLE\_call\_transferFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-29 18:30:36+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 43298197                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x52ed6a60bb76016b7223689b5533ff452737e95577c39a4e13bd93487d797566 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 47                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x900f717ea076e1e7a484ad9dd2db81ceec60ebf1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| sender             | VARCHAR   | 0x71976ae069fdc8e81ad70294cbb6973a5ce5683f                         |                                                                                                                        |
| recipient          | VARCHAR   | 0xbf1ac395731307e83cbf1901957ed0a4faa15a02                         |                                                                                                                        |
| amount             | VARCHAR   | 33735179656633287064                                               |                                                                                                                        |

## 3. Table: ANGLE\_call\_transfer\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-14 20:49:58+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 35610480                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc87c09001a2df7c6dd42bd571b91ea78e9d7803194f395b3bc4ad6a9cca0f774 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 26                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x900f717ea076e1e7a484ad9dd2db81ceec60ebf1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| recipient          | VARCHAR   | 0xa15649ac5d4dc553030de9c0d8aa042d99fc68fa                         |                                                                                                                        |
| amount             | VARCHAR   | 980163563560130944                                                 |                                                                                                                        |

## 4. Table: ANGLE\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-09 06:44:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 31686089                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7bb03e0ffac34bf1dfd3d2bb4dda835e4489bb27cad894112a9f16e0666a7342 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 86                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x900f717ea076e1e7a484ad9dd2db81ceec60ebf1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 361812274505012316000                                              |                                                                                                                        |

## 5. Table: ANGLE\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 16:45:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34748621                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdfc22ac64b1544b4b167ec5ba56d97be70c046c5932d4af1ec2c597049704018 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x900f717ea076e1e7a484ad9dd2db81ceec60ebf1                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3477d80484f494fc65cc424a360b4151efc2c862                         |                                                              |
| to                | VARCHAR   | 0x5ffc0e014350207a403005e3946a45f631671a9c                         |                                                              |
| value             | VARCHAR   | 1410946847199846228000                                             |                                                              |

## 6. Table: AngleRouterV1\_call\_changeAllowance\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| tokens             | VARCHAR   |                                                                                                                        |             |
| spenders           | VARCHAR   |                                                                                                                        |             |
| amounts            | VARCHAR   |                                                                                                                        |             |

## 7. Table: AngleRouterV1\_call\_claimRewards\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| gaugeUser          | VARCHAR   |                                                                                                                        |             |
| liquidityGauges    | VARCHAR   |                                                                                                                        |             |

## 8. Table: AngleRouterV1\_call\_mixerVaultManagerPermit\_history

| Column                   | Type      | Example                                                                                                                | Description |
| ------------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp         | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number            | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash        | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index       | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address           | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address              | VARCHAR   | Address of the called contract                                                                                         |             |
| status                   | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error                    | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| paramsPermitVaultManager | VARCHAR   |                                                                                                                        |             |
| paramsPermit             | VARCHAR   |                                                                                                                        |             |
| actions                  | VARCHAR   |                                                                                                                        |             |
| data                     | VARCHAR   |                                                                                                                        |             |

## 9. Table: AngleRouterV1\_call\_mixer\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-07-05 14:14:07+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 30368642                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2c35bf086461d73510b0fac7e70f1b5f74f845e4b1f3b582e482936f1705b4bc                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 60                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x892bf71463bd9fa57f3c2266ab74dbe1b96decea                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| paramsPermit       | VARCHAR   |                                                                                                      |                                                                                                                        |
| actions            | VARCHAR   | 2,13                                                                                                 |                                                                                                                        |
| data               | VARCHAR   | 0x,0x0000000000000000000000000d500b1d8e8ef31e21c99d1db9a6444d3adf12700000000000000000000000004b81f51 |                                                                                                                        |

## 10. Table: AngleRouterV1\_event\_CoreUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_core            | VARCHAR   |                                                              |             |

## 11. Table: AngleRouterV2\_call\_changeAllowance\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| tokens             | VARCHAR   |                                                                                                                        |             |
| spenders           | VARCHAR   |                                                                                                                        |             |
| amounts            | VARCHAR   |                                                                                                                        |             |

## 12. Table: AngleRouterV2\_call\_claimRewards\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| gaugeUser          | VARCHAR   |                                                                                                                        |             |
| liquidityGauges    | VARCHAR   |                                                                                                                        |             |

## 13. Table: AngleRouterV2\_call\_mixerVaultManagerPermit\_history

| Column                   | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp         | TIMESTAMP | 2023-01-12 15:45:40+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number            | INTEGER   | 37990169                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash        | VARCHAR   | 0x79c598612cb108132550b6f4e958c0ff752e893fb38b1262a98dd3e15c623aea                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index       | INTEGER   | 33                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address           | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address              | VARCHAR   | 0x595ab88628cd1af06706e25f10c485b651c47aa8                                                           | Address of the called contract                                                                                         |
| status                   | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                    | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| paramsPermitVaultManager | VARCHAR   | 0xfB16d8e96C0C6e9B72541BFd8D4C3D9e867c990b,0xd213e6F654bc06F76a46261BA1e66cdd1dC71583,true,167354192 |                                                                                                                        |
| paramsPermit             | VARCHAR   |                                                                                                      |                                                                                                                        |
| actions                  | VARCHAR   | 1,6,9                                                                                                |                                                                                                                        |
| data                     | VARCHAR   | 0x,0x0000000000000000000000000d500b1d8e8ef31e21c99d1db9a6444d3adf12700000000000000000000000000000000 |                                                                                                                        |

## 14. Table: AngleRouterV2\_call\_mixer\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-13 21:28:13+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 42668962                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xd8851dcb1f7dc3b41414a347da361af671030064650630d6c79ff3e962b91133                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 49                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x595ab88628cd1af06706e25f10c485b651c47aa8                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| paramsPermit       | VARCHAR   |                                                                                                      |                                                                                                                        |
| actions            | VARCHAR   | 1,6,9                                                                                                |                                                                                                                        |
| data               | VARCHAR   | 0x,0x0000000000000000000000000d500b1d8e8ef31e21c99d1db9a6444d3adf12700000000000000000000000000000000 |                                                                                                                        |

## 15. Table: AngleRouterV2\_call\_setCore\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| \_core             | VARCHAR   |                                                                                                                        |             |

## 16. Table: Angle\_amDAIamUSDCamUSDT\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-05 19:17:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36466360                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf857f03da7907bfb8c04b1525fcf3d76b41e1b5d1f0fff653462fd778217e84b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 578                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe1bc17f85d54a81068fc510d5a94e95800d342d9                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x595ab88628cd1af06706e25f10c485b651c47aa8                         |                                                              |
| to                | VARCHAR   | 0x595ab88628cd1af06706e25f10c485b651c47aa8                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000                                                |                                                              |

## 17. Table: Angle\_amDAIamUSDCamUSDT\_event\_Recovered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 18. Table: Angle\_amDAIamUSDCamUSDT\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-20 15:04:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37061694                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6239f9dbc7d90bdb7de3986d4dda8b5a00d7208f193fb5781b24e42af29f4357 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 354                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe1bc17f85d54a81068fc510d5a94e95800d342d9                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x661e9287a011cc2335cf9af9142bcc77fb44bd9a                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 100000000000000000                                                 |                                                              |

## 19. Table: Angle\_amDAIamUSDCamUSDT\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-23 13:54:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37180346                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4103bf5932bb4bc8bbfb4e977ffbd198ba05b3edf60966f07cd1744a868d3e38 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe1bc17f85d54a81068fc510d5a94e95800d342d9                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x661e9287a011cc2335cf9af9142bcc77fb44bd9a                         |                                                              |
| to                | VARCHAR   | 0x661e9287a011cc2335cf9af9142bcc77fb44bd9a                         |                                                              |
| amount            | VARCHAR   | 674746831760445866                                                 |                                                              |

## 20. Table: LayerZeroagEUR\_call\_burn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-07-25 13:22:42+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 31123175                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x93cc9d86742e858b2e971baebabd9b49c2a3fce120ec120e78185b777f58566c | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 48                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,0,2                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 50000000000000000000000                                            |                                                                                                                        |

## 21. Table: LayerZeroagEUR\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-29 18:10:52+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 43297644                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8999cd3dbd3618e73933163df5bc83486d84054adb906219426e92e56bd3216b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 69                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 1000                                                               |                                                                                                                        |

## 22. Table: LayerZeroagEUR\_call\_transferFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-07 04:16:42+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 43622109                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbc8e546483869e4622e3d323e2ff40bb7306b67b23269f604b90eb9fbd681781 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,1,0,0,0,0,0,0,1                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| sender             | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         |                                                                                                                        |
| recipient          | VARCHAR   | 0xe0b52e49357fd4daf2c15e02058dce6bc0057db4                         |                                                                                                                        |
| amount             | VARCHAR   | 1298943155025116063                                                |                                                                                                                        |

## 23. Table: LayerZeroagEUR\_call\_transfer\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-31 13:05:22+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 35027539                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8089b86f3609d30041ef276a85b85035d5e89943c9cd01cd59415e608bdbd0a4 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 57                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1,0,0                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| recipient          | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         |                                                                                                                        |
| amount             | VARCHAR   | 12100000000000000000                                               |                                                                                                                        |

## 24. Table: LayerZeroagEUR\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-30 12:40:49+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 40938946                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc801d590c6565588787ce31f757281f510864616fa4bf39f9d8599f9815567ec | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 40                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 15000000000000000000000                                            |                                                                                                                        |
| recipient          | VARCHAR   | 0xba17f0d13d28f324a5a943c04067552db860c0c3                         |                                                                                                                        |

## 25. Table: LayerZeroagEUR\_event\_MessageFailed\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_srcChainId      | VARCHAR   |                                                              |             |
| \_srcAddress      | VARCHAR   |                                                              |             |
| \_nonce           | VARCHAR   |                                                              |             |
| \_payload         | VARCHAR   |                                                              |             |

## 26. Table: LayerZeroagEUR\_event\_ReceiveFromChain\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-30 00:57:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40920055                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b524a6a98c6102a41d592e95f121d088a63446e59a6449f5eaf8db0f9ceb159 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the contract that produced the log                |
| \_srcChainId      | VARCHAR   | 102                                                                |                                                              |
| \_srcAddress      | VARCHAR   | 0x3ef340ac54d1ac06d9a00989589707ac0b4b9e9ca8faa1208fa5f4316828ee6b |                                                              |
| \_toAddress       | VARCHAR   | 0x4d9d45c57371dddc2921e70ed877b3e341f24090                         |                                                              |
| \_amount          | VARCHAR   | 105037960348646088437                                              |                                                              |
| \_nonce           | VARCHAR   | 147                                                                |                                                              |

## 27. Table: LayerZeroagEUR\_event\_SendToChain\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 00:17:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43844785                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd7f2ce34ca9bcebf893ca94d9df3ad8341be597414025c0b9ec9cadc845fa483 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the contract that produced the log                |
| \_sender          | VARCHAR   | 0x97224e21063710b3f9d1d2e8293675b094cde39f                         |                                                              |
| \_dstChainId      | VARCHAR   | 102                                                                |                                                              |
| \_toAddress       | VARCHAR   | 0x306e172a7803932bd27eb4f7fe8d47771a089d1f393f8c2407ce8f8d44998f74 |                                                              |
| \_amount          | VARCHAR   | 38379788857275687                                                  |                                                              |
| \_nonce           | VARCHAR   | 11623                                                              |                                                              |

## 28. Table: LayerZeroagEUR\_event\_SetTrustedRemote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-25 13:22:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31123175                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93cc9d86742e858b2e971baebabd9b49c2a3fce120ec120e78185b777f58566c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 177                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the contract that produced the log                |
| \_srcChainId      | VARCHAR   | 11                                                                 |                                                              |
| \_srcAddress      | VARCHAR   | 0x840b25c87b626a259ca5ac32124fa752f0230a72                         |                                                              |

## 29. Table: LayerZeroagEUR\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 08:36:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42647398                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83f262c4dca4ae5bc04dab2c669361227069f37f5bdd4174052e5266438812d6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 238                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe0b52e49357fd4daf2c15e02058dce6bc0057db4                         |                                                              |
| to                | VARCHAR   | 0x0c1ebbb61374da1a8c57cb6681bf27178360d36f                         |                                                              |
| value             | VARCHAR   | 3980916684270858                                                   |                                                              |

## 30. Table: Treasury\_event\_BadDebtUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| badDebtValue      | VARCHAR   |                                                              |             |

## 31. Table: Treasury\_event\_Recovered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| token             | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 32. Table: Treasury\_event\_SurplusBufferUpdated\_history

| Column             | Type      | Example                                                      | Description |
| ------------------ | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number      | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index         | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address  | VARCHAR   | Address of the contract that produced the log                |             |
| surplusBufferValue | VARCHAR   |                                                              |             |

## 33. Table: Treasury\_event\_SurplusForGovernanceUpdated\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| \_surplusForGovernance | VARCHAR   |                                                              |             |

## 34. Table: Treasury\_event\_VaultManagerToggled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 23:54:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 32090499                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2a0b3dc97fd599bad50ba992f9a5c0bed02ad190db13e7fb71f9cc5bc8124c6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 353                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2f2e0ba9746aae15888cf234c4eb5b301710927e                         | Address of the contract that produced the log                |
| vaultManager      | VARCHAR   | 0x0945de4f356de3569fe12850ab85a91f533b87a0                         |                                                              |

## 35. Table: VaultManager\_call\_angle\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-04 16:23:54+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 38906848                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x92d8776fdb532fe5bee79e4c41dca075ec7de16304de40620aa2ca6fed653e11                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 96                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,8                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xfb16d8e96c0c6e9b72541bfd8d4c3d9e867c990b                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| actions            | VARCHAR   | 0,2,5                                                                                                |                                                                                                                        |
| datas              | VARCHAR   | 0x000000000000000000000000e51fae4c964e0eba4734a2d0b33db3c0ca7454ba,0x0000000000000000000000000000000 |                                                                                                                        |
| from               | VARCHAR   | 0xe51fae4c964e0eba4734a2d0b33db3c0ca7454ba                                                           |                                                                                                                        |
| to                 | VARCHAR   | 0xe51fae4c964e0eba4734a2d0b33db3c0ca7454ba                                                           |                                                                                                                        |
| who                | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |
| repayData          | VARCHAR   | 0x                                                                                                   |                                                                                                                        |

## 36. Table: VaultManager\_call\_createVault\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| toVault            | VARCHAR   |                                                                                                                        |             |

## 37. Table: VaultManager\_call\_getDebtOut\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-11 08:17:22+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37935683                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xdb18f67450b76ec016de4e6e8a69fc5cf556b6a0a853db93e768cfd4f8f7a673 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 154                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0945de4f356de3569fe12850ab85a91f533b87a0                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vaultID            | VARCHAR   | 10                                                                 |                                                                                                                        |
| stablecoinAmount   | VARCHAR   | 398999999999999999999                                              |                                                                                                                        |
| senderBorrowFee    | VARCHAR   | 0                                                                  |                                                                                                                        |
| senderRepayFee     | VARCHAR   | 0                                                                  |                                                                                                                        |

## 38. Table: VaultManager\_call\_liquidate\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-06-15 07:33:36+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 43931184                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x06ae79e6d22b5b7489d5de54b24eaf60d0466e923fc24c7795e7421acfd1239f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 34                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x4b81f51988cd6a9f44350cdabee9620d16359aa3                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| vaultIDs           | VARCHAR   | 11                                                                 |                                                                                                                        |
| amounts            | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |
| from               | VARCHAR   | 0xfda462548ce04282f4b6d6619823a7c64fdc0185                         |                                                                                                                        |
| to                 | VARCHAR   | 0xfda462548ce04282f4b6d6619823a7c64fdc0185                         |                                                                                                                        |

## 39. Table: VaultManager\_event\_AccruedToTreasury\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| surplusEndValue   | VARCHAR   |                                                              |             |
| badDebtEndValue   | VARCHAR   |                                                              |             |

## 40. Table: VaultManager\_event\_CollateralAmountUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 08:47:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45852780                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2d36915558b90d5335c39b90ccbb5286bcd3abce9a19ecc03843c973111d8c9b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 275                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfb16d8e96c0c6e9b72541bfd8d4c3d9e867c990b                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 997                                                                |                                                              |
| collateralAmount  | VARCHAR   | 1000000000                                                         |                                                              |
| isIncrease        | VARCHAR   | 0                                                                  |                                                              |

## 41. Table: VaultManager\_event\_DebtCeilingUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-13 12:16:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40297445                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20643603ec40561f9ca389d83e82a784df89aed104c3d545727542eb305f16e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3f125ecd51181af1f344adf76e4271d2923707ab                         | Address of the contract that produced the log                |
| debtCeiling       | VARCHAR   | 0                                                                  |                                                              |

## 42. Table: VaultManager\_event\_DebtTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-18 13:55:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44053748                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b4cfecbd81e2390fd55fc0902a16650dc8962f03ccb592d820f7b36308ebe6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 500                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf18303e2dd58cf29cad655b3bd2e1cc4582c6a16                         | Address of the contract that produced the log                |
| srcVaultID        | VARCHAR   | 48                                                                 |                                                              |
| dstVaultID        | VARCHAR   | 107                                                                |                                                              |
| dstVaultManager   | VARCHAR   | 0x4b81f51988cd6a9f44350cdabee9620d16359aa3                         |                                                              |
| amount            | VARCHAR   | 5000000000000000                                                   |                                                              |

## 43. Table: VaultManager\_event\_InterestAccumulatorUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-07 06:59:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43626522                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7618f116d965a4ca0b9e01be08d643ec0cfb42e692cd1848fa1b8dd8f746c6e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 254                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3f125ecd51181af1f344adf76e4271d2923707ab                         | Address of the contract that produced the log                |
| value             | VARCHAR   | 1004667405700590939975506444                                       |                                                              |
| timestamp         | VARCHAR   | 1686121186                                                         |                                                              |

## 44. Table: VaultManager\_event\_InternalDebtUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-15 18:25:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43947859                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe439069bf8f4c553b885b6b401ef21d08fe7909bb540f99a2e63fb46393f4063 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3f125ecd51181af1f344adf76e4271d2923707ab                         | Address of the contract that produced the log                |
| vaultID           | VARCHAR   | 44                                                                 |                                                              |
| internalAmount    | VARCHAR   | 34837399721944033                                                  |                                                              |
| isIncrease        | VARCHAR   | 0                                                                  |                                                              |

## 45. Table: VaultManager\_event\_LiquidatedVaults\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-18 22:10:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30875549                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc4e2bb432bae57094e7f1656b619c11e76d19ddd1ed49bfbc9d545e0c4bf7aa5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3f125ecd51181af1f344adf76e4271d2923707ab                         | Address of the contract that produced the log                |
| vaultIDs          | VARCHAR   | 2                                                                  |                                                              |

## 46. Table: VaultManager\_event\_LiquidationBoostParametersUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_veBoostProxy    | VARCHAR   |                                                              |             |
| xBoost            | VARCHAR   |                                                              |             |
| yBoost            | VARCHAR   |                                                              |             |

## 47. Table: VaultManager\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-24 07:07:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35998591                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f1cdaabf65d2ef0f5711aa1c0daa2a8fea7b368b645cf9080d64fdd5e541396 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 185                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfb16d8e96c0c6e9b72541bfd8d4c3d9e867c990b                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x237379cbbe22bc194a5e30fc7ebcb3f4cbab87c1                         |                                                              |
| tokenId           | VARCHAR   | 166                                                                |                                                              |

## 48. Table: agEUR\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-09 12:54:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23518238                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51a1e606fd923b0722e55180c2622def5d031a7d8f129ff3124c5f5ff1d1fcc1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 215                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe0b52e49357fd4daf2c15e02058dce6bc0057db4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x05afb98db7d32d4100ff4dac8a318580ca6d1da5                         |                                                              |
| to                | VARCHAR   | 0x82a54e66c05fcd555adae593848a4257c9e51ad9                         |                                                              |
| value             | VARCHAR   | 21601551893625447336029                                            |                                                              |
