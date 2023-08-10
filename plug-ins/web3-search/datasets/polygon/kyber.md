# kyber

## 1. Table: AggregationRouter\_event\_Exchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-10 01:21:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26950229                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6d5cf907509810aec0066c2b1ef7680a71eda65a6ed21b7e8637bae38906d751 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1fc3607fa67b58deddb0faf7a116f417a20c551c                         | Address of the contract that produced the log                |
| pair              | VARCHAR   | 0x18008a3d4de136e090d0a71cb1de601fc8246225                         |                                                              |
| amountOut         | VARCHAR   | 2713481197453804624                                                |                                                              |
| output            | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |

## 2. Table: AggregationRouter\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-28 20:06:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 19621743                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc846928745f5ec2c68ffe7ccfc4d62e282fc87f76ace9d27a5949ceacafc6c92 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 294                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1fc3607fa67b58deddb0faf7a116f417a20c551c                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x7afac84bf3931b11548ed02b4460ad754cf54c66                         |                                                              |

## 3. Table: AggregationRouter\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-01 22:22:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20873546                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2cc59d5c38b144053673223aabd89f74b296f24d325ee0d3ee33af0792f5a2a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1fc3607fa67b58deddb0faf7a116f417a20c551c                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x70dadc7dcaaaeee9819addae6e3261f7ddc18f66                         |                                                              |
| srcToken          | VARCHAR   | 0x00e5646f60ac6fb446f621d146b6e1886f002905                         |                                                              |
| dstToken          | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                         |                                                              |
| dstReceiver       | VARCHAR   | 0x70dadc7dcaaaeee9819addae6e3261f7ddc18f66                         |                                                              |
| spentAmount       | VARCHAR   | 49864474772234941559                                               |                                                              |
| returnAmount      | VARCHAR   | 34957875994794580                                                  |                                                              |

## 4. Table: AggregationRouter\_v2\_event\_Error\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reason            | VARCHAR   |                                                              |             |

## 5. Table: AggregationRouter\_v2\_event\_Exchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-04 04:23:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31497350                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x50bd3416c42951aeff791ab9d445879a02ab1068cff9753ee519006e5a0f215b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf1a1b60f2d438842916c0adc43748768353ec25                         | Address of the contract that produced the log                |
| pair              | VARCHAR   | 0xd12bcdfb9a39be79da3bdf02557efdcd5ca59e77                         |                                                              |
| amountOut         | VARCHAR   | 1106586049562657089                                                |                                                              |
| output            | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |

## 6. Table: AggregationRouter\_v2\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-11 11:06:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23592013                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7343c92cec0fa591f6e03e53a9a10a869da3ad688335d20704d55130e8692c01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf1a1b60f2d438842916c0adc43748768353ec25                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x7afac84bf3931b11548ed02b4460ad754cf54c66                         |                                                              |

## 7. Table: AggregationRouter\_v2\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-04 22:44:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30344176                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x18758b3bba1447843539f6508102d8e391d04cf77ee6e1525135ab93a0ba8c19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 204                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdf1a1b60f2d438842916c0adc43748768353ec25                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0518aa86011ad513cdc0a4308183053143e8a0a0                         |                                                              |
| srcToken          | VARCHAR   | 0x1599fe55cda767b1f631ee7d414b41f5d6de393d                         |                                                              |
| dstToken          | VARCHAR   | 0xeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee                         |                                                              |
| dstReceiver       | VARCHAR   | 0x0518aa86011ad513cdc0a4308183053143e8a0a0                         |                                                              |
| spentAmount       | VARCHAR   | 124183594658432370370324                                           |                                                              |
| returnAmount      | VARCHAR   | 188555744856021804567                                              |                                                              |

## 8. Table: AggregationRouter\_v3\_event\_ClientData\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-10 13:59:03+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29397575                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x54f537007bd2f1d9599aa36098f701c18e3c2979551e77e9fa7a720f70f1eaa8                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00555513acf282b42882420e5e5ba87b44d8fa6e                                                           | Address of the contract that produced the log                |
| clientData        | VARCHAR   | 0x7b22536f75726365223a226b7962657273776170222c2244617461223a227b5c22736f757263655c223a5c226b79626572 |                                                              |

## 9. Table: AggregationRouter\_v3\_event\_Error\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reason            | VARCHAR   |                                                              |             |

## 10. Table: AggregationRouter\_v3\_event\_Exchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-20 21:43:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27376915                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x627f60db7b3a82615e988b1780194c9b52aec7afb9a504e019aa109f4d89765c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 366                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00555513acf282b42882420e5e5ba87b44d8fa6e                         | Address of the contract that produced the log                |
| pair              | VARCHAR   | 0xd12bcdfb9a39be79da3bdf02557efdcd5ca59e77                         |                                                              |
| amountOut         | VARCHAR   | 493340260184204958                                                 |                                                              |
| output            | VARCHAR   | 0x02474589f8e03110efc56ed3d69d60294d9ff063                         |                                                              |

## 11. Table: AggregationRouter\_v3\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-06 08:36:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26806784                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc3023b40d3ffef74bb652ba847a437a00938e2b1a4568b07abc9b64cb7b41eae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00555513acf282b42882420e5e5ba87b44d8fa6e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x7afac84bf3931b11548ed02b4460ad754cf54c66                         |                                                              |

## 12. Table: AggregationRouter\_v3\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-11 23:36:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30620869                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf0684eaf6a6ebf83e07e1b8c2704d8b049df4c379ee774a0cbc0ba49587977a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 118                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00555513acf282b42882420e5e5ba87b44d8fa6e                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x7af761df929afd00b21d0c493150b98f39c2831f                         |                                                              |
| srcToken          | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| dstToken          | VARCHAR   | 0x04f177fcacf6fb4d2f95d41d7d3fee8e565ca1d0                         |                                                              |
| dstReceiver       | VARCHAR   | 0x7af761df929afd00b21d0c493150b98f39c2831f                         |                                                              |
| spentAmount       | VARCHAR   | 100000                                                             |                                                              |
| returnAmount      | VARCHAR   | 1102380778252820233                                                |                                                              |

## 13. Table: DMMFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 19:18:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44255425                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb041398af9112a577489d87e2eecddd0f6c0b490aab85c2ff2b44b323c6c357 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 171                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f1fe642060b5b9658c15721ea22e982643c095c                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         |                                                              |
| token1            | VARCHAR   | 0x36e34780f8d9efe008db0f333ce41c5b59b2de23                         |                                                              |
| pool              | VARCHAR   | 0x2fd8e390e20628bab966dc7aeccb74bb474df75f                         |                                                              |
| ampBps            | VARCHAR   | 1000000000                                                         |                                                              |
| totalPool         | VARCHAR   | 733                                                                |                                                              |

## 14. Table: DMMFactory\_event\_SetFeeConfiguration\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-28 16:24:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16254643                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x75c0a587a96bb4beb384bada23ebf39610cfea9925ed1d54898b79b2846c1c27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 592                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f1fe642060b5b9658c15721ea22e982643c095c                         | Address of the contract that produced the log                |
| feeTo             | VARCHAR   | 0x91c9d4373b077ef8082f468c7c97f2c499e36f5b                         |                                                              |
| governmentFeeBps  | VARCHAR   | 1000                                                               |                                                              |

## 15. Table: DMMFactory\_event\_SetFeeToSetter\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-28 16:26:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16254684                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65c8f98e413b17d9ec88f96d793e98302f0393d796ea63ecda69b09a98a28245 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 347                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f1fe642060b5b9658c15721ea22e982643c095c                         | Address of the contract that produced the log                |
| feeToSetter       | VARCHAR   | 0x91c9d4373b077ef8082f468c7c97f2c499e36f5b                         |                                                              |

## 16. Table: DMMPool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-11 07:49:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30595021                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e1ae21bd9801b67ca2873ad95a61d1d0498c0ef1543683482391788e78830c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x228f77326875c4f0049f3c17510fad59a572673e                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x546c79662e028b661dfb4767664d0273184e4dd1                         |                                                              |
| amount0           | VARCHAR   | 92404347401995112481                                               |                                                              |
| amount1           | VARCHAR   | 70234692337222492837909                                            |                                                              |
| to                | VARCHAR   | 0xbe2f0354d970265bfc36d383af77f72736b81b54                         |                                                              |

## 17. Table: DMMPool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 16:43:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45905775                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab386001b85d79b9635bc3a2d37afcfa54c27bc7e95bdc27b305cde6fe104ca2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x30d50b36be1fe4bd1d78553f77937caabad37f7f                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x546c79662e028b661dfb4767664d0273184e4dd1                         |                                                              |
| amount0           | VARCHAR   | 2511227938800365                                                   |                                                              |
| amount1           | VARCHAR   | 9058352279413343992                                                |                                                              |

## 18. Table: DMMPool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-08 23:01:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41306968                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x049c57e885985881c0049c6ed206d7d10b8d979a5168b990d6acaeae80fb5d64 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 228                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2b68bd68f551ce4fdbc81d0ed841b7d0b1fdc621                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x10d443594cbe2ecc2574df8710ffc6a9a2f46c74                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 11176542                                                           |                                                              |
| amount0Out        | VARCHAR   | 10131283251321271268                                               |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x01fd0d981dcf288dd9afe4d1f75c82a76ca2128f                         |                                                              |
| feeInPrecision    | VARCHAR   | 832839479819977                                                    |                                                              |

## 19. Table: DMMPool\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 08:16:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33211589                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ecb4d0fa730452f7163c77a36d4973d6262f6bf2cadd886d452aeb744b7490c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x84b96129607e65debd696d374b302b7864a92d92                         | Address of the contract that produced the log                |
| vReserve0         | VARCHAR   | 0                                                                  |                                                              |
| vReserve1         | VARCHAR   | 0                                                                  |                                                              |
| reserve0          | VARCHAR   | 3905084666715608960794                                             |                                                              |
| reserve1          | VARCHAR   | 1365958                                                            |                                                              |

## 20. Table: DMMPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 12:37:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45227173                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb0fd98cb0e25d44c49fe657ede19a0bae1f3586bd836d106ad69a754d8901722 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 162                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xab08b0c9dadc343d3795dae5973925c3b6e39977                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x161eb8e75f182de2db245195081f8a5684c42e40                         |                                                              |
| to                | VARCHAR   | 0xec209bcdef8798772ac1456ea9d93c940187363c                         |                                                              |
| value             | VARCHAR   | 949350233202271634                                                 |                                                              |

## 21. Table: DMMPool\_event\_UpdateEMA\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 03:43:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45014609                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9676878075838102ed01508082b5f8e56555cb7e039433c301d4c68d6ec7ac8d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 751                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x228f77326875c4f0049f3c17510fad59a572673e                         | Address of the contract that produced the log                |
| shortEMA          | VARCHAR   | 39729                                                              |                                                              |
| longEMA           | VARCHAR   | 10226789540                                                        |                                                              |
| lastBlockVolume   | VARCHAR   | 24313695585595240248                                               |                                                              |
| skipBlock         | VARCHAR   | 70619                                                              |                                                              |

## 22. Table: ElasticFactory\_event\_ConfigMasterUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-24 07:46:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35999663                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9e6426aa85e95ce965af52cc06d1a81a9a198483ff5117e3cafe36527e9e7e00 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f1dddbf348ac2fbe22a163e30f99f9ece3dd50a                         | Address of the contract that produced the log                |
| oldConfigMaster   | VARCHAR   | 0xbe2f0354d970265bfc36d383af77f72736b81b54                         |                                                              |
| newConfigMaster   | VARCHAR   | 0x91c9d4373b077ef8082f468c7c97f2c499e36f5b                         |                                                              |

## 23. Table: ElasticFactory\_event\_FeeConfigurationUpdated\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2022-06-13 13:11:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 29518254                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xdaf8c013f34555065245745e6cabf53f20274914518dd39b06dd8a5aea2f3516 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 205                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x5f1dddbf348ac2fbe22a163e30f99f9ece3dd50a                         | Address of the contract that produced the log                |
| feeTo              | VARCHAR   | 0x91c9d4373b077ef8082f468c7c97f2c499e36f5b                         |                                                              |
| governmentFeeUnits | VARCHAR   | 10000                                                              |                                                              |

## 24. Table: ElasticFactory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-17 20:13:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38204576                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf2e384cf9fcff1d67c03e720c995f8ee7d51a4cacd7eb91eff0cf98165560c1d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 142                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f1dddbf348ac2fbe22a163e30f99f9ece3dd50a                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x1bfd67037b42cf73acf2047067bd4f2c47d9bfd6                         |                                                              |
| token1            | VARCHAR   | 0x2791bca1f2de4661ed88a30c99a7a9449aa84174                         |                                                              |
| swapFeeUnits      | VARCHAR   | 40                                                                 |                                                              |
| tickDistance      | VARCHAR   | 8                                                                  |                                                              |
| pool              | VARCHAR   | 0x62ddc806129ec8ea794776aab89f00e8d9b1d44c                         |                                                              |

## 25. Table: ElasticFactory\_event\_SwapFeeEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 07:32:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29347468                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4bcf25d7d6f7d09976f2b64468355fced8a3d91c3b3dc5126ae5c98eb98ba6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 110                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5f1dddbf348ac2fbe22a163e30f99f9ece3dd50a                         | Address of the contract that produced the log                |
| swapFeeUnits      | VARCHAR   | 40                                                                 |                                                              |
| tickDistance      | VARCHAR   | 8                                                                  |                                                              |

## 26. Table: ElasticPool\_event\_BurnRTokens\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-01 08:31:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35060376                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d1fc5c8470fbaf781c2974df243ac3e5ddd483694271f7c41e43dcfd6fdcffe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 520                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0387dbd5e8504938edf4b38eacbf77a1d0394a1b                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x2b1c7b41f6a8f2b2bc45c3233a5d5fb3cd6dc9a8                         |                                                              |
| qty               | VARCHAR   | 82859456622                                                        |                                                              |
| qty0              | VARCHAR   | 3311606                                                            |                                                              |
| qty1              | VARCHAR   | 2085280944116633                                                   |                                                              |

## 27. Table: ElasticPool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-31 18:46:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35037206                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e1f9916b9232c1fd614181b912e2e028b2d37375af2bb49c483ef7621024eae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 192                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0387dbd5e8504938edf4b38eacbf77a1d0394a1b                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x2b1c7b41f6a8f2b2bc45c3233a5d5fb3cd6dc9a8                         |                                                              |
| tickLower         | VARCHAR   | 201576                                                             |                                                              |
| tickUpper         | VARCHAR   | 203928                                                             |                                                              |
| qty               | VARCHAR   | 8919539865818757                                                   |                                                              |
| qty0              | VARCHAR   | 20868020039                                                        |                                                              |
| qty1              | VARCHAR   | 12416571217023496251                                               |                                                              |

## 28. Table: ElasticPool\_event\_Flash\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 03:20:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43312556                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x65a6dbacf58dc5a1a8c9cac0df285558949e1e2a821e69f579f42e0d222f7a19 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 474                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf9cc934753a127100585812181ac04d07158a4c2                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xe2617b97b31f5d3b56833094e70890b1ee2e7b38                         |                                                              |
| recipient         | VARCHAR   | 0xe2617b97b31f5d3b56833094e70890b1ee2e7b38                         |                                                              |
| qty0              | VARCHAR   | 670896128                                                          |                                                              |
| qty1              | VARCHAR   | 0                                                                  |                                                              |
| paid0             | VARCHAR   | 53671                                                              |                                                              |
| paid1             | VARCHAR   | 0                                                                  |                                                              |

## 29. Table: ElasticPool\_event\_Initialize\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-03 18:28:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39926364                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0e193df0b673d3d643ac716771e56f00cf40b6edf646ed3857dffe4b341325b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 370                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x99e7dead4c99347580fbd7daf395a282356d1d06                         | Address of the contract that produced the log                |
| sqrtP             | VARCHAR   | 202731719087432747500288812871158410                               |                                                              |
| tick              | VARCHAR   | 295116                                                             |                                                              |

## 30. Table: ElasticPool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-11 14:34:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39175849                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6f372ad719458e3e98428e2dbd6b84d86b2b9a72c9c3574c2cd4345ea733efe0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 314                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0387dbd5e8504938edf4b38eacbf77a1d0394a1b                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x2b1c7b41f6a8f2b2bc45c3233a5d5fb3cd6dc9a8                         |                                                              |
| owner             | VARCHAR   | 0x2b1c7b41f6a8f2b2bc45c3233a5d5fb3cd6dc9a8                         |                                                              |
| tickLower         | VARCHAR   | 201144                                                             |                                                              |
| tickUpper         | VARCHAR   | 203608                                                             |                                                              |
| qty               | VARCHAR   | 543257555841943                                                    |                                                              |
| qty0              | VARCHAR   | 580000000                                                          |                                                              |
| qty1              | VARCHAR   | 1268103907732840978                                                |                                                              |

## 31. Table: ElasticPool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-29 01:29:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30118608                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaadf92751456bce1ea802ee96c025f212d660b309ec1b51a6f19f799e33dcf50 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf9cc934753a127100585812181ac04d07158a4c2                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x41684b361557e9282e0373ca51260d9331e518c9                         |                                                              |
| recipient         | VARCHAR   | 0x41684b361557e9282e0373ca51260d9331e518c9                         |                                                              |
| deltaQty0         | VARCHAR   | -19760195                                                          |                                                              |
| deltaQty1         | VARCHAR   | 19784295                                                           |                                                              |
| sqrtP             | VARCHAR   | 79273369830011326931439335486                                      |                                                              |
| liquidity         | VARCHAR   | 9913344910499                                                      |                                                              |
| currentTick       | VARCHAR   | 11                                                                 |                                                              |

## 32. Table: ElasticPool\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-10 06:09:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36647935                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f90699940e7f78834f8530dd8f93fc5c721fc2a5705ce3507bb529635eae1bc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x944dde4c9d98c856960ce3e75c3989c982efb8b7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x944dde4c9d98c856960ce3e75c3989c982efb8b7                         |                                                              |
| value             | VARCHAR   | 100000                                                             |                                                              |

## 33. Table: MetaAggregationRouter\_event\_ClientData\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 16:16:19+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34174616                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc94232cd5673ba97f060dbcd3cc25b1e6884844923b66f18bbcb6fc46950a189                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x617dee16b86534a5d792a4d7a62fb491b544111e                                                           | Address of the contract that produced the log                |
| clientData        | VARCHAR   | 0x7b22536f75726365223a226b7962657273776170222c2244617461223a227b5c22736f757263655c223a5c226b79626572 |                                                              |

## 34. Table: MetaAggregationRouter\_event\_Error\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| reason            | VARCHAR   |                                                              |             |

## 35. Table: MetaAggregationRouter\_event\_Exchange\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-24 11:07:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36005387                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5fd1731b6856461efae74db219f63747fbe86f0ffa288c22ee03b5464db8ea43 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 123                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x617dee16b86534a5d792a4d7a62fb491b544111e                         | Address of the contract that produced the log                |
| pair              | VARCHAR   | 0x7f92d949185cd8ceebebad89876ab3e90d1ce3b5                         |                                                              |
| amountOut         | VARCHAR   | 6413771096102136313917                                             |                                                              |
| output            | VARCHAR   | 0x01d35cbc2070a3b76693ce2b6364eae24eb88591                         |                                                              |

## 36. Table: MetaAggregationRouter\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-28 10:19:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31232434                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1a631dcc9ffa8710998383df1fe971cb5313555d0ad6198b21f5e0041d8d3835 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x617dee16b86534a5d792a4d7a62fb491b544111e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x7afac84bf3931b11548ed02b4460ad754cf54c66                         |                                                              |
| newOwner          | VARCHAR   | 0xbe2f0354d970265bfc36d383af77f72736b81b54                         |                                                              |

## 37. Table: MetaAggregationRouter\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-04 11:00:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31508122                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcda6fd0a4d1bac9b95ce523bb4820cfe37b742b017a23f0690a2edbf8bcd173d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 140                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x617dee16b86534a5d792a4d7a62fb491b544111e                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x684bada8b201de782a4335a3d1432ce5d140c181                         |                                                              |
| srcToken          | VARCHAR   | 0xafc780bb79e308990c7387ab8338160ba8071b67                         |                                                              |
| dstToken          | VARCHAR   | 0x0f110c55efe62c16d553a3d3464b77e1853d0e97                         |                                                              |
| dstReceiver       | VARCHAR   | 0x684bada8b201de782a4335a3d1432ce5d140c181                         |                                                              |
| spentAmount       | VARCHAR   | 133578697073617456                                                 |                                                              |
| returnAmount      | VARCHAR   | 12494590515543003165                                               |                                                              |
