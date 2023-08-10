# yam

## 1. Table: YAMAMPLPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:08:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636675                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3fb803c97abead93e176d3f9cdbf1d9c42a71fe03876b33fe0733b07dd6d6504 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ebb67687fee2d265d7b824714df13622d90e663                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |

## 2. Table: YAMAMPLPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74796dd72003bff61b3087d73e32a930b56179faee39db58c7bcf8c31af627ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 188                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ebb67687fee2d265d7b824714df13622d90e663                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 3. Table: YAMAMPLPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-15 19:28:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10666508                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x847882590ce60220abb441234665304470c3101ccd89601ff90f4c5db7902534 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 165                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ebb67687fee2d265d7b824714df13622d90e663                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0079ce80043edc3325598e4a3b6293ab779bf174                         |                                                              |
| reward            | VARCHAR   | 1052838005440910727383                                             |                                                              |

## 4. Table: YAMAMPLPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-20 03:46:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10694705                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd53aebabbbee9e49d5aa437f798fee926820cfb5d920b48d6089936769b1050b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 291                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ebb67687fee2d265d7b824714df13622d90e663                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x05d17cd6b4783cfa2ee1484677d076c68fffe2f4                         |                                                              |
| amount            | VARCHAR   | 31350000000000000                                                  |                                                              |

## 5. Table: YAMAMPLPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 04:22:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10688370                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb777e0b7cdb6173f3319274402970167cff163a5ea3126953c513fda8813210 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9ebb67687fee2d265d7b824714df13622d90e663                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x41e0579e8d04862a4f0b27cdfe33ca43787e0ea1                         |                                                              |
| amount            | VARCHAR   | 219262900000000                                                    |                                                              |

## 6. Table: YAMCOMPPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:23:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636740                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20c49ccc80653f01533d3ae34d1c8d1b82a7c4b327c512a2d344435f289484f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 271                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8538e5910c6f80419cd3170c26073ff238048c9e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |
| newOwner          | VARCHAR   | 0xae99ff8fe2236af5083ea979ecf1dbaa0efd07e3                         |                                                              |

## 7. Table: YAMCOMPPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0bc578bd100984e1d2ea7793d403e4c2c1c0700c114dede4ed23d9a516c49a37 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8538e5910c6f80419cd3170c26073ff238048c9e                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 8. Table: YAMCOMPPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-29 14:49:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10958013                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83aa96a73a9775ad4c75909b6fe1b5c475903e8e86bf7255c42a353df18f2bd2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8538e5910c6f80419cd3170c26073ff238048c9e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x495d5208da464e1efc646a4e9344721a510d8654                         |                                                              |
| reward            | VARCHAR   | 230126477477158919116                                              |                                                              |

## 9. Table: YAMCOMPPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-17 03:07:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10675075                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2133a358051ab3bc78b30d45110e0e78a318fc3458976b029d89d31db53093f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 222                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8538e5910c6f80419cd3170c26073ff238048c9e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x083227628a8ce4b78ac244ffd140392393024242                         |                                                              |
| amount            | VARCHAR   | 9000000000000000000                                                |                                                              |

## 10. Table: YAMCOMPPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-22 15:15:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10710800                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe8224900841369aea604a7ee1aec04178178421be80614fac9d4287f11d9bd5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8538e5910c6f80419cd3170c26073ff238048c9e                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xa189d42f68da0069d14abfbf48faa0f21eca86fb                         |                                                              |
| amount            | VARCHAR   | 5604907090000000000                                                |                                                              |

## 11. Table: YAMDelegate\_v3\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-19 20:09:19+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12666852                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x975047f3696966c7a0e4725e46ca7b3712a913d59eb183c180bb0ae79fb4fb43             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x229fed4f4192ba3aba690e37088bb4a68881df3d                                     |                                                              |
| spender           | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                                     |                                                              |
| amount            | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 12. Table: YAMDelegate\_v3\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-15 06:15:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13618697                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4f1e28650832ddc6c864cbdc2e0c6875f71c4aaf0fed29406abb957b27621c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0x1f0aef221b865213af9214cd6b4debfbc4ec4c1d                         |                                                              |
| fromDelegate      | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| toDelegate        | VARCHAR   | 0x1f0aef221b865213af9214cd6b4debfbc4ec4c1d                         |                                                              |

## 13. Table: YAMDelegate\_v3\_event\_DelegateVotesChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-20 15:36:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12672020                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9105520870b675be542709534e0432caaf71cb594bd7548dd91b6462d5d9e11b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 340                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| delegate          | VARCHAR   | 0x0f82e57804d0b1f6fab2370a43dcfad3c7cb239c                         |                                                              |
| previousBalance   | VARCHAR   | 433782827509039574651234557246                                     |                                                              |
| newBalance        | VARCHAR   | 434145177533254300044594333425                                     |                                                              |

## 14. Table: YAMDelegate\_v3\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-06 09:49:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12580219                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x357a5152db1e3cf0cfbf6ab6e881044ea0a2cfb3151ca545193e0fb76643489d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 126                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x590084ff305a6ffd021153a19ab6065ca019e424                         |                                                              |
| amount            | VARCHAR   | 10034892797757222688                                               |                                                              |

## 15. Table: YAMDelegate\_v3\_event\_NewGov\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-18 15:54:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10887078                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8cfa612e987a3f7fe045a6014ffa0e9f0c9c349592857e01e33ae9e270d52ef1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| oldGov            | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |
| newGov            | VARCHAR   | 0x8b4f1616751117c38a0f84f9a146cca191ea3ec5                         |                                                              |

## 16. Table: YAMDelegate\_v3\_event\_NewIncentivizer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-12 16:40:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11243912                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc9992d7fecf9b17c31d94d391b28972151b52baa8aae802b5d680ecf61c61ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 277                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| oldIncentivizer   | VARCHAR   | 0x5b0501f7041120d36bc8c6dc3faea0b74b32a0ed                         |                                                              |
| newIncentivizer   | VARCHAR   | 0xd67c05523d8ec1c60760fd017ef006b9f6e496d0                         |                                                              |

## 17. Table: YAMDelegate\_v3\_event\_NewMigrator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-18 15:49:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10887049                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78a5c9045ed440b567f9a24644f9650599db5a0c8ceba69a900b986dcbb5ffe1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| oldMigrator       | VARCHAR   | 0x72cfed9293cbfb2bfc7515c413048c697c6c811c                         |                                                              |
| newMigrator       | VARCHAR   | 0x72cfed9293cbfb2bfc7515c413048c697c6c811c                         |                                                              |

## 18. Table: YAMDelegate\_v3\_event\_NewPendingGov\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-18 15:54:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10887076                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78776ce50d17814d79845641e3f503449da6634d36c69db4ed49b921216afbb0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| oldPendingGov     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingGov     | VARCHAR   | 0x8b4f1616751117c38a0f84f9a146cca191ea3ec5                         |                                                              |

## 19. Table: YAMDelegate\_v3\_event\_NewRebaser\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-12 16:40:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11243912                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc9992d7fecf9b17c31d94d391b28972151b52baa8aae802b5d680ecf61c61ed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| oldRebaser        | VARCHAR   | 0x1fb361f274f316d383b94d761832ab68099a7b00                         |                                                              |
| newRebaser        | VARCHAR   | 0xd93f403b432d39aa0f736c2021be6051d85a1d55                         |                                                              |

## 20. Table: YAMDelegate\_v3\_event\_Rebase\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2020-12-14 20:25:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 11453268                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x969cb7dd4a9b5707d6c7baaf09f0489b2cb857986ea0fbcc1cac123892665abf | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 231                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| epoch                 | VARCHAR   | 36                                                                 |                                                              |
| prevYamsScalingFactor | VARCHAR   | 2446809116929982866                                                |                                                              |
| newYamsScalingFactor  | VARCHAR   | 2453489380481270300                                                |                                                              |

## 21. Table: YAMDelegate\_v3\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-28 13:45:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11946179                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed94378614c667e7ba2f74bafae556f9887b21aa090888610903bb5c482a752e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0aacfbec6a24756c20d41914f2caba817c0d8521                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xbb66cfa846703e6a724eb3736ae16b6e22613234                         |                                                              |
| amount            | VARCHAR   | 22636734046394077238                                               |                                                              |

## 22. Table: YAMDelegator\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-05 07:50:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12766243                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x73722667610be39b55ba2a1e47c08e17ba49d9838577076d4b301bb0360ea7c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 312                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x72f1bf04f6f471ae395013d6f06b1a2434e88bc4                         |                                                              |
| spender           | VARCHAR   | 0xf1d7c9e4c57a5c1902f4a4ae2630d2da78ffb1c1                         |                                                              |
| amount            | VARCHAR   | 0                                                                  |                                                              |

## 23. Table: YAMDelegator\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 01:07:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10687483                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0479ed08c06d1e14cccc2a80394228417b72ca2045b3315a3503f25106ecdceb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0xf887a691dc0fd9d81891dcc79aa329ccc26f0ab6                         |                                                              |
| fromDelegate      | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |
| toDelegate        | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |

## 24. Table: YAMDelegator\_event\_DelegateVotesChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-10 19:48:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11029688                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbf88edefb1767becf8865d0d62b0aa2075ed7afa64ca1e76c8345a8a5f84a756 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 124                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| delegate          | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |
| previousBalance   | VARCHAR   | 41243853726278918328793306916                                      |                                                              |
| newBalance        | VARCHAR   | 41565694947630063782210566865                                      |                                                              |

## 25. Table: YAMDelegator\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-20 05:49:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11091237                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x531b073f2482877921d86972eaa3321fb494470a86a293400074abf3cc741d56 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 136                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0xaddbcd6a68bfeb6e312e82b30ce1eb4a54497f4c                         |                                                              |
| amount            | VARCHAR   | 34328307658052599675781                                            |                                                              |

## 26. Table: YAMDelegator\_event\_NewGov\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:23:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636743                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11f450227fb43b17c6b9f10ef6b4a7d97b0312ee765ca1eee932b0ecf9194ea7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| oldGov            | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |
| newGov            | VARCHAR   | 0xae99ff8fe2236af5083ea979ecf1dbaa0efd07e3                         |                                                              |

## 27. Table: YAMDelegator\_event\_NewImplementation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 04:47:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636560                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1b96008716c88a7bda17a1ba479af2725dc5ae81a590835402d081a74132e35c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 53                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| oldImplementation | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newImplementation | VARCHAR   | 0xa923af6d05993495257a872ec69dbbf01501eb0e                         |                                                              |

## 28. Table: YAMDelegator\_event\_NewIncentivizer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636722                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x068074afce9fcb80b62a841fe4093402ec36dd353e085e76e263ca18646cc33c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 8                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| oldIncentivizer   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newIncentivizer   | VARCHAR   | 0xaddbcd6a68bfeb6e312e82b30ce1eb4a54497f4c                         |                                                              |

## 29. Table: YAMDelegator\_event\_NewPendingGov\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:23:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636741                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xefa8d57a28904183ab5e631be25f7f7376c0c21744868a5c6999349b35eb32b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 88                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| oldPendingGov     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newPendingGov     | VARCHAR   | 0xae99ff8fe2236af5083ea979ecf1dbaa0efd07e3                         |                                                              |

## 30. Table: YAMDelegator\_event\_NewRebaser\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 04:50:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636576                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x81dc17688e3479b1f96e5cdfb5766dcba7609aa2bba1fea877f5bcf43500c163 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| oldRebaser        | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newRebaser        | VARCHAR   | 0x649714bc2fffcb1e65c689b49a10216d4960833d                         |                                                              |

## 31. Table: YAMDelegator\_event\_Rebase\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2020-08-19 08:04:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 10689364                                                           | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0xd2ada6da2d376d120616ae46ae20268e88b96c98cb86d52dc82043ed8acb96f7 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 89                                                                 | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| epoch                 | VARCHAR   | 14                                                                 |                                                              |
| prevYamsScalingFactor | VARCHAR   | 11123071445415645438                                               |                                                              |
| newYamsScalingFactor  | VARCHAR   | 10798116097200350819                                               |                                                              |

## 32. Table: YAMDelegator\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-22 14:58:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10710714                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x49c559c6f4ebdc91653fe792ed594ec045788a0bb6567a6136e14c4b52ddf342 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e2298e3b3390e3b945a5456fbf59ecc3f55da16                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc5b6488c7d5bed173b76bd5dca712f45fb9eaeab                         |                                                              |
| to                | VARCHAR   | 0xfb626333099a91ab677bcd5e9c71bc4dbe0238a8                         |                                                              |
| amount            | VARCHAR   | 21318490663253968360674                                            |                                                              |

## 33. Table: YAMETHPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:07:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636671                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe821b2f8ca9a4a7667f3cec5aaac4de35066391cf959c630459697c2d62b8912 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x587a07ce5c265a38dd6d42def1566ba73eeb06f5                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |

## 34. Table: YAMETHPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeae8e7fb3c1ef4bfecafec2c9bcf75fb5324a3d6e05fab0d4782fdec3738a3bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 184                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x587a07ce5c265a38dd6d42def1566ba73eeb06f5                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 35. Table: YAMETHPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-13 09:02:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10650706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74edc881887de9f8efe6d993448be000b186ec9aa135d45c9aa6a3b6212c0d48 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x587a07ce5c265a38dd6d42def1566ba73eeb06f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xe6410ecbaa041a5dcde79164ca66de42a8d72bee                         |                                                              |
| reward            | VARCHAR   | 261510513872516304542                                              |                                                              |

## 36. Table: YAMETHPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 19:34:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10640561                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb56fc650f1a0a1b31063a675a6738d2411cce2d68da09715a8455eb9095607a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 221                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x587a07ce5c265a38dd6d42def1566ba73eeb06f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1a6a15bf5e616332e742990f34298d2c513a3631                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000                                                |                                                              |

## 37. Table: YAMETHPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-15 10:24:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10866056                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22affb5faa625c65c5c2378e1f8d580da60a76bf630c2342fcd66493fde8014d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 135                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x587a07ce5c265a38dd6d42def1566ba73eeb06f5                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xe1b185849eb5688e1276eb0a9ce648b50e791fee                         |                                                              |
| amount            | VARCHAR   | 3600000000000000000                                                |                                                              |

## 38. Table: YAMLENDPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:23:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636740                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd27e1df912abbc55c960f05e8657cac2790d1b665e2f32b0f664fa98b3a114d0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6009a344c7f993b16eba2c673fefd2e07f9be5fd                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |
| newOwner          | VARCHAR   | 0xae99ff8fe2236af5083ea979ecf1dbaa0efd07e3                         |                                                              |

## 39. Table: YAMLENDPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f42e94f97b5ad7b5db7569f2fc62ebf301a875a9f084c44bb6cb0cbed153ee6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6009a344c7f993b16eba2c673fefd2e07f9be5fd                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 40. Table: YAMLENDPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-16 20:36:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10673288                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8bbf6cd9389e7baa138cc1eddf623f5278a1004a20b86413dc2d204a3058d0c6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6009a344c7f993b16eba2c673fefd2e07f9be5fd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x37d50885b44500a2eacab7c93dd349590600f05f                         |                                                              |
| reward            | VARCHAR   | 162486604331226936052                                              |                                                              |

## 41. Table: YAMLENDPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-17 15:53:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10678446                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf539e17be51ae0b51edbe628a972d8e3f99b0c54d32a745858aa941f05429abb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6009a344c7f993b16eba2c673fefd2e07f9be5fd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x9b29b87b8428fab4228a16d8d38a6482cb7e68eb                         |                                                              |
| amount            | VARCHAR   | 9473090432850388293633                                             |                                                              |

## 42. Table: YAMLENDPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-23 11:32:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10716315                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e0f262e641f61d243c8e75cd1662b210d96b1f3b6ee6b1eb668affcfa002383 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 203                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6009a344c7f993b16eba2c673fefd2e07f9be5fd                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x5262a040f3f7aa9341e0dec4e34cf6f1121ecf70                         |                                                              |
| amount            | VARCHAR   | 204900000000000000000                                              |                                                              |

## 43. Table: YAMLINKPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:23:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636740                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9fc927164d6dd8eb9fd13715ce69386155e7748a5e168761b4f7b181a991cfd2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 267                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfdc28897a1e32b595f1f4f1d3ae0df93b1eee452                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |
| newOwner          | VARCHAR   | 0xae99ff8fe2236af5083ea979ecf1dbaa0efd07e3                         |                                                              |

## 44. Table: YAMLINKPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe2d12ae24b0a8679337bb9e7c85662696eae6274edcaf4c3be1217dacb816ed4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 186                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfdc28897a1e32b595f1f4f1d3ae0df93b1eee452                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 45. Table: YAMLINKPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-14 00:28:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10654863                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xebd9ea637da107125d8ec89393bc6489e4a5265739c14d7b5bfa0576df434350 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 131                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfdc28897a1e32b595f1f4f1d3ae0df93b1eee452                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0091ba2b0ce0d1b279a661a2de11701a3cda57c7                         |                                                              |
| reward            | VARCHAR   | 42184232321156369049                                               |                                                              |

## 46. Table: YAMLINKPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-15 02:49:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10662047                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf030e62e8b06fb5f664288c8670e853a287fedc237a8060da3faae32772df5de | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 13                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfdc28897a1e32b595f1f4f1d3ae0df93b1eee452                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x04c843c465106d460e067ebbf9f7b8f5aee461c0                         |                                                              |
| amount            | VARCHAR   | 20000000000000000000000                                            |                                                              |

## 47. Table: YAMLINKPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-21 15:18:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10704348                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29601602676c4f2baffa1db1e0df1e3e423f0f823fc138f729023da2032a0690 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfdc28897a1e32b595f1f4f1d3ae0df93b1eee452                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0d75b30b65fec765dde3b275de3977cdf2b6bab2                         |                                                              |
| amount            | VARCHAR   | 5706013748410000000000                                             |                                                              |

## 48. Table: YAMMKRPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:23:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636740                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa2ccc1bb87223d76f20a2cb284dc400db74993b13448177d4d417969be75bb91 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 266                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcfe1e539acb2d489a651ca011a6eb93d32f97e23                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |
| newOwner          | VARCHAR   | 0xae99ff8fe2236af5083ea979ecf1dbaa0efd07e3                         |                                                              |

## 49. Table: YAMMKRPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92021358b51f9073592801a6e75744626f6d1fd38fca5d50f31d7f0364ff2523 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 185                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcfe1e539acb2d489a651ca011a6eb93d32f97e23                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 50. Table: YAMMKRPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 01:53:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10687683                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x75bafac7d9210fb32e27ac4c7e9bebab82559934c277c4de3fdeaa1f11fdeeb5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcfe1e539acb2d489a651ca011a6eb93d32f97e23                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0154d25120ed20a516fe43991702e7463c5a6f6e                         |                                                              |
| reward            | VARCHAR   | 748667010096253730829                                              |                                                              |

## 51. Table: YAMMKRPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-17 01:39:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10674693                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x80d88d0a205666c7838ec9a5e9e231cc8ed84973302420a719f2ea416fb25b57 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 221                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcfe1e539acb2d489a651ca011a6eb93d32f97e23                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x01b059ee5772b03a7109b84c6885e436eb60c5dc                         |                                                              |
| amount            | VARCHAR   | 200000000000000000000                                              |                                                              |

## 52. Table: YAMMKRPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-22 02:21:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10707357                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x86b19eaba214ec1a259dbb69251ddee1069b4734c7195bed73ce8f98d5bacd73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 277                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcfe1e539acb2d489a651ca011a6eb93d32f97e23                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xb16a53610fa8b08455e88d73f1189aae2b8b0de8                         |                                                              |
| amount            | VARCHAR   | 70000000000000000                                                  |                                                              |

## 53. Table: YAMSNXPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:15:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636703                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x710a688eee59aa30ed2aa012b6dcca2c341b7371798e20bf6655e0513f87401a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3fc1ffdb14d92394f40eec91d9ce8b807f132d                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |

## 54. Table: YAMSNXPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x028582e76915305dd0720fd9dfec76e0630bfe7eb17dd6059b6b5b8fd6b6a6bf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 187                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3fc1ffdb14d92394f40eec91d9ce8b807f132d                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 55. Table: YAMSNXPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-04 21:46:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10797392                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4d00180cf85ae65c888a3020110380736b9b2538954e3b0250d986f66ca5737 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3fc1ffdb14d92394f40eec91d9ce8b807f132d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xf326d3a28d326c15bcb98881048849739fcf5364                         |                                                              |
| reward            | VARCHAR   | 36406400201285307764                                               |                                                              |

## 56. Table: YAMSNXPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 20:45:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10640900                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x045ddf354595a4f118714e7cf9b88cfbe8c5ab98990d129fefd38ae618bfdcaf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3fc1ffdb14d92394f40eec91d9ce8b807f132d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xda248cc10b477c1144219183ec87b0621dac37b3                         |                                                              |
| amount            | VARCHAR   | 1245000000000000000000                                             |                                                              |

## 57. Table: YAMSNXPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-16 01:48:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10668241                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4fda6cd89e14650bbe3f124196568129d3702c1171d162711e96a3c5987a869a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c3fc1ffdb14d92394f40eec91d9ce8b807f132d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x1a1fed4157f0eaecdcd1dc4749c74765754a6594                         |                                                              |
| amount            | VARCHAR   | 495000000000000000000                                              |                                                              |

## 58. Table: YAMYFIPool\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:10:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636680                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe50e34e710602cb8f78247bf2b66efb61c8ca33b9911e59229457067e3c29554 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5b6488c7d5bed173b76bd5dca712f45fb9eaeab                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x683a78ba1f6b25e29fbbc9cd1bfa29a51520de84                         |                                                              |

## 59. Table: YAMYFIPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-11 05:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10636725                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd1ed692c1794d125949ecb3b1c36e635f760ad5f6b42d33b5007c223142441cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 180                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5b6488c7d5bed173b76bd5dca712f45fb9eaeab                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 250000000000000000000000                                           |                                                              |

## 60. Table: YAMYFIPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 08:08:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10689388                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1feb3aedcc4e131a8dcebab39441e38ed64468fad3960893e8949eae84ea407f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5b6488c7d5bed173b76bd5dca712f45fb9eaeab                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xd72708e95577f80056fd6a44ec30d644b5a86486                         |                                                              |
| reward            | VARCHAR   | 219862851618500400822                                              |                                                              |

## 61. Table: YAMYFIPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-17 15:56:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10678471                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x77644b8af743b290442e8c529470466987c087fee23f0cd6e67277d79ae31283 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5b6488c7d5bed173b76bd5dca712f45fb9eaeab                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x04e82683c964b9a71b6f653f57ea1c8ed0a216d8                         |                                                              |
| amount            | VARCHAR   | 614746391910368201                                                 |                                                              |

## 62. Table: YAMYFIPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-17 05:29:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10675697                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7b1a726f82c7ff06e161fd5fccf78d31ef3fb8f3bd4adec2941148a2d9298664 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc5b6488c7d5bed173b76bd5dca712f45fb9eaeab                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xa75cd63034c3fbbaef11ab7a80bf17bc4e21291d                         |                                                              |
| amount            | VARCHAR   | 199237493373030770551                                              |                                                              |
