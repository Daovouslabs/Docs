# sushiswap

## 1. Table: BentoBoxV1\_event\_LogDeploy\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-18 20:15:25+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12660521                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe8b064ec65202c9a6622af4fe2e55b95f892829a38617321443b74aec42fff7e                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 340                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf5bce5077908a1b7370b9ae04adc565ebd643966                                                           | Address of the contract that produced the log                |
| masterContract    | VARCHAR   | 0x2cba6ab6574646badc84f0544d05059e57a5dc42                                                           |                                                              |
| data              | VARCHAR   | 0x0000000000000000000000007d1afa7b718fb893db30a3abc0cfc608aacfebb0000000000000000000000000a0b86991c6 |                                                              |
| cloneAddress      | VARCHAR   | 0xe83cbc07d4df1f3ba8fd451f9e56b012402e64ca                                                           |                                                              |

## 2. Table: KashiPairV1\_event\_LogBorrow\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-09 05:35:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12398315                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x21e17e77818c51abc644f3d8bd2d4c7630d787deb35258a0584c48408e8e12ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 261                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6eafe077df3ad19ade1ce1abdf8bdf2133704f89                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x774facd1685bca4a978f6097ed69c5ea0b158a65                         |                                                              |
| to                | VARCHAR   | 0x774facd1685bca4a978f6097ed69c5ea0b158a65                         |                                                              |
| amount            | VARCHAR   | 1900000000                                                         |                                                              |
| feeAmount         | VARCHAR   | 950000                                                             |                                                              |
| part              | VARCHAR   | 1853987327                                                         |                                                              |

## 3. Table: KashiPairV1\_event\_LogRepay\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-15 16:50:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13810898                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa3d163c81c2dd2c09d5b7c67618e9ddaf669033ffec8eeccf47e4c8922fca6a5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 670                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xff7d29c7277d8a8850c473f0b71d7e5c4af45a50                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xf4220602257980674d5cf9bab9085e0342592dfa                         |                                                              |
| to                | VARCHAR   | 0xf4220602257980674d5cf9bab9085e0342592dfa                         |                                                              |
| amount            | VARCHAR   | 9898999999                                                         |                                                              |
| part              | VARCHAR   | 8811032082                                                         |                                                              |

## 4. Table: MasterChef\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 03:24:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17248378                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6e3b99f40d55927f4ccfab686e14ea41109611c8d1b85c2c760d7e6242487969 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 25                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2edad668740f1aa35e4d8f227fb8e17dca888cd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1f14be60172b40dac0ad9cd72f6f0f2c245992e8                         |                                                              |
| pid               | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 1404082028233                                                      |                                                              |

## 5. Table: MasterChef\_event\_EmergencyWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-10 08:55:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12211171                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3bf1565869739b1e51838e4a4b88436596a88b2a46c75e7e466599d38f7d16f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2edad668740f1aa35e4d8f227fb8e17dca888cd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x7db7f636eb50ab2734b587a4eb0ee3e8e75d5254                         |                                                              |
| pid               | VARCHAR   | 1                                                                  |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: MasterChef\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-27 09:38:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10741822                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x414204c5bd062c86812b9bf5bedadd96c370a743f095430a413c961105adc8ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2edad668740f1aa35e4d8f227fb8e17dca888cd                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xf942dba4159cb61f8ad88ca4a83f5204e8f4a6bd                         |                                                              |
| newOwner          | VARCHAR   | 0x9a8541ddf3a932a9a922b607e9cf7301f1d47bd1                         |                                                              |

## 7. Table: MasterChef\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 03:18:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17383239                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12441f898a287d09383272e9a0e133552b9f72f1d64dcc5bbbd1083a7dbc65e0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2edad668740f1aa35e4d8f227fb8e17dca888cd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1f14be60172b40dac0ad9cd72f6f0f2c245992e8                         |                                                              |
| pid               | VARCHAR   | 12                                                                 |                                                              |
| amount            | VARCHAR   | 657410213819416700                                                 |                                                              |

## 8. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-28 08:18:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14473593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x001d6b24b7681bae9b5b46a3fa661451be392cac24161bb4d31a0a8a95f5f4c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc0aee478e3658e2610c5f7a4a2e1777ce9e4f2ac                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x1ec0e884ee78a947e7fd0c3e35cc190d3216d48e                         |                                                              |
| token1            | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| pair              | VARCHAR   | 0x202af04e690b20a7a0da5cbeac334bdf01db2d51                         |                                                              |
| \_uint            | VARCHAR   | 2714                                                               |                                                              |

## 9. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 08:44:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15917031                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20c814d76326c6d212d3ae464d7e5285b436339c5b3ddd37fe5832077093d7ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 46                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0646583be34b133ce5d247f1d94e7effe32b58d0                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xdc774d5260ec66e5dd4627e1dd800eff3911345c                         |                                                              |
| spender           | VARCHAR   | 0x688c3e4658b5367da06fd629e41879beab538e37                         |                                                              |
| value             | VARCHAR   | 81831688253681646                                                  |                                                              |

## 10. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-06 23:35:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11005208                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35b44d32e92251485ba5286c1695ca462434e29396ad0e5e22327c26cc0aad5b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001b6450083e531a5a7bf310bd2c1af4247e23d4                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x6684977bbed67e101bb80fc07fccfba655c0a64f                         |                                                              |
| amount0           | VARCHAR   | 17942777663280792250                                               |                                                              |
| amount1           | VARCHAR   | 350040834535930278                                                 |                                                              |
| to                | VARCHAR   | 0x6684977bbed67e101bb80fc07fccfba655c0a64f                         |                                                              |

## 11. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-08 06:42:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14543629                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x96f2f8b96370e41c19f8bb2e4090f4b8a06389c92dcef3d6b62a33104d79e37e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 486                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x055475920a8c93cffb64d039a8205f7acc7722d3                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xd9e1ce17f2641f24ae83637ab66a2cca9c378b9f                         |                                                              |
| amount0           | VARCHAR   | 1950462575347                                                      |                                                              |
| amount1           | VARCHAR   | 58633966052184552567866                                            |                                                              |

## 12. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 11:26:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14596062                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x653f0d45fc23fbf6a33da3e8b2e69277167b013e4bfa035b72708adb70a2a895 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbdc120fef90fb185a49ad8fa62c7bc0ed0516cc7                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0000000000009cb77a0c864c0b1ca56062140580                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 17687449236402763966                                               |                                                              |
| amount0Out        | VARCHAR   | 28452448343566263                                                  |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x0000000000009cb77a0c864c0b1ca56062140580                         |                                                              |

## 13. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 01:14:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17659936                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x08212ae0dd3cfc06c538375da110f48dbe3c773bddc40133ea8c59c95383e3cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001b6450083e531a5a7bf310bd2c1af4247e23d4                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 84097664776677566753245                                            |                                                              |
| reserve1          | VARCHAR   | 70355477555327698006                                               |                                                              |

## 14. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-30 06:49:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12733849                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb76bf0ad27e393ae9fac439b53cbb8be604c0ea4dad2eba2c14cf481b1067d67 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 330                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001b6450083e531a5a7bf310bd2c1af4247e23d4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xe11fc0b43ab98eb91e9836129d1ee7c3bc95df50                         |                                                              |
| value             | VARCHAR   | 814271698488226434                                                 |                                                              |
