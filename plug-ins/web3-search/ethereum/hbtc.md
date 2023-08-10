# hbtc

## 1. Table: HBTCToken\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-07 06:45:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9231939                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xace159c24540a8c7d7cab4ba2d6a14a74e849565afddb5e74fcac49333a12cd5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                         | Address of the contract that produced the log                |
| TaskType          | VARCHAR   | modifyAddress                                                      |                                                              |
| class             | VARCHAR   | store                                                              |                                                              |
| oldAddress        | VARCHAR   | 0x6e1a6d87e9d26b63fc7304d57feaabff2d87b308                         |                                                              |
| newAddress        | VARCHAR   | 0xc728693dcf6b257bf88577d6c92e52028426eefd                         |                                                              |

## 2. Table: HBTCToken\_event\_AdminRequiredNumChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-07 19:31:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15698307                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfcc6af0d2113db90ee73d87856c87a774e34b2aac22abb04faa405fd1fc0cc72 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                         | Address of the contract that produced the log                |
| TaskType          | VARCHAR   | resetRequiredNum                                                   |                                                              |
| class             | VARCHAR   | owner                                                              |                                                              |
| previousNum       | VARCHAR   | 2                                                                  |                                                              |
| requiredNum       | VARCHAR   | 3                                                                  |                                                              |

## 3. Table: HBTCToken\_event\_AdminTaskDropped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| taskHash          | VARCHAR   |                                                              |             |

## 4. Table: HBTCToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 21:47:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16350526                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x177760dd2336b405f3a821e856ee490c4ce3c2bfc45f314a14a0d2b0fd1ed168 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xe66b31678d6c16e9ebf358268a790b763c133750                         |                                                              |
| spender           | VARCHAR   | 0xdef1c0ded9bec7f1a1670819833240f027b25eff                         |                                                              |
| value             | VARCHAR   | 119809790100000000                                                 |                                                              |

## 5. Table: HBTCToken\_event\_Burned\_history

| Column            | Type      | Example                                                             | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-30 10:18:23+00:00                                           | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15645504                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d64a5f939acfc3e971dc785b38d2a708c2d870beae22edf2faa2919277ad933  | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                          | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                          |                                                              |
| value             | VARCHAR   | 5999999000000000000000                                              |                                                              |
| proof             | VARCHAR   | 1e7e78e17996894afcedf9dbc29508b3307a7e10342c257db5404f284214965b\_0 |                                                              |
| btcAddress        | VARCHAR   | 1NRXTibN25saCQ2o4kL1tJh4yFQskgHZoT                                  |                                                              |

## 6. Table: HBTCToken\_event\_Burning\_history

| Column            | Type      | Example                                                             | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-30 08:08:23+00:00                                           | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15644858                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x37012b8234d4fa950502b66e1f42e45b06613b967327de3563138a89861ffd77  | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                          | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                          |                                                              |
| value             | VARCHAR   | 1000000000000000                                                    |                                                              |
| proof             | VARCHAR   | ac642b1cf125b1b911e1b1abf0351aac48e569489bae2a346366467ac3443e3d\_0 |                                                              |
| btcAddress        | VARCHAR   | 1NRXTibN25saCQ2o4kL1tJh4yFQskgHZoT                                  |                                                              |
| burner            | VARCHAR   | 0x6b1c7f38a207b4b0f1934d2889740c700340016c                          |                                                              |

## 7. Table: HBTCToken\_event\_Minted\_history

| Column            | Type      | Example                                                              | Description                                                  |
| ----------------- | --------- | -------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-07 06:32:44+00:00                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11605922                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78acec20119e5885b71597ae84b2bfce15fe95f982c3aa811c27ada0a29f40a5   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 248                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                           | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x0f1b6a0e8ea224b866820f2f87ced1cb4bf76e4a                           |                                                              |
| value             | VARCHAR   | 199999500000000000000                                                |                                                              |
| proof             | VARCHAR   | fc3660c57ccfce2c196f63f804340a0f7d2fd4d116c9c54442dbbc7987297a23\_10 |                                                              |

## 8. Table: HBTCToken\_event\_Minting\_history

| Column            | Type      | Example                                                             | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-10 08:05:19+00:00                                           | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9453883                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0f827bf956974ffb9a9406078af643ea66f7f724ecb90c6db13b453be8030fc0  | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                          | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x0f1b6a0e8ea224b866820f2f87ced1cb4bf76e4a                          |                                                              |
| value             | VARCHAR   | 5000000000000000                                                    |                                                              |
| proof             | VARCHAR   | bb1823be26b36242ea581354c164956d1913c81daac05028e29ea37f11baee7e\_0 |                                                              |
| minter            | VARCHAR   | 0x31589a028fad4cb6809825f83b4e0992e126c6da                          |                                                              |

## 9. Table: HBTCToken\_event\_PauseChangedTo\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-09 08:25:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9076436                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29a2182f491717261fd3507b727772e186e9fca601b196c9907ad9124a108d80 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                         | Address of the contract that produced the log                |
| pauseState        | VARCHAR   | false                                                              |                                                              |

## 10. Table: HBTCToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-13 03:40:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10055426                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd8aaa1235dda660765d69a1331684713c5b93e7f2622c3f3d4b696f24303568f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0316eb71485b0ab14103307bf65a021042c6d380                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xafe311fbe26229f4ecacbb5c9c1813cc5ac20d2f                         |                                                              |
| to                | VARCHAR   | 0x1077159828f74a737126822b10bf19b33186e49a                         |                                                              |
| value             | VARCHAR   | 2000000000000000                                                   |                                                              |
