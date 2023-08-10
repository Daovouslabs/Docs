# aragon

## 1. Table: ACL\_event\_ChangePermissionManager\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-25 04:32:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9939489                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb64d08ee8944abeb6732eb87ad23afe8e2300a3c1408ebb5f3ad96d3289cb1c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x23d06732d7466ad1ab71c38a03aefc1b46a57f73                         | Address of the contract that produced the log                |
| app               | VARCHAR   | 0x23d06732d7466ad1ab71c38a03aefc1b46a57f73                         |                                                              |
| role              | VARCHAR   | 0x0b719b33c83b8e5d300c521cb8b54ae9bd933996a14bef8c2f4e0285d2d2400a |                                                              |
| manager           | VARCHAR   | 0xb9da44c051c6cc9e04b7e0f95e95d69c6a6d8031                         |                                                              |

## 2. Table: ACL\_event\_SetPermissionParams\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-01 22:47:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9983115                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7e777268c31a223930721e5ac22e7580ba502b0ec5f91b415894f37c8c57e99 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x089a8dcd9f37d9d23699789dd0f9fddaf235557e                         | Address of the contract that produced the log                |
| entity            | VARCHAR   | 0x387eacfd4dcb6a983cb537128e3f3fa5c645a080                         |                                                              |
| app               | VARCHAR   | 0xd5323227c25d92362beabd010f23d39194d95805                         |                                                              |
| role              | VARCHAR   | 0x5de467a460382d13defdc02aacddc9c7d6605d6d4e0b8bd2f70732cae8ea17bc |                                                              |
| paramsHash        | VARCHAR   | 0xccbe3c384578965dcdcc9b77e3d23c088e6036e76209bf2c4c0ee09efca6e8db |                                                              |

## 3. Table: ACL\_event\_SetPermission\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-08 04:31:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12391512                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x032f3a5a33d2472f0c3ba11b5fecbb6c0b396a20eddb7934ae232bbb022c86b4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 273                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3724eaa559552caf1392a94f1c00a995667e88e8                         | Address of the contract that produced the log                |
| entity            | VARCHAR   | 0xbaf36227160a1468b9f2a90b1194fa34d00ef38f                         |                                                              |
| app               | VARCHAR   | 0x27bb950db044c3c03d9c7cf58737a9446ac21e58                         |                                                              |
| role              | VARCHAR   | 0x5de467a460382d13defdc02aacddc9c7d6605d6d4e0b8bd2f70732cae8ea17bc |                                                              |
| allowed           | VARCHAR   | true                                                               |                                                              |

## 4. Table: Agent\_event\_AddProtectedToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-02-23 19:24:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9541505                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x62849e043c903fd9d0db2f881911f989c6ec72d141e8499fe3409a67432ebd61 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb3b44d6e2be31844835d27e735440ee6e0a82c91                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x960b236a07cf122663c4303350609a66a7b288c0                         |                                                              |

## 5. Table: Agent\_event\_Execute\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-14 23:43:28+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9672631                                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3d82e1d78c3cadf32d6d5a0562cd1ecacae74a3db8c75cf486f935a393513ef                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 135                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1d0d3d83f883ab4e6d9fd24b3a29e72e78600390                                                           | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x51e91b64f36a0169986f8a1fdca70fca212f399c                                                           |                                                              |
| target            | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                                                           |                                                              |
| ethValue          | VARCHAR   | 0                                                                                                    |                                                              |
| data              | VARCHAR   | 0x095ea7b3000000000000000000000000200c142d18892ce0589e2bd93617a524692ac5e300000000000000000000000000 |                                                              |

## 6. Table: Agent\_event\_SafeExecute\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-11 15:05:01+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8915072                                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf4edd504087d97ede2863d9440f353aab4d881db1af0badbdbbc1390679dca59                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 199                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb84daf0280ce50251d55c86c6b1bc53c5e7d9ca                                                           | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x885912e005098430e0a6d426fe6f0439e48e0bd3                                                           |                                                              |
| target            | VARCHAR   | 0x9062c0a6dbd6108336bcbe4593a3d1ce05512069                                                           |                                                              |
| data              | VARCHAR   | 0xc47f0027000000000000000000000000000000000000000000000000000000000000002000000000000000000000000000 |                                                              |

## 7. Table: Agent\_event\_ScriptResult\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-21 16:29:47+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17529232                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x127a595c99383ad25784dc9a1f837df54e2a503e6c0232897f19f8f9886f5462                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x336252602b3a8a0be336ed942228305173e8082b                                                           | Address of the contract that produced the log                |
| executor          | VARCHAR   | 0x5ceb19e1890f677c3676d5ecdf7c501eba01a054                                                           |                                                              |
| script            | VARCHAR   | 0x000000015cb5ba62dc8ced477f20d4692986f1cd421747610000002419165587000000000000000000000000a117000000 |                                                              |
| input             | VARCHAR   | 0x                                                                                                   |                                                              |
| returnData        | VARCHAR   | 0x                                                                                                   |                                                              |

## 8. Table: Agent\_event\_VaultDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-29 01:47:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17795516                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xba676883b4e8f0926aad0b4e522340bcf2e90b2e7e127fc02232fd2c8288ddbe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 194                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x9a6ebe7e2a7722f8200d0ffb63a1f6406a0d7dce                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| sender            | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                         |                                                              |
| amount            | VARCHAR   | 50000000000000                                                     |                                                              |

## 9. Table: DAOFactory\_event\_DeployDAO\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-08 12:29:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13378214                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x00f2ec4ffb65dfca9a432977b17e2bcc9bb000de1f1665a81024f08a8a5be36e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb9da44c051c6cc9e04b7e0f95e95d69c6a6d8031                         | Address of the contract that produced the log                |
| dao               | VARCHAR   | 0xe38668387c3d2cfa0cc5db40a77ee53de5fc62f1                         |                                                              |

## 10. Table: DAOFactory\_event\_DeployEVMScriptRegistry\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-01-08 06:19:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7029804                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1e9671415c9ff6b5036a5ca15559e089f8fca6d5bf60ce0a26088777ba19d226 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 22                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x595b34c93aa2c2ba0a38daeede629a0dfbdcc559                         | Address of the contract that produced the log                |
| reg               | VARCHAR   | 0x8de2c7bc1763134a5149e026478bb739d954f78e                         |                                                              |

## 11. Table: EVMScriptRegistry\_event\_EnableExecutor\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-14 23:44:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10863149                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xecd58f5c28065ce49a37a30141e4d497618ea276b96e43767df59059a7750c89 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2f13a85620bd59cf39e12ecb175e0386726c1723                         | Address of the contract that produced the log                |
| executorId        | VARCHAR   | 1                                                                  |                                                              |
| executorAddress   | VARCHAR   | 0x5ceb19e1890f677c3676d5ecdf7c501eba01a054                         |                                                              |

## 12. Table: Finance\_event\_NewPeriod\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-11 19:02:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9261355                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf29485c38d4f3880ce754123a964390898e1b39e004da270abd709d51a7b5b74 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x64a84f667268df3120956b0d2e2498b8fa503b56                         | Address of the contract that produced the log                |
| periodId          | VARCHAR   | 0                                                                  |                                                              |
| periodStarts      | VARCHAR   | 1578769356                                                         |                                                              |
| periodEnds        | VARCHAR   | 1581361355                                                         |                                                              |

## 13. Table: Finance\_event\_NewTransaction\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 09:15:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14595489                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbed87ac57d722b171daf92885a3330bd38d392d55db5f965990af58cb4ddf57b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 152                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1fafda0d9039e4aabfa7b4e293b1196212a704b7                         | Address of the contract that produced the log                |
| transactionId     | VARCHAR   | 200                                                                |                                                              |
| incoming          | VARCHAR   | false                                                              |                                                              |
| entity            | VARCHAR   | 0xf43e5bb41351a97d0eb6fa34249b1392604133b7                         |                                                              |
| amount            | VARCHAR   | 1000000000000000000                                                |                                                              |
| reference         | VARCHAR   |                                                                    |                                                              |

## 14. Table: JurorsRegistry\_event\_JurorActivated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-26 01:07:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10732980                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0cc692198ececc7c7a1a6272d77b5537cb8751a985fcef38391c3624b331390 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 174                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| juror             | VARCHAR   | 0xea74e048ccecd7ade98491fe9683a686bee73aec                         |                                                              |
| fromTermId        | VARCHAR   | 594                                                                |                                                              |
| amount            | VARCHAR   | 10222578515432927590388                                            |                                                              |
| sender            | VARCHAR   | 0xea74e048ccecd7ade98491fe9683a686bee73aec                         |                                                              |

## 15. Table: JurorsRegistry\_event\_JurorBalanceLocked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-01 18:07:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10776833                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7ca51878c92cc4ccc7ada9849213d5b1669ccdf2003bb6ae2cb1163c2aa9b1c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 195                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| juror             | VARCHAR   | 0x9ab0b3323b1c9035b90ca4f1e462bb72c5417503                         |                                                              |
| amount            | VARCHAR   | 3000000000000000000000                                             |                                                              |

## 16. Table: JurorsRegistry\_event\_JurorBalanceUnlocked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-19 16:05:51+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10097312                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b5f6be6f77783a4366bc947ed6c853adf6588d9fcdd6e0179290cc9e663678c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| juror             | VARCHAR   | 0x543dd7aab977db9acc05a84058bfb957b1275f95                         |                                                              |
| amount            | VARCHAR   | 3000000000000000000000                                             |                                                              |

## 17. Table: JurorsRegistry\_event\_JurorDeactivationProcessed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-15 08:19:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13028619                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x30753e41d7ba79ec0f846287b128bac8655a166c881447a7ca84a70715ef9732 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 267                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| juror             | VARCHAR   | 0xc7f91d9f1a2609c89d600bacf38a21f09e77ddd8                         |                                                              |
| availableTermId   | VARCHAR   | 1656                                                               |                                                              |
| amount            | VARCHAR   | 10000000000000000000000                                            |                                                              |
| processedTermId   | VARCHAR   | 1656                                                               |                                                              |

## 18. Table: JurorsRegistry\_event\_JurorDeactivationRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-16 16:41:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9683728                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x435d40feb04ec53f75c082931372d25b66150aa8e4b55fb562c9d3fde58fb71b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| juror             | VARCHAR   | 0x73ff129a689364996432a1a3a4587e3f132b67da                         |                                                              |
| availableTermId   | VARCHAR   | 107                                                                |                                                              |
| amount            | VARCHAR   | 77705411061911670721900                                            |                                                              |

## 19. Table: JurorsRegistry\_event\_JurorSlashed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-27 16:12:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9955515                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x73b2115833d982d3f86f1e7bc6ec7bf3f15bbfffb2e85cee00deb8f4a547b9d7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| juror             | VARCHAR   | 0x7a0d32cdd4511956d7c751a7bb7beace2321e17d                         |                                                              |
| amount            | VARCHAR   | 3000000000000000000000                                             |                                                              |
| effectiveTermId   | VARCHAR   | 233                                                                |                                                              |

## 20. Table: JurorsRegistry\_event\_JurorTokensAssigned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-19 16:34:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10097444                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec2830522517c72adb783c3638f83fe1aa99c2f325a80cfc8584a9d0070c6156 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| juror             | VARCHAR   | 0x543dd7aab977db9acc05a84058bfb957b1275f95                         |                                                              |
| amount            | VARCHAR   | 6000000000000000000000                                             |                                                              |

## 21. Table: JurorsRegistry\_event\_JurorTokensBurned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-20 20:02:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10104843                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x070db2520672c4b2e9ac4c6da3450557bdb2a8dc9554a0ea01c681c7a8b833f8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| amount            | VARCHAR   | 9000000000000000000000                                             |                                                              |

## 22. Table: JurorsRegistry\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-11 15:00:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9650899                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x02959ca7b190c132894644341302aa87c00cdeb50c7d09a1ed1105cc68cc927f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 150                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x58cecfe9f9c1e8e96c241c564f791a5d62275493                         |                                                              |
| amount            | VARCHAR   | 30579613400247345122845                                            |                                                              |
| total             | VARCHAR   | 30579613400247345122845                                            |                                                              |
| data              | VARCHAR   | 0xb260c42a65bc7e60dc6a2d0b885734c9766df021978fc91e8490cde094eeb6ee |                                                              |

## 23. Table: JurorsRegistry\_event\_TotalActiveBalanceLimitChanged\_history

| Column                          | Type      | Example                                                            | Description                                                  |
| ------------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp                | TIMESTAMP | 2020-02-07 16:29:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                   | INTEGER   | 9436631                                                            | The block number where this event was emitted                |
| transaction\_hash               | VARCHAR   | 0xe971239444563c7ec6925ffc1e8f4575854c2d7af2e55972378f00ce77ef6c66 | Hash of the transactions in which this event was emitted     |
| log\_index                      | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address               | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| previousTotalActiveBalanceLimit | VARCHAR   | 0                                                                  |                                                              |
| currentTotalActiveBalanceLimit  | VARCHAR   | 184467440737095510000000000000000000000                            |                                                              |

## 24. Table: JurorsRegistry\_event\_Unstaked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-20 05:36:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10100983                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e2b6955dcdc4343ea1d74d921bef4487b24420b3c4c7e5b666948ee0fc934ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0f7471c1df2021ff45f112878f755aabe7aa16bf                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xb5474aa6accaf2ce461466a860fbc441edf785c6                         |                                                              |
| amount            | VARCHAR   | 200000000000000000000                                              |                                                              |
| total             | VARCHAR   | 10275471264904308236630                                            |                                                              |
| data              | VARCHAR   | 0x                                                                 |                                                              |

## 25. Table: Kernel\_event\_NewAppProxy\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-15 01:23:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15972133                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2fc05eda6ac99f52b08cf8fc2764a25065601bc505da58cd2f6fcd5a5a164aa6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 381                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1046a4c6cfd7a81223afdcb35208f2884d7a6832                         | Address of the contract that produced the log                |
| proxy             | VARCHAR   | 0x77c27406b76e962e5e8056eb3ad48e758c719709                         |                                                              |
| isUpgradeable     | VARCHAR   | true                                                               |                                                              |
| appId             | VARCHAR   | 0xbf8491150dafc5dcaee5b861414dca922de09ccffa344964ae167212e8c673ae |                                                              |

## 26. Table: Kernel\_event\_SetApp\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-22 09:13:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7808753                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaffea537999e89fc8289212a09ec586f1e38224c8b77e6710a526a91989b19a2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 36                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x784c16504fd1a13b4dd428ba117e95c88046b133                         | Address of the contract that produced the log                |
| namespace         | VARCHAR   | 0xc681a85306374a5ab27f0bbc385296a54bcd314a1948b6cf61c4ea1bc44bb9f8 |                                                              |
| appId             | VARCHAR   | 0x3b4bf6bf3ad5000ecf0f989d5befde585c6860fea3e574a4fab4c49d1c177d9c |                                                              |
| app               | VARCHAR   | 0x4a6ce97a84178a84c1cee46a763db619d0e6e413                         |                                                              |

## 27. Table: TokenManager\_event\_NewVesting\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-21 02:25:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15381330                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2dc8fb4c94f82d9b858e69ac982c590e208936ea9b833c05cc64ea1ab92fdc9b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50a7c5a2aa566eb8aafc80ffc62e984bfece334f                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0x512b9e224e7cdb89656d9b2ffbae4ed0acb6c406                         |                                                              |
| vestingId         | VARCHAR   | 2                                                                  |                                                              |
| amount            | VARCHAR   | 75000000000000000000000                                            |                                                              |

## 28. Table: TokenManager\_event\_RevokeVesting\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-23 15:01:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16248183                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc2804a68b308f7630b9b49cfc4422534bd6424e9f607e5ba9931066ca44d84ad | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 343                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xad5166841ddde094d20e9453eef5968dde385482                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0x8974ed381e5f9536afc1da45ab25e3a1c85facab                         |                                                              |
| vestingId         | VARCHAR   | 1                                                                  |                                                              |
| nonVestedAmount   | VARCHAR   | 1000000000000000000                                                |                                                              |

## 29. Table: TokenManager\_event\_ScriptResult\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-08-16 05:13:15+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8359544                                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92920dd33108b42b9eda92ca5a025080cdad1b06ae7c800a3ccac031572be387                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x23993052342e99a51915e8923ade63512af93743                                                           | Address of the contract that produced the log                |
| executor          | VARCHAR   | 0x60177692b61777ab7bca2f9c12b82c0c87d9434d                                                           |                                                              |
| script            | VARCHAR   | 0x000000018f90fa255f5ab26d4ae9075a5e1ab54bbe5f015900000124d948d4680000000000000000000000000000000000 |                                                              |
| input             | VARCHAR   | 0x                                                                                                   |                                                              |
| returnData        | VARCHAR   | 0x                                                                                                   |                                                              |

## 30. Table: Vault\_event\_VaultDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-01 15:03:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8657172                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3eb4dbd27018ae81c9cb0efb30cd2532f18479726c253f4a05d450262aa3e632 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa7d9aa201734c6b9fb2ba8cdd15a83dc96abe804                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| sender            | VARCHAR   | 0x6690994f7659ab0f80766990a66186e69c77d5ae                         |                                                              |
| amount            | VARCHAR   | 20000000000000000                                                  |                                                              |

## 31. Table: Vault\_event\_VaultTransfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-25 09:21:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14454587                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3d5de3a03ba23a81191d5cbcbfcb984a665d1d90f00b53935a19e6a7a150a857 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 471                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xabfd88db78d2503af372cb9c21cdc2f181232b4f                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x89ab32156e46f46d02ade3fecbe5fc4243b9aaed                         |                                                              |
| to                | VARCHAR   | 0xa69b574f4e97819205e6bc55b4aa2ec34d7f514a                         |                                                              |
| amount            | VARCHAR   | 913500000000000000000                                              |                                                              |

## 32. Table: Voting\_event\_CastVote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-01 10:29:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17385373                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa9e423f6cac0cd79dabe0b6ae6b3e731fd29a3c3f9bb32e6eba15b5d2a11de40 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 282                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6c871f1fc69c23809413a96fb359cb428245aa60                         | Address of the contract that produced the log                |
| voteId            | VARCHAR   | 457                                                                |                                                              |
| voter             | VARCHAR   | 0x81c4dbf721a0a483b18de563850d939a11624128                         |                                                              |
| supports          | VARCHAR   | true                                                               |                                                              |
| stake             | VARCHAR   | 1                                                                  |                                                              |

## 33. Table: Voting\_event\_ChangeMinQuorum\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2020-01-28 21:41:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 9373005                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xf25d63f01f6f2ae13b0d2aa928370373f564df2c226cfdf9263adad303f179da | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x41e83d829459f99bf4ee2e26d0d79748fb16b94f                         | Address of the contract that produced the log                |
| minAcceptQuorumPct | VARCHAR   | 599999999999999999                                                 |                                                              |

## 34. Table: Voting\_event\_ChangeSupportRequired\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2020-04-22 22:45:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 9925038                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x87dd31bbce98fe4209297bc70c519d06018cb3839956c8d45cb4320572444877 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x387eacfd4dcb6a983cb537128e3f3fa5c645a080                         | Address of the contract that produced the log                |
| supportRequiredPct | VARCHAR   | 600000000000000000                                                 |                                                              |

## 35. Table: Voting\_event\_ExecuteVote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-07 19:17:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15920183                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcecb8a60a98e9cdf18ad1944ab3f60a0bfaf04f9ee3533fba5a4425d5946b91d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 270                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2c59f6160980b7755053d1f54a86fe6b44dbde92                         | Address of the contract that produced the log                |
| voteId            | VARCHAR   | 5                                                                  |                                                              |

## 36. Table: Voting\_event\_ScriptResult\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-31 07:22:53+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8845149                                                                                              | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b38cd3b83d5e134f84618484b456a40d88721ffce3e42b8abf224fd1ced4e08                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 152                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x21c1bc26b885a1bce53fb4fe42ff5c237b45ce9f                                                           | Address of the contract that produced the log                |
| executor          | VARCHAR   | 0x5ceb19e1890f677c3676d5ecdf7c501eba01a054                                                           |                                                              |
| script            | VARCHAR   | 0x00000001357bafc444fad3b03ef0a2241314ea60f176c0e40000004440c10f19000000000000000000000000c690045bca |                                                              |
| input             | VARCHAR   | 0x                                                                                                   |                                                              |
| returnData        | VARCHAR   | 0x                                                                                                   |                                                              |

## 37. Table: Voting\_event\_StartVote\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-09 10:18:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12599760                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5377b9c47496c3fa64403ea64ac8340fb35de9951da18dc75bd1ec5977a8aa22 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ba7dc7db8fdb59e2fb21df349ba3deac74ba0eb                         | Address of the contract that produced the log                |
| voteId            | VARCHAR   | 0                                                                  |                                                              |
| creator           | VARCHAR   | 0xefc3218290ade0b092a49cf9566c674875f73591                         |                                                              |
| metadata          | VARCHAR   |                                                                    |                                                              |
