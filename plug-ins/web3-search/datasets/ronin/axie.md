# axie

## 1. Table: Axie\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-28 10:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2678592                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb9c6bbdac149e6bfc2ebf527e7123332ec2c1ea588c7b1a9e9c188b8f38ac645 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 2. Table: Axie\_event\_AdminRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_oldAdmin        | VARCHAR   |                                                              |             |

## 3. Table: Axie\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 00:36:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22630819                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2c13c6de71cdc47e859c3e3a732f7f11316428c73c5f42b2bc75b4726b653abd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x49dee1f51124c163c261335ea06ff9872eca9052                         |                                                              |
| \_operator        | VARCHAR   | 0xfff9ce5f71ca6178d3beecedb61e7eff1602950e                         |                                                              |
| \_approved        | VARCHAR   | true                                                               |                                                              |

## 4. Table: Axie\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-21 05:52:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9494229                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1801de3f96e9d1cbce3c9e51749c4718a4984016797f7ca3a7a54eac2fda1fbe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x2416abc3664bee0a2c108ce6857a92fecc256f90                         |                                                              |
| \_approved        | VARCHAR   | 0xca8c3dd14d58ce6a145b9f242fa17590948e6b73                         |                                                              |
| \_tokenId         | VARCHAR   | 2317347                                                            |                                                              |

## 5. Table: Axie\_event\_AxieEvolved\_history

| Column            | Type                        | Example                                                                                              | Description                                                  |
| ----------------- | --------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP                   | 2022-12-11 13:03:34+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER                     | 19674933                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR                     | 0x001b909b60df624d5e33d79884cdbeed3951693f2489164b83f3b32cd689a01d                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER                     | 0                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR                     | 0x32950db2a7164ae833121501c797d79e7b79d74c                                                           | Address of the contract that produced the log                |
| \_axieId          | VARCHAR                     | 11593015                                                                                             |                                                              |
| \_genes           | STRUCT\<x STRING, y STRING> | {'x': '1607011640244166917231097051887759089736690290556411783955202', 'y': '17668495924791101073271 |                                                              |
| \_genes.x         | VARCHAR                     | 1607011640244166917231097051887759089736690290556411783955202                                        | None                                                         |
| \_genes.y         | VARCHAR                     | 1766849592479110107327122345274330138403943576299861344333986898536055554                            | None                                                         |

## 6. Table: Axie\_event\_AxieMinted\_history

| Column            | Type                                                                                                                          | Example                                                                                              | Description                                                  |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP                                                                                                                     | 2023-02-04 03:31:57+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER                                                                                                                       | 21238452                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR                                                                                                                       | 0x7033ba6aa57450f4d01d84cde962d8670915149b1e2f2ba1e204b2145b624a29                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER                                                                                                                       | 4                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR                                                                                                                       | 0x32950db2a7164ae833121501c797d79e7b79d74c                                                           | Address of the contract that produced the log                |
| \_axieId          | VARCHAR                                                                                                                       | 11635778                                                                                             |                                                              |
| \_axie            | STRUCT\<sireId STRING, matronId STRING, birthDate STRING, genes STRUCT\<x STRING, y STRING>, breedCount STRING, level STRING> | {'sireId': '0', 'matronId': '0', 'birthDate': '1675481517', 'genes': {'x': '144740111546645356765680 |                                                              |
| \_axie.sireId     | VARCHAR                                                                                                                       | 0                                                                                                    | None                                                         |
| \_axie.matronId   | VARCHAR                                                                                                                       | 0                                                                                                    | None                                                         |
| \_axie.birthDate  | VARCHAR                                                                                                                       | 1675481517                                                                                           | None                                                         |
| \_axie.genes      | STRUCT\<x STRING, y STRING>                                                                                                   | {'x': '14474011154664535676568008633771928844682596865223023271937353267811669050378', 'y': '1767173 | None                                                         |
| \_axie.genes.x    | VARCHAR                                                                                                                       | 14474011154664535676568008633771928844682596865223023271937353267811669050378                        | None                                                         |
| \_axie.genes.y    | VARCHAR                                                                                                                       | 1767173994242566824952599218275304929769105714064666809435297862347998474                            | None                                                         |
| \_axie.breedCount | VARCHAR                                                                                                                       | 0                                                                                                    | None                                                         |
| \_axie.level      | VARCHAR                                                                                                                       | 0                                                                                                    | None                                                         |

## 7. Table: Axie\_event\_AxieSpawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 15:19:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17292937                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d24eb063f22387802a9fb687c65c07b28af68ee1c8c1a847d4f7928ce953f82 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_axieId          | VARCHAR   | 11483936                                                           |                                                              |

## 8. Table: Axie\_event\_AxieggMinted\_history

| Column                 | Type                                                                                                                          | Example                                                                                              | Description                                                  |
| ---------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP                                                                                                                     | 2021-10-13 19:57:07+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER                                                                                                                       | 7527614                                                                                              | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR                                                                                                                       | 0x69570e6b0c54ca730207f14dc8fd4b00d3d75e5b5d85780a9434de3e06c56e69                                   | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER                                                                                                                       | 3                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR                                                                                                                       | 0x32950db2a7164ae833121501c797d79e7b79d74c                                                           | Address of the contract that produced the log                |
| \_axieId               | VARCHAR                                                                                                                       | 9671                                                                                                 |                                                              |
| \_axie                 | STRUCT\<sireId STRING, matronId STRING, birthDate STRING, genes STRUCT\<x STRING, y STRING>, breedCount STRING, level STRING> | {'sireId': '1648', 'matronId': '1327', 'birthDate': '1541593344', 'genes': {'x': '0', 'y': '0'}, 'br |                                                              |
| \_axie.sireId          | VARCHAR                                                                                                                       | 1648                                                                                                 | None                                                         |
| \_axie.matronId        | VARCHAR                                                                                                                       | 1327                                                                                                 | None                                                         |
| \_axie.birthDate       | VARCHAR                                                                                                                       | 1541593344                                                                                           | None                                                         |
| \_axie.genes           | STRUCT\<x STRING, y STRING>                                                                                                   | {'x': '0', 'y': '0'}                                                                                 | None                                                         |
| \_axie.genes.x         | VARCHAR                                                                                                                       | 0                                                                                                    | None                                                         |
| \_axie.genes.y         | VARCHAR                                                                                                                       | 0                                                                                                    | None                                                         |
| \_axie.breedCount      | VARCHAR                                                                                                                       | 0                                                                                                    | None                                                         |
| \_axie.level           | VARCHAR                                                                                                                       | 0                                                                                                    | None                                                         |
| \_axiegg               | STRUCT\<sireGenes STRUCT\<x STRING, y STRING>, matronGenes STRUCT\<x STRING, y STRING>>                                       | {'sireGenes': {'x': '4820887848465713675262806947933654799170232132810486533080066', 'y': '176738796 |                                                              |
| \_axiegg.sireGenes     | STRUCT\<x STRING, y STRING>                                                                                                   | {'x': '4820887848465713675262806947933654799170232132810486533080066', 'y': '17673879621809751566608 | None                                                         |
| \_axiegg.sireGenes.x   | VARCHAR                                                                                                                       | 4820887848465713675262806947933654799170232132810486533080066                                        | None                                                         |
| \_axiegg.sireGenes.y   | VARCHAR                                                                                                                       | 1767387962180975156660804361715934713447070779371659064137850103688904966                            | None                                                         |
| \_axiegg.matronGenes   | STRUCT\<x STRING, y STRING>                                                                                                   | {'x': '4820838772619653456982692130050733640763744499863978166485250', 'y': '17671722826092574437901 | None                                                         |
| \_axiegg.matronGenes.x | VARCHAR                                                                                                                       | 4820838772619653456982692130050733640763744499863978166485250                                        | None                                                         |
| \_axiegg.matronGenes.y | VARCHAR                                                                                                                       | 1767172282609257443790182545317113248339095394161893787927417304127652358                            | None                                                         |

## 9. Table: Axie\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-20 10:04:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5960615                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85ce57eea07015b1e8e58ebc953d151ecc38ed081c93b99285fa96e2cef1166b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_minter          | VARCHAR   | 0xbc4319a64d1aa5396735c3fec426016fe1c01721                         |                                                              |

## 10. Table: Axie\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-20 10:11:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5960772                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x286eaccbec59ff4382db03ec48ab2751a439d7443967e1931206ffe4ca8dec9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_minter          | VARCHAR   | 0xbcba374d3ae40a19e41c00331b66642945a773f2                         |                                                              |

## 11. Table: Axie\_event\_NonceUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_nonce           | VARCHAR   |                                                              |             |

## 12. Table: Axie\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-20 07:25:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3307910                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74f12394f70c2afc71000624217fda827504f19534e1212044479af0125d9e60 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |

## 13. Table: Axie\_event\_PermissionSetAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-11 13:11:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16206231                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x72aaaa7475da2f9188227bcf1ea23154162ab1fcd3608e4607b1ea4a141a2490 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x01289f9da73448cd65b7143524dd70fe4cd46175                         |                                                              |
| \_operator        | VARCHAR   | 0x2368dfed532842db89b470fde9fd584d48d4f644                         |                                                              |
| \_approved        | VARCHAR   | true                                                               |                                                              |

## 14. Table: Axie\_event\_PermissionSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-11 11:08:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7459442                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x57605f1f6e7198a718f015d2229ee66ee9283f86c307ba20b9e43b2742ea9e32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 214                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0x7ae66c960fab044e74567c06970ddd2b6a726e8d                         |                                                              |
| \_operator        | VARCHAR   | 0xef3c63d058a0536025ae6780182d0494a5d25c99                         |                                                              |
| \_funcSig         | VARCHAR   | 0x02cdc770                                                         |                                                              |
| \_approved        | VARCHAR   | true                                                               |                                                              |

## 15. Table: Axie\_event\_SeederAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-28 05:59:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3536588                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc13644f39bb2c63a212c327d67e9b2a160e51a56ceb9111ca9c13a04e8019fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_seeder          | VARCHAR   | 0xf76f8fca486ed06bb7e24bcc351855409cd15665                         |                                                              |

## 16. Table: Axie\_event\_SeederRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-28 07:03:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3537876                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17037155f788f1768d63aae334afc54db6e85f02fa6d75d61236bc47f5518807 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_seeder          | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 17. Table: Axie\_event\_SpenderUnwhitelisted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_spender         | VARCHAR   |                                                              |             |

## 18. Table: Axie\_event\_SpenderWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-28 11:14:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2678892                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe418af915580d58bf752484c0ee33fd980d066dc1b56784390bf895f58247dce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_spender         | VARCHAR   | 0x2da06d60bd413bcbb6586430857433bd9d3a4be4                         |                                                              |

## 19. Table: Axie\_event\_TokenOperatorSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-15 04:43:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9320088                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xef1d94e8141d14111168c8816d9f30c420611a83068cd6b33a4e5601b8e0d016 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_tokenId         | VARCHAR   | 2317347                                                            |                                                              |
| \_operator        | VARCHAR   | 0xca8c3dd14d58ce6a145b9f242fa17590948e6b73                         |                                                              |
| \_approved        | VARCHAR   | true                                                               |                                                              |

## 20. Table: Axie\_event\_TokenPermissionSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_funcSig         | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 21. Table: Axie\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-18 12:26:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19017110                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x724ad40c600b4c511886dd0197918884192ec09ee19d58b2cbdf45efe955ee1f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x73f9fedb49860632c7afe149758d4bc34303d179                         |                                                              |
| \_to              | VARCHAR   | 0x000f2d88d5142f0e252952a881ce143d9bcb86d0                         |                                                              |
| \_tokenId         | VARCHAR   | 9805490                                                            |                                                              |

## 22. Table: Axie\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-20 07:25:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3307917                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x416a1b88c2ce562820ace4d56fb0632135ed6f519f64ad37cda89d6727294cce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x32950db2a7164ae833121501c797d79e7b79d74c                         | Address of the contract that produced the log                |

## 23. Table: Exchange\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 11:57:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2622168                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x48ea343b8788fee3e9133bae9cfa55bf79c832631df5f601a25a1d7d4c84841b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2da06d60bd413bcbb6586430857433bd9d3a4be4                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 24. Table: Exchange\_event\_AdminRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_oldAdmin        | VARCHAR   |                                                              |             |

## 25. Table: Exchange\_event\_ListingCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-28 08:28:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11483986                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf952cd7ca58b58490de4bb4a333903ed61bde78ad1c04aa68e464335dabd2371 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2da06d60bd413bcbb6586430857433bd9d3a4be4                         | Address of the contract that produced the log                |
| \_creator         | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         |                                                              |
| \_listingIndex    | VARCHAR   | 8339393                                                            |                                                              |

## 26. Table: Exchange\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 11:58:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2622174                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x096a29ddc86cd24f7ec5f96b3d415f9e311418c076f769651bea3617352c07db | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2da06d60bd413bcbb6586430857433bd9d3a4be4                         | Address of the contract that produced the log                |
| \_operator        | VARCHAR   | 0x09a504fc612d91d63842eb596c2a67d289813a2d                         |                                                              |

## 27. Table: Exchange\_event\_OperatorRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_operator        | VARCHAR   |                                                              |             |

## 28. Table: Exchange\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-08 07:34:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16113107                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd2d9ccfced8ccfd78e8578ae9f15003415022a9e789cc4bb6dc8cb21c7166331 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2da06d60bd413bcbb6586430857433bd9d3a4be4                         | Address of the contract that produced the log                |

## 29. Table: Exchange\_event\_TokenAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 11:57:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2622168                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x48ea343b8788fee3e9133bae9cfa55bf79c832631df5f601a25a1d7d4c84841b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2da06d60bd413bcbb6586430857433bd9d3a4be4                         | Address of the contract that produced the log                |
| \_token           | VARCHAR   | 0xc99a6a985ed2cac1ef41640596c5a5f9f4e19ef5                         |                                                              |

## 30. Table: Exchange\_event\_TokenRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_token           | VARCHAR   |                                                              |             |

## 31. Table: Exchange\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 32. Table: Gateway\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-25 11:28:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 783                                                                | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0d1d9beee14140d572db6bfdf2b30a1ca32e41dc84272dcf7b9b0e3c96fd64ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe35d62ebe18413d96ca2a2f7cf215bb21a406b4b                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 33. Table: Gateway\_event\_AdminRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_oldAdmin        | VARCHAR   |                                                              |             |

## 34. Table: Gateway\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-28 15:34:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13191590                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe806b36b9f337e8512dd806a5845451232a0da52c66f2921c4f7e222bd5e19fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe35d62ebe18413d96ca2a2f7cf215bb21a406b4b                         | Address of the contract that produced the log                |

## 35. Table: Gateway\_event\_RequestTokenWithdrawalSigAgain\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-04-04 09:18:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 12492880                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x8cb366a28dc6986ff60d812d26466e9378d40082bc06b5a57f5ae5db754a781a | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 109                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xe35d62ebe18413d96ca2a2f7cf215bb21a406b4b                         | Address of the contract that produced the log                |
| \_withdrawalId     | VARCHAR   | 1063976                                                            |                                                              |
| \_owner            | VARCHAR   | 0xa049ee373b70cc99719797a46b5e358b91bfe6ac                         |                                                              |
| \_tokenAddress     | VARCHAR   | 0xc99a6a985ed2cac1ef41640596c5a5f9f4e19ef5                         |                                                              |
| \_mainchainAddress | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| \_standard         | VARCHAR   | 20                                                                 |                                                              |
| \_tokenNumber      | VARCHAR   | 9719962362553314906                                                |                                                              |

## 36. Table: Gateway\_event\_TokenDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-13 20:46:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2258335                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x860fd84f8597237897894ae8318d0dc7b8bc1826ea720f5103c988662698018a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe35d62ebe18413d96ca2a2f7cf215bb21a406b4b                         | Address of the contract that produced the log                |
| depositId         | VARCHAR   | 1458                                                               |                                                              |
| owner             | VARCHAR   | 0x887c1e3f21d3b33a5bebc2ffd4d144e977448299                         |                                                              |
| tokenAddress      | VARCHAR   | 0xc99a6a985ed2cac1ef41640596c5a5f9f4e19ef5                         |                                                              |
| tokenNumber       | VARCHAR   | 29000000000000000                                                  |                                                              |

## 37. Table: Gateway\_event\_TokenWithdrew\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2021-11-13 00:18:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 8396520                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x199f4979c25261f9c6c04d7248d78accd28a4b4fcdfde71da50796a03514cf31 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xe35d62ebe18413d96ca2a2f7cf215bb21a406b4b                         | Address of the contract that produced the log                |
| \_withdrawId       | VARCHAR   | 998806                                                             |                                                              |
| \_owner            | VARCHAR   | 0x17513166d0b94a46db0785624fdcd92a3ce3843a                         |                                                              |
| \_tokenAddress     | VARCHAR   | 0x0b7007c13325c48911f73a2dad5fa5dcbf808adc                         |                                                              |
| \_mainchainAddress | VARCHAR   | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                         |                                                              |
| \_standard         | VARCHAR   | 20                                                                 |                                                              |
| \_tokenNumber      | VARCHAR   | 50000000                                                           |                                                              |

## 38. Table: Gateway\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 39. Table: LandItem\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 08:48:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2618382                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9aee6d7beb8f990e70d06ac71a7cbeb4329c1b75fa82dbfa1d5c3d64b5e14517 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96660f0e4a3e9bc7388925d245a6d4d79e21259                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |
| \_newAdmin        | VARCHAR   | 0xed4a9f48a62fb6fdcfb45bb00c9f61d1a436e58c                         |                                                              |

## 40. Table: LandItem\_event\_AdminRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_oldAdmin        | VARCHAR   |                                                              |             |

## 41. Table: LandItem\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-08 02:02:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26544338                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x190a1ce03779c67fe7b0a301396f5dbe4ef84261076f8df4ad4a9496f8fb3229 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96660f0e4a3e9bc7388925d245a6d4d79e21259                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0xb7b4d65cb5a0c44ccb9019ca74745686188173db                         |                                                              |
| \_operator        | VARCHAR   | 0xfff9ce5f71ca6178d3beecedb61e7eff1602950e                         |                                                              |
| \_approved        | VARCHAR   | true                                                               |                                                              |

## 42. Table: LandItem\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_owner           | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |
| \_tokenId         | VARCHAR   |                                                              |             |

## 43. Table: LandItem\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-19 07:19:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10330728                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1fab61955d17ef530fdfd1070916af651cd44c40905f0a27d8556d25c0ee94e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 155                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96660f0e4a3e9bc7388925d245a6d4d79e21259                         | Address of the contract that produced the log                |
| \_minter          | VARCHAR   | 0x144697847f4bf184534af5945abe0fb5f1b14fba                         |                                                              |

## 44. Table: LandItem\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-22 10:09:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7775035                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4e50e1f1dd5fcb1a948b948b112fc86625f2637c0ef48f8e7b38eab96088e007 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96660f0e4a3e9bc7388925d245a6d4d79e21259                         | Address of the contract that produced the log                |
| \_minter          | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 45. Table: LandItem\_event\_NonceUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_nonce           | VARCHAR   |                                                              |             |

## 46. Table: LandItem\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 47. Table: LandItem\_event\_PermissionSetAll\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_owner           | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 48. Table: LandItem\_event\_PermissionSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_owner           | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_funcSig         | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 49. Table: LandItem\_event\_SpenderUnwhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 10:59:38+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2621001                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38e396ea765c4c24bcfb8f34ecf50c9e7f34904010cc7be481b20e4e5b413e69 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96660f0e4a3e9bc7388925d245a6d4d79e21259                         | Address of the contract that produced the log                |
| \_spender         | VARCHAR   | 0x1e9457cb10ba980234e0bd33d3a4fad241629256                         |                                                              |

## 50. Table: LandItem\_event\_SpenderWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-01 09:25:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 199910                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcef86ce5dca04fde4574d1923ef7e5b9ea9345bb867d22502f7d7dff88c4aec5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96660f0e4a3e9bc7388925d245a6d4d79e21259                         | Address of the contract that produced the log                |
| \_spender         | VARCHAR   | 0x65776dacd0788ee994be9fd7f5216cf96e64414c                         |                                                              |

## 51. Table: LandItem\_event\_TokenOperatorSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 52. Table: LandItem\_event\_TokenPermissionSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_funcSig         | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 53. Table: LandItem\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 20:31:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25731579                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xff4ce932181381c874cbf5d609babf31bd7c9359dc8abc8e80a9d319c791fbf5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa96660f0e4a3e9bc7388925d245a6d4d79e21259                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x144697847f4bf184534af5945abe0fb5f1b14fba                         |                                                              |
| \_to              | VARCHAR   | 0xecafd2a04c9a951575982ca4581b713ce794ca1c                         |                                                              |
| \_tokenId         | VARCHAR   | 69417602851871446546528419916080715166584                          |                                                              |

## 54. Table: LandItem\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 55. Table: Land\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 08:48:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2618379                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb84209fb5cafc1bbe0c5ac6b332f38e4d489d5dd048758f5f594d136d5d9fdd6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c811e3c958e190f5ec15fb376533a3398620500                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |
| \_newAdmin        | VARCHAR   | 0xed4a9f48a62fb6fdcfb45bb00c9f61d1a436e58c                         |                                                              |

## 56. Table: Land\_event\_AdminRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_oldAdmin        | VARCHAR   |                                                              |             |

## 57. Table: Land\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-21 23:13:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21744102                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x967de485009d126e2489edf0d3d377da472b5dab68c29f4b7afb01536b9e63b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c811e3c958e190f5ec15fb376533a3398620500                         | Address of the contract that produced the log                |
| \_owner           | VARCHAR   | 0xc98fc0171a883ad5fa1181f7d738d75f2b82e077                         |                                                              |
| \_operator        | VARCHAR   | 0x2368dfed532842db89b470fde9fd584d48d4f644                         |                                                              |
| \_approved        | VARCHAR   | true                                                               |                                                              |

## 58. Table: Land\_event\_Approval\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_owner           | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |
| \_tokenId         | VARCHAR   |                                                              |             |

## 59. Table: Land\_event\_MinterAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-01 09:24:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 199895                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e838cd21abbea408dd239cc6efcd2ab665d2224af61e3550f0fbedd8e336420 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c811e3c958e190f5ec15fb376533a3398620500                         | Address of the contract that produced the log                |
| \_minter          | VARCHAR   | 0x432804802092cd6f6fb37a8f1b702089611ce101                         |                                                              |

## 60. Table: Land\_event\_MinterRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-22 10:08:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7775032                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x775834e3668ae9c1527b1936510e63679705c48a17888ed17dcc5d8c7519ce36 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c811e3c958e190f5ec15fb376533a3398620500                         | Address of the contract that produced the log                |
| \_minter          | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 61. Table: Land\_event\_NonceUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_nonce           | VARCHAR   |                                                              |             |

## 62. Table: Land\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 63. Table: Land\_event\_PermissionSetAll\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_owner           | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 64. Table: Land\_event\_PermissionSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_owner           | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_funcSig         | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 65. Table: Land\_event\_SpenderUnwhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 10:59:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2620998                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf5c28eb365f6c9edd4b4d97a012f6d7deed84d8798c12ac65ec81f1d040f30e1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c811e3c958e190f5ec15fb376533a3398620500                         | Address of the contract that produced the log                |
| \_spender         | VARCHAR   | 0x1e9457cb10ba980234e0bd33d3a4fad241629256                         |                                                              |

## 66. Table: Land\_event\_SpenderWhitelisted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-01 09:24:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 199905                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0420dbb32c1aeb62812af17ec30f946d516d3f5ab3c93c8114a55ecf940ee080 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c811e3c958e190f5ec15fb376533a3398620500                         | Address of the contract that produced the log                |
| \_spender         | VARCHAR   | 0x65776dacd0788ee994be9fd7f5216cf96e64414c                         |                                                              |

## 67. Table: Land\_event\_TokenOperatorSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 68. Table: Land\_event\_TokenPermissionSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_tokenId         | VARCHAR   |                                                              |             |
| \_operator        | VARCHAR   |                                                              |             |
| \_funcSig         | VARCHAR   |                                                              |             |
| \_approved        | VARCHAR   |                                                              |             |

## 69. Table: Land\_event\_Transfer\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 14:22:38+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3489060                                                                        | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaa21c040a6de76d8046c0e37859276e11d306f5392f301fce19951a3fd64fbf6             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 54                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c811e3c958e190f5ec15fb376533a3398620500                                     | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0x0000000000000000000000000000000000000000                                     |                                                              |
| \_to              | VARCHAR   | 0x381657a078294b43e3be6487ce01eb661ef5c884                                     |                                                              |
| \_tokenId         | VARCHAR   | 115792089237316195417293883273301227099642666250061051525540919587547153170431 |                                                              |

## 70. Table: Land\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 71. Table: Marketplace\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 11:58:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2622186                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x66e99cc545da2d8c9476304b2d196c9110e0ced2ed7274e363204f118e1730d2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 72. Table: Marketplace\_event\_AdminRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_oldAdmin        | VARCHAR   |                                                              |             |

## 73. Table: Marketplace\_event\_AuctionCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-24 22:25:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3441126                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b1dc26d2a63e3a4ea9bac01c62e63a2cdde8e0a58549e316fa81726c314ebf3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         | Address of the contract that produced the log                |
| \_seller          | VARCHAR   | 0xa0ba8c4d87e5ed5e475a555307cc49d80b9e17e7                         |                                                              |
| \_listingIndex    | VARCHAR   | 79780                                                              |                                                              |

## 74. Table: Marketplace\_event\_AuctionCreated\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2022-04-05 06:59:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 12518912                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0xbd512a12f28eff6b62344353ea145be5f7ba92086b597a3b20559b3d6ecb362f | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         | Address of the contract that produced the log                |
| \_seller             | VARCHAR   | 0xbb60db8cd299bfe9c4236e430a83204a64a61c81                         |                                                              |
| \_listingIndex       | VARCHAR   | 7837424                                                            |                                                              |
| \_startingPrices     | VARCHAR   | 37000000000000000                                                  |                                                              |
| \_endingPrices       | VARCHAR   | 37000000000000000                                                  |                                                              |
| \_exchangeTokens     | VARCHAR   | 0xc99a6A985eD2Cac1ef41640596C5A5f9F4E19Ef5                         |                                                              |
| \_durations          | VARCHAR   | 86400                                                              |                                                              |
| \_startingTimestamps | VARCHAR   | 1649141996                                                         |                                                              |

## 75. Table: Marketplace\_event\_AuctionSuccessful\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-04 05:03:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15994877                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf99aaf5f8943b21689de608eb7db84afb6403cbc67dcff1b4157caf303ed2b6a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         | Address of the contract that produced the log                |
| \_seller          | VARCHAR   | 0x00230b575b9c7be68a48e80b2a2985441907c6c1                         |                                                              |
| \_buyer           | VARCHAR   | 0x306d8159dd2fe1ebb28d83e8466e612e6049e21c                         |                                                              |
| \_listingIndex    | VARCHAR   | 7883948                                                            |                                                              |
| \_token           | VARCHAR   | 0xc99a6a985ed2cac1ef41640596c5a5f9f4e19ef5                         |                                                              |
| \_totalPrice      | VARCHAR   | 4000000000000000                                                   |                                                              |

## 76. Table: Marketplace\_event\_OperatorAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-26 13:07:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2623554                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4fececdf63a79dc6af9decf3df5832db4f0665d13c42c4bb78fa13e6d4c48f4f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         | Address of the contract that produced the log                |
| \_operator        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 77. Table: Marketplace\_event\_OperatorRemoved\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-22 10:09:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7775038                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5a46d3dbbadf3e73f69c79f3c338b9cf002aeb5676d947ff47c08adef4cf8af9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         | Address of the contract that produced the log                |
| \_operator        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 78. Table: Marketplace\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-08 07:31:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16113055                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88972cc30619c53ae47c94dcea074bed61272d11e1d5c2bb1307355a9d9acd84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         | Address of the contract that produced the log                |

## 79. Table: Marketplace\_event\_TokenAuctionCancelled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_seller          | VARCHAR   |                                                              |             |
| \_listingIndex    | VARCHAR   |                                                              |             |
| \_exchangeTokens  | VARCHAR   |                                                              |             |

## 80. Table: Marketplace\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-03 05:05:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3708315                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1f095d40a471a23800cbc2d59ee9669cc777ee9c2af8d9124cbd4c681a7dd91a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x213073989821f738a7ba3520c3d31a1f9ad31bbd                         | Address of the contract that produced the log                |

## 81. Table: OfferAuction\_event\_AdminChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-03 08:05:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 255924                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x014ec065129fccf0b0dd9d5c36b323bff069116470d19f68f4107a8f899d598f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5b16d12a0c2c88db94115968abd7afa78b6bc504                         | Address of the contract that produced the log                |
| \_oldAdmin        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| \_newAdmin        | VARCHAR   | 0xf20fe980677d703a0a1fe5f38cc9ab0f1452ca11                         |                                                              |

## 82. Table: OfferAuction\_event\_AdminRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_oldAdmin        | VARCHAR   |                                                              |             |

## 83. Table: OfferAuction\_event\_OfferAccepted\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_seller          | VARCHAR   |                                                              |             |
| \_buyer           | VARCHAR   |                                                              |             |
| \_listingIndex    | VARCHAR   |                                                              |             |
| \_token           | VARCHAR   |                                                              |             |
| \_price           | VARCHAR   |                                                              |             |

## 84. Table: OfferAuction\_event\_OfferCanceled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_offerer         | VARCHAR   |                                                              |             |
| \_token           | VARCHAR   |                                                              |             |
| \_listingIndex    | VARCHAR   |                                                              |             |

## 85. Table: OfferAuction\_event\_OfferCreated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_offerer         | VARCHAR   |                                                              |             |
| \_listingIndex    | VARCHAR   |                                                              |             |
| \_token           | VARCHAR   |                                                              |             |
| \_price           | VARCHAR   |                                                              |             |

## 86. Table: OfferAuction\_event\_OfferRejected\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_offerer         | VARCHAR   |                                                              |             |
| \_token           | VARCHAR   |                                                              |             |
| \_listingIndex    | VARCHAR   |                                                              |             |

## 87. Table: OfferAuction\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 88. Table: OfferAuction\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 89. Table: RoninGatewayV2\_event\_Deposited\_history

| Column                      | Type                                                                                                                                                                                                                  | Example                                                                                              | Description                                                  |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP                                                                                                                                                                                                             | 2023-01-03 18:41:31+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER                                                                                                                                                                                                               | 20340521                                                                                             | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR                                                                                                                                                                                                               | 0x261fe5186b11071f44ca4016127e87fa1ee6b8afb27bf237eeab0badd2936a40                                   | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER                                                                                                                                                                                                               | 1                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR                                                                                                                                                                                                               | 0x0cf8ff40a508bdbc39fbe1bb679dcba64e65c7df                                                           | Address of the contract that produced the log                |
| receiptHash                 | VARCHAR                                                                                                                                                                                                               | 0xbf97c5f2fb8b09916691e68ddf60cadebc82b72f669a6929e144d6281f24e09b                                   |                                                              |
| receipt                     | STRUCT\<id STRING, kind STRING, mainchain STRUCT\<addr STRING, tokenAddr STRING, chainId STRING>, ronin STRUCT\<addr STRING, tokenAddr STRING, chainId STRING>, info STRUCT\<erc STRING, id STRING, quantity STRING>> | {'id': '24673', 'kind': '0', 'mainchain': {'addr': '0x7c4658033dbdc99de994f93a260c46a93aaea056', 'to |                                                              |
| receipt.id                  | VARCHAR                                                                                                                                                                                                               | 24673                                                                                                | None                                                         |
| receipt.kind                | VARCHAR                                                                                                                                                                                                               | 0                                                                                                    | None                                                         |
| receipt.mainchain           | STRUCT\<addr STRING, tokenAddr STRING, chainId STRING>                                                                                                                                                                | {'addr': '0x7c4658033dbdc99de994f93a260c46a93aaea056', 'tokenAddr': '0xa0b86991c6218b36c1d19d4a2e9eb | None                                                         |
| receipt.mainchain.addr      | VARCHAR                                                                                                                                                                                                               | 0x7c4658033dbdc99de994f93a260c46a93aaea056                                                           | None                                                         |
| receipt.mainchain.tokenAddr | VARCHAR                                                                                                                                                                                                               | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                                                           | None                                                         |
| receipt.mainchain.chainId   | VARCHAR                                                                                                                                                                                                               | 1                                                                                                    | None                                                         |
| receipt.ronin               | STRUCT\<addr STRING, tokenAddr STRING, chainId STRING>                                                                                                                                                                | {'addr': '0xf215a16ad975224b9e7a8bd32856a2dd316d01c0', 'tokenAddr': '0x0b7007c13325c48911f73a2dad5fa | None                                                         |
| receipt.ronin.addr          | VARCHAR                                                                                                                                                                                                               | 0xf215a16ad975224b9e7a8bd32856a2dd316d01c0                                                           | None                                                         |
| receipt.ronin.tokenAddr     | VARCHAR                                                                                                                                                                                                               | 0x0b7007c13325c48911f73a2dad5fa5dcbf808adc                                                           | None                                                         |
| receipt.ronin.chainId       | VARCHAR                                                                                                                                                                                                               | 2020                                                                                                 | None                                                         |
| receipt.info                | STRUCT\<erc STRING, id STRING, quantity STRING>                                                                                                                                                                       | {'erc': '0', 'id': '0', 'quantity': '8970000'}                                                       | None                                                         |
| receipt.info.erc            | VARCHAR                                                                                                                                                                                                               | 0                                                                                                    | None                                                         |
| receipt.info.id             | VARCHAR                                                                                                                                                                                                               | 0                                                                                                    | None                                                         |
| receipt.info.quantity       | VARCHAR                                                                                                                                                                                                               | 8970000                                                                                              | None                                                         |

## 90. Table: RoninGatewayV2\_event\_MainchainWithdrew\_history

| Column                      | Type                                                                                                                                                                                                                  | Example                                                                                              | Description                                                  |
| --------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp            | TIMESTAMP                                                                                                                                                                                                             | 2023-04-19 11:40:04+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number               | INTEGER                                                                                                                                                                                                               | 23359963                                                                                             | The block number where this event was emitted                |
| transaction\_hash           | VARCHAR                                                                                                                                                                                                               | 0x398b46780207b2d152864e740da2af4272e4d1a50906ac18a46b62864d8d4d8b                                   | Hash of the transactions in which this event was emitted     |
| log\_index                  | INTEGER                                                                                                                                                                                                               | 0                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address           | VARCHAR                                                                                                                                                                                                               | 0x0cf8ff40a508bdbc39fbe1bb679dcba64e65c7df                                                           | Address of the contract that produced the log                |
| receiptHash                 | VARCHAR                                                                                                                                                                                                               | 0xdefeb0a569d5514d108f6b6552de0602ce8634cfd3afebf10fde10a14229f0e3                                   |                                                              |
| receipt                     | STRUCT\<id STRING, kind STRING, mainchain STRUCT\<addr STRING, tokenAddr STRING, chainId STRING>, ronin STRUCT\<addr STRING, tokenAddr STRING, chainId STRING>, info STRUCT\<erc STRING, id STRING, quantity STRING>> | {'id': '135000', 'kind': '1', 'mainchain': {'addr': '0x67500462ac5a6943285ea7307f095b11fcb418f3', 't |                                                              |
| receipt.id                  | VARCHAR                                                                                                                                                                                                               | 135000                                                                                               | None                                                         |
| receipt.kind                | VARCHAR                                                                                                                                                                                                               | 1                                                                                                    | None                                                         |
| receipt.mainchain           | STRUCT\<addr STRING, tokenAddr STRING, chainId STRING>                                                                                                                                                                | {'addr': '0x67500462ac5a6943285ea7307f095b11fcb418f3', 'tokenAddr': '0xa0b86991c6218b36c1d19d4a2e9eb | None                                                         |
| receipt.mainchain.addr      | VARCHAR                                                                                                                                                                                                               | 0x67500462ac5a6943285ea7307f095b11fcb418f3                                                           | None                                                         |
| receipt.mainchain.tokenAddr | VARCHAR                                                                                                                                                                                                               | 0xa0b86991c6218b36c1d19d4a2e9eb0ce3606eb48                                                           | None                                                         |
| receipt.mainchain.chainId   | VARCHAR                                                                                                                                                                                                               | 1                                                                                                    | None                                                         |
| receipt.ronin               | STRUCT\<addr STRING, tokenAddr STRING, chainId STRING>                                                                                                                                                                | {'addr': '0x384e4267b19f65ab477fe048b568c5edb0b96e5b', 'tokenAddr': '0x0b7007c13325c48911f73a2dad5fa | None                                                         |
| receipt.ronin.addr          | VARCHAR                                                                                                                                                                                                               | 0x384e4267b19f65ab477fe048b568c5edb0b96e5b                                                           | None                                                         |
| receipt.ronin.tokenAddr     | VARCHAR                                                                                                                                                                                                               | 0x0b7007c13325c48911f73a2dad5fa5dcbf808adc                                                           | None                                                         |
| receipt.ronin.chainId       | VARCHAR                                                                                                                                                                                                               | 2020                                                                                                 | None                                                         |
| receipt.info                | STRUCT\<erc STRING, id STRING, quantity STRING>                                                                                                                                                                       | {'erc': '0', 'id': '0', 'quantity': '654807626'}                                                     | None                                                         |
| receipt.info.erc            | VARCHAR                                                                                                                                                                                                               | 0                                                                                                    | None                                                         |
| receipt.info.id             | VARCHAR                                                                                                                                                                                                               | 0                                                                                                    | None                                                         |
| receipt.info.quantity       | VARCHAR                                                                                                                                                                                                               | 654807626                                                                                            | None                                                         |

## 91. Table: Validator\_event\_ThresholdUpdated\_history

| Column              | Type      | Example                                                      | Description |
| ------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number       | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index          | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address   | VARCHAR   | Address of the contract that produced the log                |             |
| \_id                | VARCHAR   |                                                              |             |
| numerator           | VARCHAR   |                                                              |             |
| denominator         | VARCHAR   |                                                              |             |
| previousNumerator   | VARCHAR   |                                                              |             |
| previousDenominator | VARCHAR   |                                                              |             |

## 92. Table: Validator\_event\_ValidatorAdded\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_id              | VARCHAR   |                                                              |             |
| validator         | VARCHAR   |                                                              |             |

## 93. Table: Validator\_event\_ValidatorRemoved\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_id              | VARCHAR   |                                                              |             |
| validator         | VARCHAR   |                                                              |             |
