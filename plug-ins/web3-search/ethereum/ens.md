# ens

## 1. Table: BaseRegistrarImplementation2\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 01:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15550174                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc96508fad468e59a11bd0f61ddbccb7bf35528dd19197b5db2dd7cf7521467b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x718f255fcb6e4537f4f45276d61c4f902e4f91ef                         |                                                              |
| operator          | VARCHAR   | 0x1d15d646d2a48a0bbd8544a7d9ab8730d0ea769a                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 2. Table: BaseRegistrarImplementation2\_event\_Approval\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-07 02:55:16+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13176082                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6bad9fb798c0e49cd54d83d33b38262846800d914db3d1fbc41cee352b75055f            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 314                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                                    | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x2b77fb1c59aac4cb785d0fc9ecd3623479a59022                                    |                                                              |
| approved          | VARCHAR   | 0x67332780711d6af31f19210cd3b7dbc6f4b1e605                                    |                                                              |
| tokenId           | VARCHAR   | 99218729431694671476841305155182527183917706889032298744728127639180850277200 |                                                              |

## 3. Table: BaseRegistrarImplementation2\_event\_ControllerAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-10 17:27:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9456489                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e1532fbb95ec440a816d3ff5e49280796a03117b703adbea82de0897850861f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                         | Address of the contract that produced the log                |
| controller        | VARCHAR   | 0x283af0b28c62c092c9727f1ee09c02ca627eb7f5                         |                                                              |

## 4. Table: BaseRegistrarImplementation2\_event\_ControllerRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-30 00:51:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9380451                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x61a41008f49df6c1572e10bb22cb59e6179601af925bd68f22a3b3380c4e709d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                         | Address of the contract that produced the log                |
| controller        | VARCHAR   | 0x4fe4e666be5752f1fdd210f4ab5de2cc26e3e0e8                         |                                                              |

## 5. Table: BaseRegistrarImplementation2\_event\_NameRegistered\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-01 00:18:07+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15053312                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3f4e8193b84cf4b95bb18ee01fd0e6559aa8a70736db042878a652fb6d0fefb3            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                                    | Address of the contract that produced the log                |
| id                | VARCHAR   | 18209619987220580958208447028056510746349021617036778270019279212037886675168 |                                                              |
| owner             | VARCHAR   | 0x283af0b28c62c092c9727f1ee09c02ca627eb7f5                                    |                                                              |
| expires           | VARCHAR   | 1719748591                                                                    |                                                              |

## 6. Table: BaseRegistrarImplementation2\_event\_NameRenewed\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-02 20:22:45+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13148416                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x44c7cc614519f73be817f09ccf55a09ed7f432d25fc3e462c096dbe200c8f425            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 318                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                                    | Address of the contract that produced the log                |
| id                | VARCHAR   | 71634202636410150172301910357017760022837098727916720143329987198658478505173 |                                                              |
| expires           | VARCHAR   | 1817034330                                                                    |                                                              |

## 7. Table: BaseRegistrarImplementation2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-30 03:04:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9381046                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa487487e093e33808f57b61a11a6f1d9ef9c13c9b19a2d506a9e26ff8fc1f4c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 141                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0904dac3347ea47d208f3fd67402d039a3b99859                         |                                                              |
| newOwner          | VARCHAR   | 0xcf60916b6cb4753f58533808fa610fcbd4098ec0                         |                                                              |

## 8. Table: BaseRegistrarImplementation2\_event\_Transfer\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 14:03:23+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15553772                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x47163b14592b72312b7b3e06d697a076065ca396b8d6b2f41761e885fa32ecc5            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x57f1887a8bf19b14fc0df6fd9b2acc9af147ea85                                    | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                                    |                                                              |
| to                | VARCHAR   | 0x02ff125d71291b94eb89d76494dfd4d3b9964661                                    |                                                              |
| tokenId           | VARCHAR   | 43629122875546974911199108446838205962817282250746014229283196586424200336856 |                                                              |

## 9. Table: BaseRegistrarImplementation\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-20 08:21:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8967284                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc04227ed7bead11dda8b888bb8d4d5b5e68ba9d7605b5e96b841fce32e4d926d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfac7bea255a6990f749363002136af6556b31e04                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x1eae59ed1012d8b7c6b37910b4df20163cafd1ac                         |                                                              |
| operator          | VARCHAR   | 0xc94e32d4b2da9b4e6e1908d59a52719d1499b90e                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 10. Table: BaseRegistrarImplementation\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-07 21:46:12+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8892427                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x58ff28a7c570de7013dd9978598375311e7e5f8587b9547d87160028175cb685             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfac7bea255a6990f749363002136af6556b31e04                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x4905f174cc2b82585d022271ba71e3fd8d1fa756                                     |                                                              |
| approved          | VARCHAR   | 0xc32659651d137a18b79925449722855aa327231d                                     |                                                              |
| tokenId           | VARCHAR   | 110227063993860708706961073390041690752443963199593707654105391973491579232304 |                                                              |

## 11. Table: BaseRegistrarImplementation\_event\_NameMigrated\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-26 00:17:19+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9354179                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc787c383cccf2240da019d25c3967675829f90d701073fad23eed1a98e6c8d81            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfac7bea255a6990f749363002136af6556b31e04                                    | Address of the contract that produced the log                |
| id                | VARCHAR   | 45978360990821223467589934396970952372327403908733810665026000365974230929475 |                                                              |
| owner             | VARCHAR   | 0x137a283c517927ffcf0270ac5ba378a42b89ee95                                    |                                                              |
| expires           | VARCHAR   | 1588550400                                                                    |                                                              |

## 12. Table: BaseRegistrarImplementation\_event\_NameRegistered\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-14 09:32:18+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7955968                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x545cd16c74cd0a93bba2eae2d2925227b800fb4fbcefcea899761e6b7227391b            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfac7bea255a6990f749363002136af6556b31e04                                    | Address of the contract that produced the log                |
| id                | VARCHAR   | 86980208026955217602990064297379926373662467190049480321179451591017849949243 |                                                              |
| owner             | VARCHAR   | 0x1be1329bfcd8bc85b424fa9af7392e5defbdb2ed                                    |                                                              |
| expires           | VARCHAR   | 1588550400                                                                    |                                                              |

## 13. Table: BaseRegistrarImplementation\_event\_NameRenewed\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-08 18:46:03+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8703006                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f53f68d9bb84ab3b6e7c1948b16a178ca37ebcfe4ab914cd87a64cb6dcf1579            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfac7bea255a6990f749363002136af6556b31e04                                    | Address of the contract that produced the log                |
| id                | VARCHAR   | 38193096983377148578553531265287073191727849814179827133915229819476298322570 |                                                              |
| expires           | VARCHAR   | 1746335160                                                                    |                                                              |

## 14. Table: BaseRegistrarImplementation\_event\_Transfer\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-16 19:13:46+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8363326                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd5263ebfe84e51eb03ada85019e0fd6fef194b44568a444d11b941d369d7aa0b             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 128                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfac7bea255a6990f749363002136af6556b31e04                                     | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                                     |                                                              |
| to                | VARCHAR   | 0x007d13b082d4fafa566ad96ee07153c51e1b3171                                     |                                                              |
| tokenId           | VARCHAR   | 106180191130483515882274972925864748461847280356153785178679492551652151570273 |                                                              |

## 15. Table: ENSRegistryWithFallback\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 11:39:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17741274                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd4c6e572780fa0273be09eacf1090bcbf582aaac7a8d39aec3d3f7c38f0ed18 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000c2e074ec69a0dfb2997ba6c7d2e1e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xd04e9f0945dea8373d882c730e2c93a74b591796                         |                                                              |
| operator          | VARCHAR   | 0xd4416b13d2b3a9abae7acd5d6c2bbdbe25686401                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 16. Table: ENSRegistryWithFallback\_event\_NewOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-07-16 12:19:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10470504                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc6bf6b8628067aa04ae0d4514f0c3ebfd628901a68e527267d6555eeed9dabf7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000c2e074ec69a0dfb2997ba6c7d2e1e                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0x002414632d01ec62f79ecea6c44427832e5ac5a2c4a7a130d83888fb47feed55 |                                                              |
| label             | VARCHAR   | 0x3350d745acd40b6a232b0266fe40c74a81ac78c31f48c00f5714ba6769cbc374 |                                                              |
| owner             | VARCHAR   | 0x528f7bd49690c0353d69be67ed6a2b6f76c86127                         |                                                              |

## 17. Table: ENSRegistryWithFallback\_event\_NewResolver\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 18:27:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12730532                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb3e5259d7b2a1c9f88c0944cbc0362d629dc9ffc43f9cde5ab1cc515c3dd074c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 370                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000c2e074ec69a0dfb2997ba6c7d2e1e                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0xcfa0a12ba4b374332bb25a4a4fe8f232a43e93fc039e65f410afa8a98158109e |                                                              |
| resolver          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 18. Table: ENSRegistryWithFallback\_event\_NewTTL\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 05:23:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15916034                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5a7c97b616f7f2e6489a9fe8065dc4a225dc6a96e7182d708fafdc0492434d7c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 570                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000c2e074ec69a0dfb2997ba6c7d2e1e                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0x8ca83c1d5d506b91942e24c6ab05382f4295f4447c04c4285ac33d4a71fc0b08 |                                                              |
| ttl               | VARCHAR   | 18446744073709551615                                               |                                                              |

## 19. Table: ENSRegistryWithFallback\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 04:18:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17824879                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xafb1665290d6afd3a2fce1b395d6659517107635f5ad8ecaa7041bae285b6dbb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 506                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000c2e074ec69a0dfb2997ba6c7d2e1e                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0x0afccdbe1b9c07c5a6bb3eeedfaf3d6811dbf0f18b2c3aabb459f0218bd50938 |                                                              |
| owner             | VARCHAR   | 0xf080b17bf859ac0152243b122a9fb5f2641d688d                         |                                                              |

## 20. Table: ENSRegistry\_event\_NewOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-07 20:58:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15698742                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x656f1fd5bb791d18668a1a569aaa3d3769aa44e87cf7df6628c900aac71cf011 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 665                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x314159265dd8dbb310642f98f50c066173c1259b                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0x5f7791d31ca0493e9ca7c9ca16695ecd9d5044768674d14d31ab5d8277518fff |                                                              |
| label             | VARCHAR   | 0x03a58fa4fa0013ce70a3c6c577562ff75d0e1ca52f6f77eecb0485ba96293ff6 |                                                              |
| owner             | VARCHAR   | 0xdb5ac1a559b02e12f29fc0ec0e37be8e046def49                         |                                                              |

## 21. Table: ENSRegistry\_event\_NewResolver\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-14 16:19:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15747495                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf6e60c4acb96b4e4af0a95bcd6a5d3f5a81a4e3c9e6f729e44d51d1f4d5a736c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x314159265dd8dbb310642f98f50c066173c1259b                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0xfc28a4ec77eb890fa20624fa0e7e87cf66beec05d3521774ab2211346eeb17e8 |                                                              |
| resolver          | VARCHAR   | 0x1da022710df5002339274aadee8d58218e9d6ab5                         |                                                              |

## 22. Table: ENSRegistry\_event\_NewTTL\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-07-10 17:38:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4003999                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xafb6d7ac92f6beb3f3df6a9bbfaeb2f99b9db020ee69199af95f2e8ea5253467 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x314159265dd8dbb310642f98f50c066173c1259b                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0xfac963bc058381048d445ea4f8cadd6b70b057034ee1096cec5d49562735b446 |                                                              |
| ttl               | VARCHAR   | 152602057872002244                                                 |                                                              |

## 23. Table: ENSRegistry\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-08 14:30:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10026125                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed7573ea381f3180f393162eec3ee24af5ff255ee6b845d397deb8f2dbb63c0e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 95                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x314159265dd8dbb310642f98f50c066173c1259b                         | Address of the contract that produced the log                |
| node              | VARCHAR   | 0x3693e2e7b49192c8d438961f683a202b15c0fc03b698acdb8f2b05cbe52977cb |                                                              |
| owner             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 24. Table: ENSToken\_event\_Claim\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 07:24:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13619000                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x143b682fa5c198df9cde22bc79eead4d60fa895f79a1cca186d52005ae0e028b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         | Address of the contract that produced the log                |
| claimant          | VARCHAR   | 0x9047160b5e47e9290caa12886730c73cbb136884                         |                                                              |
| amount            | VARCHAR   | 34473173166350974976                                               |                                                              |

## 25. Table: ENSToken\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 10:08:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15717007                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ea0d70415afbd91c06dd0ae2ad171ec90de3ba295ae5a4b769e28d7f4e41970 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0xda31160a4afc898c01a44f2f3b1b880b6356940d                         |                                                              |
| fromDelegate      | VARCHAR   | 0xda31160a4afc898c01a44f2f3b1b880b6356940d                         |                                                              |
| toDelegate        | VARCHAR   | 0xda31160a4afc898c01a44f2f3b1b880b6356940d                         |                                                              |

## 26. Table: ENSToken\_event\_DelegateVotesChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 23:11:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15493076                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5ff9bd0395d8776c93e8bd16dc9f049aff578204479e98448294b3b9f0d555b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         | Address of the contract that produced the log                |
| delegate          | VARCHAR   | 0x30b7666a760cc3936e2c03638af18799efa7f0dc                         |                                                              |
| previousBalance   | VARCHAR   | 84509924261126688768                                               |                                                              |
| newBalance        | VARCHAR   | 0                                                                  |                                                              |

## 27. Table: ENSToken\_event\_MerkleRootChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-09 00:00:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13578841                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x581e8002ab4fed8d25e725216b846c6c2e642a8700982ab4b60505ab24c8bfed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 361                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         | Address of the contract that produced the log                |
| merkleRoot        | VARCHAR   | 0xaca22207fc31a4c3ecd6ab11ce2df3db64b8afeba4f31db2b9aeb76f1dada659 |                                                              |

## 28. Table: ENSToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-09 03:02:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13579691                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7a36823f972df70dcc2b96c9fb08810d5e0316fee77e987181d716592c7aa7f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 708                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0904dac3347ea47d208f3fd67402d039a3b99859                         |                                                              |
| newOwner          | VARCHAR   | 0xfe89cc7abb2c4183683ab71653c4cdc9b02d44b7                         |                                                              |

## 29. Table: ENSToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-22 01:30:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15585619                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb745923e916392c86899fa0188e7a3ffdab726a862c4affdd9f11b6bcfb6f90c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc18360217d8f7ab5e7c516566761ea12ce7f9d72                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe377b77e7177c236ede5abd317960fc023efd841                         |                                                              |
| to                | VARCHAR   | 0x00000000009726632680fb29d3f7a9734e3010e2                         |                                                              |
| value             | VARCHAR   | 32821500169267777536                                               |                                                              |

## 30. Table: ETHRegistrarController2\_event\_NameRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-23 05:20:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8984622                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7dc172d864f9e3201f0fdfd96a554b3db4e1aee937eb2c94d0f729ce47088c6e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 157                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb22c1c159d12461ea124b0deb4b5b93020e6ad16                         | Address of the contract that produced the log                |
| name              | VARCHAR   | letsgamble                                                         |                                                              |
| label             | VARCHAR   | 0x4db833237a109d589e2d0b898eebe6653e7b38af62bf3025878311255424c40f |                                                              |
| owner             | VARCHAR   | 0x0342571038c01c1b6f91c44dd59a719e79907827                         |                                                              |
| cost              | VARCHAR   | 33258605806566301                                                  |                                                              |
| expires           | VARCHAR   | 1606044036                                                         |                                                              |

## 31. Table: ETHRegistrarController2\_event\_NameRenewed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-03 04:30:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9407393                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0d8292dcd4e6d2c2e9daae90a464e601170db97618464a4a20091bf9a1b930f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 148                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb22c1c159d12461ea124b0deb4b5b93020e6ad16                         | Address of the contract that produced the log                |
| name              | VARCHAR   | aggregator                                                         |                                                              |
| label             | VARCHAR   | 0xe124d7cc79a19705865fa21b784ba187cd393559e960c0c071132cb60354d1a3 |                                                              |
| cost              | VARCHAR   | 52551762390712988                                                  |                                                              |
| expires           | VARCHAR   | 1651664304                                                         |                                                              |

## 32. Table: ETHRegistrarController2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-04 00:43:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8868362                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf022ee0ccc64a72baa05c7dc9759c54cede855c729ba44d7f7d94cdc32cef0b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 276                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb22c1c159d12461ea124b0deb4b5b93020e6ad16                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x0904dac3347ea47d208f3fd67402d039a3b99859                         |                                                              |

## 33. Table: ETHRegistrarController3\_event\_NameRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-11 00:14:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9646929                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb23dbd5373565fccce7c7bf76639adef0eee6e6d7f45631e149a1e287c54763 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x283af0b28c62c092c9727f1ee09c02ca627eb7f5                         | Address of the contract that produced the log                |
| name              | VARCHAR   | smallville                                                         |                                                              |
| label             | VARCHAR   | 0x963dd8eb4adbd2e727edf502aec81b4611d17ff7205a848b13ca77a6960f3e41 |                                                              |
| owner             | VARCHAR   | 0x10f546a6f4d20d91e5a8506124384759c9f4bc79                         |                                                              |
| cost              | VARCHAR   | 24689474057803142                                                  |                                                              |
| expires           | VARCHAR   | 1615442630                                                         |                                                              |

## 34. Table: ETHRegistrarController3\_event\_NameRenewed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-28 01:24:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11942851                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb94391b3520baab58a8ce66655b060b34f403af4cbb40793ceaa9d31641dcdae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x283af0b28c62c092c9727f1ee09c02ca627eb7f5                         | Address of the contract that produced the log                |
| name              | VARCHAR   | braytonkey                                                         |                                                              |
| label             | VARCHAR   | 0xd4d2a38e7e2689904f5343c097d2edf365dc7d6450eb61ad8e0fe5dbcbdd1503 |                                                              |
| cost              | VARCHAR   | 3412127007694044                                                   |                                                              |
| expires           | VARCHAR   | 1639071447                                                         |                                                              |

## 35. Table: ETHRegistrarController3\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-29 19:21:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13710360                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39effaa3280ee43c84af8db7936d0bf982bc72ea2f50af30bdcd5461eff6cdb5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 253                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x283af0b28c62c092c9727f1ee09c02ca627eb7f5                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xcf60916b6cb4753f58533808fa610fcbd4098ec0                         |                                                              |
| newOwner          | VARCHAR   | 0xfe89cc7abb2c4183683ab71653c4cdc9b02d44b7                         |                                                              |

## 36. Table: ETHRegistrarController\_event\_NameRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-14 23:58:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7761569                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb76fb1b653dd231d8dcd4e30e7923350f921327a260e9075bd166994dea0ba35 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 42                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf0ad5cad05e10572efceb849f6ff0c68f9700455                         | Address of the contract that produced the log                |
| name              | VARCHAR   | davidsun                                                           |                                                              |
| label             | VARCHAR   | 0xd4c54c5b3b46e4ee7b095117590114d6adfb8288c0db9f6e53b69223f521c60f |                                                              |
| owner             | VARCHAR   | 0x37f64fb7fa2fbc5f6056301273faf8a1fc803b7a                         |                                                              |
| cost              | VARCHAR   | 22899022484788241                                                  |                                                              |
| expires           | VARCHAR   | 1589435290                                                         |                                                              |

## 37. Table: ETHRegistrarController\_event\_NameRenewed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-23 13:12:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8796859                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb5c2ede5fe3a43be15c611c709a15f39db8a1484b81e4a6ae9ae8105c0d385c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf0ad5cad05e10572efceb849f6ff0c68f9700455                         | Address of the contract that produced the log                |
| name              | VARCHAR   | ilcalicedoro                                                       |                                                              |
| label             | VARCHAR   | 0x612ab3bb36e95fe51debf93145901cfd038dbfd03342957c3b0278c32480955f |                                                              |
| cost              | VARCHAR   | 124852850502231682                                                 |                                                              |
| expires           | VARCHAR   | 1729616081                                                         |                                                              |

## 38. Table: ETHRegistrarController\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-30 03:54:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7666495                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0109c93231666132ce6d4a8a40740495ed72f7c0801d085f8c5e97b4bdadd8c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf0ad5cad05e10572efceb849f6ff0c68f9700455                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x0904dac3347ea47d208f3fd67402d039a3b99859                         |                                                              |

## 39. Table: Registrar0\_event\_AuctionStarted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-02-06 07:35:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5039869                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22660ee4c0a9b2ad7600a0cfcdbf25833fac2ab9ff4e1aca749bb805db9929df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6090a6e47849629b7245dfa1ca21d94cd15878ef                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x7221d80e9bc50f7ac04d91b49e6fee994ca01eb0c7a297291c78d56785f3cb26 |                                                              |
| registrationDate  | VARCHAR   | 1518334527                                                         |                                                              |

## 40. Table: Registrar0\_event\_BidRevealed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-11-07 08:17:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4506314                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83bf4e6b29a0e1ea9ab203107445b58879e5e46d55def63de181fdf24f048637 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6090a6e47849629b7245dfa1ca21d94cd15878ef                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x16afd1265b685b173da0a15449f5b518f4e985d853a3976cc742575a6afbc36e |                                                              |
| owner             | VARCHAR   | 0xdb5d32743a84691d9c932cb79ced8b5a4b82c4e0                         |                                                              |
| value             | VARCHAR   | 11000000000000000                                                  |                                                              |
| status            | VARCHAR   | 1                                                                  |                                                              |

## 41. Table: Registrar0\_event\_HashInvalidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-16 01:50:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7576109                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0b01fce0397b62bf881576f0b80a437fb00400e304c4a4ce1af7adb344662df3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 19                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6090a6e47849629b7245dfa1ca21d94cd15878ef                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x42144640c7cb5ff8aa9595ae175ffcb6dd152db6e737c13cc2d5d07576967020 |                                                              |
| name              | VARCHAR   | 0x42144640c7cb5ff8aa9595ae175ffcb6dd152db6e737c13cc2d5d07576967020 |                                                              |
| value             | VARCHAR   | 10000000000000000                                                  |                                                              |
| registrationDate  | VARCHAR   | 1555318413                                                         |                                                              |

## 42. Table: Registrar0\_event\_HashRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-12-28 07:43:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6966793                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4954f289c6d564579875e7af936a82154c81b949b8725811d25fa02d5fa5ae3a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6090a6e47849629b7245dfa1ca21d94cd15878ef                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x0a64bd05793d2271c859d78d95c27f283397a35d91863586692873766d588063 |                                                              |
| owner             | VARCHAR   | 0x62e3478e2280a800cbf4f6b0358a36dcc0473679                         |                                                              |
| value             | VARCHAR   | 10000000000000000                                                  |                                                              |
| registrationDate  | VARCHAR   | 1545963972                                                         |                                                              |

## 43. Table: Registrar0\_event\_HashRegistered\_unhashed\_history

| Column            | Type      | Example                                                            | Description |
| ----------------- | --------- | ------------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | 2019-06-09 01:54:33+00:00                                          | None        |
| block\_number     | INTEGER   | 7921975                                                            | None        |
| transaction\_hash | VARCHAR   | 0xe93f6e317c8d4e08b572a2548e5553b7bfe4b1860abd08d6217277ae709f163e | None        |
| log\_index        | INTEGER   | 0                                                                  | None        |
| hash              | VARCHAR   | 0xc6ac4010db3fe8490b4d816f4bacb17c63f825363989d4f6af1858abd9327390 | None        |
| owner             | VARCHAR   | 0x3c89c68847e2eee27a125e17bc6a5e2732d8a25b                         | None        |
| value             | VARCHAR   | 20000000000000000                                                  | None        |
| registrationDate  | VARCHAR   | 1533355872                                                         | None        |
| name              | VARCHAR   | infcoin                                                            | None        |

## 44. Table: Registrar0\_event\_HashReleased\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-18 04:09:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7085200                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd12b3a178bf0fae2d3353b36085093c99e3e68c7600023b148b5cdf9dccd20c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6090a6e47849629b7245dfa1ca21d94cd15878ef                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x06d31571aee254afefb23de2aab112b54fba4616cdb0311720df975c96845db8 |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 45. Table: Registrar0\_event\_NewBid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-04-24 05:15:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7628260                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ebb81569c53f67700939c9de6e239e9047387b30b8fa98c9a6b61d583707010 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6090a6e47849629b7245dfa1ca21d94cd15878ef                         | Address of the contract that produced the log                |
| hash              | VARCHAR   | 0x92da477bc0a513315a9e95788f8c193bf12ea8703ff18a13347398ac0c68f448 |                                                              |
| bidder            | VARCHAR   | 0x12cff2a28d4fe53fcf46ad642668cf6651fa8cf7                         |                                                              |
| deposit           | VARCHAR   | 10000000000000000                                                  |                                                              |

## 46. Table: ShortNameAuctionController\_event\_NameRegistered\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-28 16:09:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8828814                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa475557ef4e5a0e59b87f1262a4797a25a2ccb3f490f80a20cde54bebf445afc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x699c7f511c9e2182e89f29b3bfb68bd327919d17                         | Address of the contract that produced the log                |
| name              | VARCHAR   | sell                                                               |                                                              |
| owner             | VARCHAR   | 0x6319f3563897f889b0a6ca45c9be588696215a16                         |                                                              |

## 47. Table: ShortNameClaims\_event\_ClaimStatusChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-26 03:41:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8423511                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x645a8d127cb82d3a963d9628fc0d199099847b93cfab62605c9fcaf572b72c78 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 129                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf7c83bd0c50e7a72b55a39fe0dabf5e3a330d749                         | Address of the contract that produced the log                |
| claimId           | VARCHAR   | 0xeeed18d644f770cf8f933851ffff24a965f65db605056455aea6ab198969d787 |                                                              |
| status            | VARCHAR   | 1                                                                  |                                                              |

## 48. Table: ShortNameClaims\_event\_ClaimSubmitted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-17 02:56:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8365387                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22a0edee2fb05483f5b173becdb9f3b097957cbbcaafef4433d81daf9fff1e7c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf7c83bd0c50e7a72b55a39fe0dabf5e3a330d749                         | Address of the contract that produced the log                |
| claimed           | VARCHAR   | jsonp                                                              |                                                              |
| dnsname           | VARCHAR   | 0x056a736f6e70026d6500                                             |                                                              |
| paid              | VARCHAR   | 26950545748581506                                                  |                                                              |
| claimant          | VARCHAR   | 0xc2f47b8d0a7e807208799a30ebb959debf0b097c                         |                                                              |
| email             | VARCHAR   | jason@kiind.design                                                 |                                                              |

## 49. Table: ShortNameClaims\_event\_resolveClaim\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2019-08-26 05:12:43+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 8423914                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbae8a54023f97bc67ac0976115203c169c105ef24d2a1ad7f4a0a7dad2987570 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 142                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf7c83bd0c50e7a72b55a39fe0dabf5e3a330d749                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| claimId            | VARCHAR   | 0x8eab1fa8dc4c1714bfa9822a1f31968b1384cc59edbaf2c38018ebdf2ea83785 |                                                                                                                        |

## 50. Table: ShortNameClaims\_event\_resolveClaims\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2019-08-26 21:20:52+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 8428216                                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xeb29831b14888b81558c4cc0aa4469106e9141c67b88d5f333436b84286a9c25                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 19                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf7c83bd0c50e7a72b55a39fe0dabf5e3a330d749                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| claimIds           | VARCHAR   | 0xed14cd189e461502668b46d314427b69089511cdf3df697ccedb4e469718a27b,0x4381612dffc43fe6600edc41f49b283 |                                                                                                                        |
