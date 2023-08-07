# pancakeswap

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-19 10:25:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20575328                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd82f25bb44e46c4ff4268d4da6c3923753720bfb31599babcd4c8378679e72f6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xca143ce32fe78f1f7019d7d551a6402fc5350c73                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x2170ed0880ac9a755fd29b2688956bd959f933f8                         |                                                              |
| token1            | VARCHAR   | 0xc76088d382da0dd729be2da579d0276e82a2d745                         |                                                              |
| pair              | VARCHAR   | 0xad10bb78e36874a6139097eea1aaaa3ed8dbbfa0                         |                                                              |
| \_uint            | VARCHAR   | 1084208                                                            |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-28 03:01:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30346319                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb5ccda9001abe625dfda29d11388b8c74733ff6dd5701755651725ac7474a7c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 362                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x58f876857a02d6762e0101bb5c46a8c1ed44dc16                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc3b512ea0745b3d85185834248b2efbcff5da371                         |                                                              |
| spender           | VARCHAR   | 0x0000000000000000000000000000000000000001                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-08 07:29:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21992194                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x001aa249c5dd1d81c550dfd6c2c521cafda2d93a62f888a304749ffbdff782ec | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0cc47ed7c830a89b62987cd15cf4f0db7ea61198                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x10ed43c718714eb63d5aa57b78b54704e256024e                         |                                                              |
| amount0           | VARCHAR   | 999999999999999990                                                 |                                                              |
| amount1           | VARCHAR   | 9999999999999999900000                                             |                                                              |
| to                | VARCHAR   | 0x542552d26015cc44683a3a51e9f2d2e29ebd16a7                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-08 11:38:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21997121                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa52f523fd2047f6e241b340d8dd28f441695cd0a1f2e54a6c2972cdd04285ee1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x02d75d7beebf6d5228a3fa5f810cedf2bea5ab1e                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x10ed43c718714eb63d5aa57b78b54704e256024e                         |                                                              |
| amount0           | VARCHAR   | 106762032898425675825762                                           |                                                              |
| amount1           | VARCHAR   | 36539537235268890265                                               |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-12 15:18:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29040109                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80b7d9cf2665c9cee6c2b3c024bb4320830ce15f0be0284cb3739c2fcf376c45 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000566b56abf0a138df881559be7db9043e3e09c                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x13f4ea83d0bd40e75c8222255bc855a974568dd4                         |                                                              |
| amount0In         | VARCHAR   | 2598536496130420647773                                             |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 10451736000499029                                                  |                                                              |
| to                | VARCHAR   | 0x13f4ea83d0bd40e75c8222255bc855a974568dd4                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-09 00:11:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20275456                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeed75442282d47a5ed39d468566602b949dddab4f9d6928cbc0c7f38443443ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 29                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf45cd219aef8618a92baa7ad848364a158a24f33                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 922203448313959761449                                              |                                                              |
| reserve1          | VARCHAR   | 21955641941711961985071698                                         |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-27 23:24:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20821005                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1eba3b873d36f71b82d4ebd1258dbd316257e4434ebc0243bd101b99ef676295 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000d27d4dfb3e336a6462a3435c3dd3953391bb7                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xafcee27282dfc68eb4b7aecbfdffa1fa8a04dbf7                         |                                                              |
| to                | VARCHAR   | 0xf69bf89cb458f8fe4a6ecabe8bc71f34866b9fb1                         |                                                              |
| value             | VARCHAR   | 1567149000000000000000                                             |                                                              |

## 8. Table: UniswapV3Factory\_event\_FeeAmountEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-01 00:04:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26956207                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x57b6445ade8e733f10303f1b9b89b275cda5a136ef14075f6fd0517e8f3b6c85 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 296                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0bfbcf9fa4f9c56b0f40a671ad40e0805a091865                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 500                                                                |                                                              |
| tickSpacing       | VARCHAR   | 10                                                                 |                                                              |

## 9. Table: UniswapV3Factory\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-01 00:04:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26956207                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x57b6445ade8e733f10303f1b9b89b275cda5a136ef14075f6fd0517e8f3b6c85 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 293                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0bfbcf9fa4f9c56b0f40a671ad40e0805a091865                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x40492810a7de793eef0dfb3a58338fdfea511047                         |                                                              |

## 10. Table: UniswapV3Factory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-10 14:15:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27228406                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70dded1c156a7a721058fc15622f627a145cb35322bf36b05635c5dc7b922aae | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 196                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0bfbcf9fa4f9c56b0f40a671ad40e0805a091865                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         |                                                              |
| token1            | VARCHAR   | 0xc1bc08472a208db09bce7b6257ba8f687586ff77                         |                                                              |
| fee               | VARCHAR   | 100                                                                |                                                              |
| tickSpacing       | VARCHAR   | 1                                                                  |                                                              |
| pool              | VARCHAR   | 0xc48216d5198385d32780fcd98670fbcd3602b9c3                         |                                                              |

## 11. Table: UniswapV3Pool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-25 17:30:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27662756                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa1485e71844312608b2273bb5ba9a3eb8a4cf8817adace3ed254873daa0736c4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x202c1d15bfbd558c7aaa07ed05df58aec62eb2f3                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x46a15b0b27311cedf172ab29e4f4766fbe7f4364                         |                                                              |
| tickLower         | VARCHAR   | 0                                                                  |                                                              |
| tickUpper         | VARCHAR   | 75800                                                              |                                                              |
| amount            | VARCHAR   | 4618392578346592929402                                             |                                                              |
| amount0           | VARCHAR   | 622519891848472386                                                 |                                                              |
| amount1           | VARCHAR   | 198524714470231487421212                                           |                                                              |

## 12. Table: UniswapV3Pool\_event\_CollectProtocol\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-03 04:11:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30519983                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14f79657a3f231d03497597d86090e43fdfb6f3cb6a5ed233c3546a149da16c2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe5607dc39beef2154aec0d4a78a399fe8b76fbe0                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x518d9643160cfd6fe469bfbd3ba66fc8035a68a3                         |                                                              |
| recipient         | VARCHAR   | 0x518d9643160cfd6fe469bfbd3ba66fc8035a68a3                         |                                                              |
| amount0           | VARCHAR   | 45162350096156052861                                               |                                                              |
| amount1           | VARCHAR   | 472297604358625940660                                              |                                                              |

## 13. Table: UniswapV3Pool\_event\_Collect\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 21:08:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28184736                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e03928c47174d56719960d01f2211042bf24f1f8d065f3472f954c3569c1d20 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xce6cab75608aa20ce748da7b340ce9294617ce00                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x46a15b0b27311cedf172ab29e4f4766fbe7f4364                         |                                                              |
| recipient         | VARCHAR   | 0xc0f350e83d88340c26ab544bb04dcd51b1ea80ac                         |                                                              |
| tickLower         | VARCHAR   | -14000                                                             |                                                              |
| tickUpper         | VARCHAR   | 0                                                                  |                                                              |
| amount0           | VARCHAR   | 417429246111170052916                                              |                                                              |
| amount1           | VARCHAR   | 289210084308477310547                                              |                                                              |

## 14. Table: UniswapV3Pool\_event\_Flash\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-03 08:27:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28773307                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7fa618d45c8d5443ed890684904cb57239480b260ff9b9565b969005dc0ad293 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 421                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x36696169c63e42cd08ce11f5deebbcebae652050                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x3bba049f9e5c7a88dd4c8ab8d75d97bebf21da77                         |                                                              |
| recipient         | VARCHAR   | 0x3bba049f9e5c7a88dd4c8ab8d75d97bebf21da77                         |                                                              |
| amount0           | VARCHAR   | 0                                                                  |                                                              |
| amount1           | VARCHAR   | 9625162258989855                                                   |                                                              |
| paid0             | VARCHAR   | 0                                                                  |                                                              |
| paid1             | VARCHAR   | 4812581129495                                                      |                                                              |

## 15. Table: UniswapV3Pool\_event\_IncreaseObservationCardinalityNext\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2023-08-02 03:25:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 30490339                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0xb624e71a188a246ea76ddd66c470d136191d038d0de83cbf1466acba09464171 | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 453                                                                | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x9474e972f49605315763c296b122cbb998b615cf                         | Address of the contract that produced the log                |
| observationCardinalityNextOld | VARCHAR   | 1                                                                  |                                                              |
| observationCardinalityNextNew | VARCHAR   | 7                                                                  |                                                              |

## 16. Table: UniswapV3Pool\_event\_Initialize\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-03 22:03:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27898270                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe219f6a293b4760cfca7ebb1e33d031dd16f00e800916f788dbaa9e5a299a459 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2de793afc5afb2c0ba0f2cac959462879ae4d64a                         | Address of the contract that produced the log                |
| sqrtPriceX96      | VARCHAR   | 79224358494714345780                                               |                                                              |
| tick              | VARCHAR   | -414487                                                            |                                                              |

## 17. Table: UniswapV3Pool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-29 19:48:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29533671                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x565b18e189beee2581a8e77b772843e4e846b6d2c5f9e64c533aab9631e399d5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8f982159a5ad19f8e8a82e6b9eafbf44bbb569d9                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x46a15b0b27311cedf172ab29e4f4766fbe7f4364                         |                                                              |
| owner             | VARCHAR   | 0x46a15b0b27311cedf172ab29e4f4766fbe7f4364                         |                                                              |
| tickLower         | VARCHAR   | -67050                                                             |                                                              |
| tickUpper         | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 725444853848561103                                                 |                                                              |
| amount0           | VARCHAR   | 20000000000000000000                                               |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |

## 18. Table: UniswapV3Pool\_event\_SetFeeProtocol\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| feeProtocol0Old   | VARCHAR   |                                                              |             |
| feeProtocol1Old   | VARCHAR   |                                                              |             |
| feeProtocol0New   | VARCHAR   |                                                              |             |
| feeProtocol1New   | VARCHAR   |                                                              |             |

## 19. Table: UniswapV3Pool\_event\_Swap\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-07-21 16:19:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 30161221                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x1f5a2e748ba5941ca197853b27131f47a843dc46e3a050f463db3ec20414e286 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x849f86ed464169397d55ac881a4b6e4240cc52e8                         | Address of the contract that produced the log                |
| sender             | VARCHAR   | 0x13f4ea83d0bd40e75c8222255bc855a974568dd4                         |                                                              |
| recipient          | VARCHAR   | 0x13f4ea83d0bd40e75c8222255bc855a974568dd4                         |                                                              |
| amount0            | VARCHAR   | 910787167721294575                                                 |                                                              |
| amount1            | VARCHAR   | -785360986759820393                                                |                                                              |
| sqrtPriceX96       | VARCHAR   | 4295128740                                                         |                                                              |
| liquidity          | VARCHAR   | 0                                                                  |                                                              |
| tick               | VARCHAR   | -887272                                                            |                                                              |
| protocolFeesToken0 | VARCHAR   | 2914518936708142                                                   |                                                              |
| protocolFeesToken1 | VARCHAR   | 0                                                                  |                                                              |
