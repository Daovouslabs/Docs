# yearn

## 1. Table: V0Vault\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-10 14:30:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17663866                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9871da370745e2e54c6cd5dab0636a8482c0d1b8c8bb913fa54d6c06ef8d9cd9 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 10                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd6ad7a6750a7593e092a9b218d66c0a814a3436e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 7647010000                                                         |                                                                                                                        |

## 2. Table: V0Vault\_call\_redeem\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-05-27 23:58:04+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12519442                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x833e37c0125e69e30ef97c76306d9a1083a95770c9d3b56297f5ad8736c34bde | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 48                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd6ad7a6750a7593e092a9b218d66c0a814a3436e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_shares           | VARCHAR   | 86490105                                                           |                                                                                                                        |

## 3. Table: V0Vault\_call\_supplyAave\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-02-17 17:27:55+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9501931                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x57fdefd6dc7166d84f887992c8fde245251c2088f5626f3251df177bbe3a6a70 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 39                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x16de59092dae5ccf4a1e6439d611fd0653f0bd01                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 55773549047715589480699                                            |                                                                                                                        |

## 4. Table: V0Vault\_call\_supplyCompound\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-07-02 23:22:10+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10382927                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x70f9f17a3712084cde97bd56ed44d21b2fdf88fbc8ba7f45596f254039364995 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 171                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x83f798e925bcd4017eb265844fddabb448f1707d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 951384000000                                                       |                                                                                                                        |

## 5. Table: V0Vault\_call\_supplyDydx\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-11-19 04:17:21+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11286201                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf1fdeb8a85937ad018b47306572d2285eda7826f538ed575e487e5201b71df6f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 73                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x73a052500105205d34daf004eab301916da8190f                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 10000000                                                           |                                                                                                                        |

## 6. Table: V0Vault\_call\_supplyFulcrum\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-02-18 04:36:41+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9505007                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5ae20c26eb9807ce32f1aabf7d36f0e5fb70ebb1c09f8dfa49a34265b701ae8e | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 80                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd6ad7a6750a7593e092a9b218d66c0a814a3436e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 89669621457                                                        |                                                                                                                        |

## 7. Table: V0Vault\_call\_withdrawAave\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-03-26 15:15:12+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9747759                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x93a2d9a3a4d1cb536185402409316cf28de79bc4339bcb0dd20e3bb3597c81db | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 60                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x04bc0ab673d88ae9dbc9da2380cb6b79c4bca9ae                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |

## 8. Table: V0Vault\_call\_withdrawDydx\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-03-03 05:53:29+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9596396                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xed1aeab16a34f5f52a0f110a055a5dead3d12fba58e9ad3cfc0d179c31ea0164 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 124                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc2cb1040220768554cf699b0d863a3cd4324ce32                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 108341782335535727614478                                           |                                                                                                                        |

## 9. Table: V0Vault\_call\_withdrawSomeCompound\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-03-11 04:45:13+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 9648142                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa7bcdc96e630611b5c95d0314b45a77e35d5624858e303fdea29422f762b60b7 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 105                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x26ea744e5b887e5205727f55dfbe8685e3b21951                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 0                                                                  |                                                                                                                        |

## 10. Table: V0Vault\_call\_withdrawSomeFulcrum\_history

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
| \_amount           | VARCHAR   |                                                                                                                        |             |

## 11. Table: V0Vault\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-04-18 20:43:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17075997                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb05766c6107e8ed482a2f7450357d4a863620a45cc3157db1accca34cf7ab4ee | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 95                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 2,7                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x04bc0ab673d88ae9dbc9da2380cb6b79c4bca9ae                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_shares           | VARCHAR   | 2515462342747628436868                                             |                                                                                                                        |

## 12. Table: V0Vault\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 12:31:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15553318                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x155230c635d3f51ba94d294d6ec9cf04fd86e39bb2dbc73ee45501e3b9c21d04 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16de59092dae5ccf4a1e6439d611fd0653f0bd01                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x45f783cce6b7ff23b2ab2d70e416cdb7d6055f51                         |                                                              |
| to                | VARCHAR   | 0xbbc81d23ea2c3ec7e56d39296f0cbb648873a5d3                         |                                                              |
| value             | VARCHAR   | 295854199394741113183                                              |                                                              |

## 13. Table: V1Vault\_call\_depositAll\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-08-09 14:02:28+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10626149                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5b266468165479ccb55967e616449d83f43b784948a3a639d2e964016ca33390 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 49                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x37d19d1c4e1fa9dc47bd1ea12f742a0887eda74a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 14. Table: V1Vault\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-02-25 10:36:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11925830                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf16db18f957f1aa2ed7399ec8c181a96d4e585cc7fd00ffe98e62c4a401c5bf2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 198                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x03403154afc09ce8e44c3b185c82c6ad5f86b9ab                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 96876231274344226513783                                            |                                                                                                                        |

## 15. Table: V1Vault\_call\_earn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-09-21 04:58:00+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10903727                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x1066eee4bf496770641cce1b044ad0d993fd2683ecf0dc7a7e2f103cf33ff636 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 177                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5dbcf33d8c2e976c6b560249878e6f1491bca25c                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 16. Table: V1Vault\_call\_withdrawAll\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-02-07 01:00:57+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11806172                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9b6b51dad72b89a7eb27f7dc7034c40891a70fd9d48a472586ff821e7ebca535 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 83                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xba2e7fed597fd0e3e70f5130bcdbbfe06bb94fe1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 17. Table: V1Vault\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-04 22:45:56+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15278594                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x52ede6e24f0dc55fc5e954540b34756fc0eccd806ee40066f71ebf1f6c1f7b28 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 185                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x5dbcf33d8c2e976c6b560249878e6f1491bca25c                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_shares           | VARCHAR   | 526698391769908208351                                              |                                                                                                                        |

## 18. Table: V1Vault\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-21 01:11:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16673534                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbddd42d5f4a038a752ebfce19c3f99086bd19b644d2b57500a2bd5336ec01378 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5bddf9843308380375a611c18b50fb9341f502a                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x58fcde6607747fc7cef8d8df2e9a798fa3c6840e                         |                                                              |
| to                | VARCHAR   | 0x01d7f32b6e463c96c00575fa97b8224326c6a6b9                         |                                                              |
| value             | VARCHAR   | 81991143916235411804                                               |                                                              |

## 19. Table: V2AdditionalVaults\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-18 04:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17071082                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x486957e2cdb87e589e8d7f19cccbc22d9adbe5a073430d1e52c2ccb6e28d05ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 281                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa696a63cc78dffa1a63e9e50587c197387ff6c7e                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| receiver          | VARCHAR   | 0xd997b5e092f6b11b2668ccb6d890f1a55a05e519                         |                                                              |
| value             | VARCHAR   | 97044267                                                           |                                                              |

## 20. Table: V2VaultRegistry\_event\_NewVault\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-27 14:16:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15034763                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2c3997116fc1e143639af34377db061ec00ea35051c8fa1127b7946968bec414 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 556                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x78f73705105a63e06b932611643e0b210fae93e9                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x32296969ef14eb0c6d29669c550d4a0449130230                         |                                                              |
| vaultId           | VARCHAR   | 0                                                                  |                                                              |
| vaultType         | VARCHAR   | 1                                                                  |                                                              |
| vault             | VARCHAR   | 0xcc7de22c5004062f409f4e3e8b5ab8ee4e62f8f9                         |                                                              |
| apiVersion        | VARCHAR   | 0.4.3                                                              |                                                              |

## 21. Table: V2Vault\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-27 11:55:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17784238                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa434a74a8c60da1c18a8211341e29de5c1e474aae0fcc305db070fe93c61e3ee | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 158                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 3                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x27b5739e22ad9033bcbf192059122d163b60349d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 1780904051231562193532                                             |                                                                                                                        |
| recipient          | VARCHAR   | 0x33eecc48943aaeabb5328a25ff28eb85f67945c2                         |                                                                                                                        |

## 22. Table: V2Vault\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-08-13 08:29:39+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15332356                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x72cda1b21009e81e43305a444147860536ac1d181a39e1528f0ef09e0f9492a0 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 17                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,41,4                                                         | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa354f35829ae975e850e23e9615b11da1b3dc4de                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| maxShares          | VARCHAR   | 61809950413                                                        |                                                                                                                        |
| recipient          | VARCHAR   | 0xe140bb5f424a53e0687bfc10f6845a5672d7e242                         |                                                                                                                        |
| maxLoss            | VARCHAR   | 1                                                                  |                                                                                                                        |

## 23. Table: V2Vault\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-05 12:00:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14326744                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf896ff1f097b564c6caf70f8290503926fc93a5c7c8b58d76559659a3d1343be | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 155                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x132d8d2c76db3812403431facb00f3453fc42125                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x8bf675b7d0b701849eaa306affa55e36a308257d                         |                                                              |
| receiver          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 15616811020356775693                                               |                                                              |

## 24. Table: Vault\_Deployer\_event\_NewExperimentalVault\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-22 03:55:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14632407                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9145e0e3e826f51ae9048a393312ba6eba5c94fc8e634964979e325f7d10ccfb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50c1a2ea0a861a967d9d0ffe2ae4012c2e053804                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         |                                                              |
| deployer          | VARCHAR   | 0xa38a0bc95b59b92b8ff8aef8f79e61a829a02dda                         |                                                              |
| vault             | VARCHAR   | 0xb364d19c3ff37e0fa4b94bf4cf626729533c1c26                         |                                                              |
| api\_version      | VARCHAR   | 0.4.3                                                              |                                                              |

## 25. Table: VeCurveVault\_call\_claimFor\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-12-12 19:05:36+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11439940                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x767ea6371db75d81b9119d84a3cb55f7883984abf2efd843822705afcd158f73 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 106                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc5bddf9843308380375a611c18b50fb9341f502a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| recipient          | VARCHAR   | 0x5ae725d8c2fc96b6471a842dee617c637dc8cc7c                         |                                                                                                                        |

## 26. Table: VeCurveVault\_call\_claim\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-08 08:56:09+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13574840                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x408cbce21def6710905e18b374545d61fde114b10e0694b9d7d6f5f6953d26c0 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 54                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xc5bddf9843308380375a611c18b50fb9341f502a                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 27. Table: Woofy\_call\_unwoof\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-01-01 19:18:29+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13921374                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x65d1b753e2e36309c023443214fa9b20f83e29ca82d4a1998261ae6f9036c7b6 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 5                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2,0,2,0                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd0660cd418a64a1d44e9214ad8e459324d8157f1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 518466266224781398                                                 |                                                                                                                        |
| receiver           | VARCHAR   | 0x92498f5a2878a2d7d6f29ccdba5b52273b29a2d9                         |                                                                                                                        |

## 28. Table: Woofy\_call\_woof\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-05-19 13:55:36+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12465216                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x3cde8915a337919bb5016110a45a03cd08a8705c7de6b3d3dae8cc90a19ff114 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 10                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 5,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xd0660cd418a64a1d44e9214ad8e459324d8157f1                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 3544733360418376704                                                |                                                                                                                        |
| receiver           | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                                                                                        |

## 29. Table: Woofy\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-19 01:55:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14612765                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x133a81ad7a868d03a2289eb6e62a35d31f66c954ff970b36f468c452c7b6dcff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 562                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd0660cd418a64a1d44e9214ad8e459324d8157f1                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x78c0a25ccc21604b3d117100de7c9523f53236c7                         |                                                              |
| receiver          | VARCHAR   | 0x5d0cdb2dae4c13c569578e85d81fd2f41d82cd9f                         |                                                              |
| value             | VARCHAR   | 2000000000000000                                                   |                                                              |

## 30. Table: YearnGovernance\_call\_voteAgainst\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-07-30 08:47:08+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10560002                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x570b140e7811c4d8f0f9d91de4ad06d0cffd1f5ff24f37f1b8702d8ceda53820 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 262                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3a22df48d84957f907e67f4313e3d43179040d6e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 28                                                                 |                                                                                                                        |

## 31. Table: YearnGovernance\_call\_voteFor\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-07-24 21:03:41+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10524549                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2f84675f028029456cf80f6e3216eec07aa4d22ac3e2e798cbf7a94936216634 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 14                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x3a22df48d84957f907e67f4313e3d43179040d6e                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| id                 | VARCHAR   | 8                                                                  |                                                                                                                        |

## 32. Table: YearnGovernance\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-19 14:00:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10490371                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x27543c184e3c55f532622824f11e23ae9fc38d34078724e40042780990fa2a49 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3a22df48d84957f907e67f4313e3d43179040d6e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x2d407ddb06311396fe14d4b49da5f0471447d45c                         |                                                              |

## 33. Table: YearnGovernance\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-19 15:38:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10490821                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14b861562694ca6ae06cebb3416dea62c149342bf9adfe9ff28e5180082047c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3a22df48d84957f907e67f4313e3d43179040d6e                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 10000000000000000000000                                            |                                                              |

## 34. Table: YearnGovernance\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-15 13:18:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10664855                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeac52ba08617289a3d20938b060dcfad2b871d63daaaa433c5c30040361d1db1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3a22df48d84957f907e67f4313e3d43179040d6e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xac7e04b9b3757cd94eaeec4abaa5b754ec2c0f88                         |                                                              |
| reward            | VARCHAR   | 5904231564070839                                                   |                                                              |

## 35. Table: YearnGovernance\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-24 17:28:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10926667                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3887510a9459a00c22a65b8a4774bb755f5bf252331eba340f000f4c6883a4a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 209                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3a22df48d84957f907e67f4313e3d43179040d6e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xd9d3dd56936f90ea4c7677f554dfefd45ef6df0f                         |                                                              |
| amount            | VARCHAR   | 1151243707008394417700                                             |                                                              |

## 36. Table: YearnGovernance\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-14 01:36:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10655197                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x644a3524cd048447499519e5d52c6b7e7c4e993059276d65767fc8fe157208f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3a22df48d84957f907e67f4313e3d43179040d6e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xf62405e188bb9629ed623d60b7c70dcc4e2abd81                         |                                                              |
| amount            | VARCHAR   | 1375563400000000000000                                             |                                                              |
