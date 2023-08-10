# cheezewizards

## 1. Table: BasicTournament\_event\_AscensionChallenged\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-11-20 06:48:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 8966913                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x054fdcfc1026e16ac11561a0dc0451472ea79895928a1b40686378e28d1e5bb4 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 151                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| ascendingWizardId   | VARCHAR   | 3832                                                               |                                                              |
| challengingWizardId | VARCHAR   | 4043                                                               |                                                              |
| commitment          | VARCHAR   | 0x82035d9033d1ec109bc3abb0e7c07f46399fe6575a58eaeb6d16c2bfbb31d50b |                                                              |

## 2. Table: BasicTournament\_event\_AscensionComplete\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-08 06:12:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8894588                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0339afb14b99f2b690b14a4e42489fefe31acd46a03908a93c4d2362e576337 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 2126                                                               |                                                              |
| power             | VARCHAR   | 0                                                                  |                                                              |

## 3. Table: BasicTournament\_event\_AscensionPairUp\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-13 10:44:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8925985                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed0bda2dac019125ce0fb8eaaf920e19dad04502500dc365b0233d63e02dc371 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 139                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| wizardId1         | VARCHAR   | 2513                                                               |                                                              |
| wizardId2         | VARCHAR   | 6207                                                               |                                                              |

## 4. Table: BasicTournament\_event\_AscensionStart\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-19 21:43:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8964695                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14f52a6b9d2438ee761eb5d004ca57d7b065866a891465dd0ef915de624c3cf0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 85                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 230                                                                |                                                              |

## 5. Table: BasicTournament\_event\_CEOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-11 23:56:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8723430                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd9d11b031d1c86633eeadfd6c533236da775a061c89cdeea98fe49876019186 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| previousCeo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCeo            | VARCHAR   | 0x9fe2712d5bdcc4a7653352a595e2938ca94acde6                         |                                                              |

## 6. Table: BasicTournament\_event\_COOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-11 23:56:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8723430                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd9d11b031d1c86633eeadfd6c533236da775a061c89cdeea98fe49876019186 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 21                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| previousCoo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCoo            | VARCHAR   | 0xd880d895ce716afc1e5e21cb901b5093701842e4                         |                                                              |

## 7. Table: BasicTournament\_event\_DuelEnd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-13 20:21:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8928409                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa1a601b510359a292681d2d91e567a4ee6c36a0119c54b6d196609584cd69970 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| duelId            | VARCHAR   | 0x7e62488bff7a132db63140e48187279ac499b08d13e929ecdb422300e23a56b8 |                                                              |
| wizardId1         | VARCHAR   | 69                                                                 |                                                              |
| wizardId2         | VARCHAR   | 1985                                                               |                                                              |
| moveSet1          | VARCHAR   | 0x0202020202000000000000000000000000000000000000000000000000000000 |                                                              |
| moveSet2          | VARCHAR   | 0x0404040404000000000000000000000000000000000000000000000000000000 |                                                              |
| power1            | VARCHAR   | 1273450988413295                                                   |                                                              |
| power2            | VARCHAR   | 0                                                                  |                                                              |

## 8. Table: BasicTournament\_event\_DuelStart\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-20 08:03:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8967216                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf95d00e0b299e8db77186153a2290f36a8128b6a873c401b6d6cf86d4a6e19e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 158                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| duelId            | VARCHAR   | 0xcd7f9148713f54d7015419a3617e12a823bd12b17b234de56527431bafc21963 |                                                              |
| wizardId1         | VARCHAR   | 3832                                                               |                                                              |
| wizardId2         | VARCHAR   | 4043                                                               |                                                              |
| timeoutBlock      | VARCHAR   | 8968081                                                            |                                                              |
| isAscensionBattle | VARCHAR   | true                                                               |                                                              |
| commit1           | VARCHAR   | 0x793583753a9f5e2afe0a1fc5d6cf29cdfce6171ded4ca91d99471d7624c089f1 |                                                              |
| commit2           | VARCHAR   | 0x82035d9033d1ec109bc3abb0e7c07f46399fe6575a58eaeb6d16c2bfbb31d50b |                                                              |

## 9. Table: BasicTournament\_event\_DuelTimeOut\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-28 20:44:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8829977                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43a130e849ad40834f71145a36a64947053bdc51e559adfcdac8a776d3bffd4b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| duelId            | VARCHAR   | 0xe4ec73222c08e2ea09e97f11d3834f929b0884d80fca1a512877d7d37e371749 |                                                              |
| wizardId1         | VARCHAR   | 2351                                                               |                                                              |
| wizardId2         | VARCHAR   | 6062                                                               |                                                              |
| power1            | VARCHAR   | 116074218750000                                                    |                                                              |
| power2            | VARCHAR   | 0                                                                  |                                                              |

## 10. Table: BasicTournament\_event\_OneSidedCommitAdded\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2019-11-20 15:24:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 8969101                                                            | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x4a96c53283db0b65ba09749a7ec318379460c5944f369c0e104f9e138c511286 | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| committingWizardId    | VARCHAR   | 3832                                                               |                                                              |
| otherWizardId         | VARCHAR   | 6188                                                               |                                                              |
| committingWizardNonce | VARCHAR   | 9                                                                  |                                                              |
| otherWizardNonce      | VARCHAR   | 19                                                                 |                                                              |
| commitment            | VARCHAR   | 0x355587c3e03a51cfbd7be80760e3cc79ad70e9b40860347bd77104c5aa57f51d |                                                              |

## 11. Table: BasicTournament\_event\_OneSidedRevealAdded\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2019-10-23 00:23:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 8793453                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xb7ad08c0f9241c276d74ff96a7f4e76e19037e709172284713047e011f80f3cc | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| duelId             | VARCHAR   | 0x11dc4b362aac8d7a766cfa108e687ff62e0d38feb1be0b49aa29da833e776fe0 |                                                              |
| committingWizardId | VARCHAR   | 6183                                                               |                                                              |
| otherWizardId      | VARCHAR   | 5100                                                               |                                                              |

## 12. Table: BasicTournament\_event\_PowerTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-07 12:11:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8889937                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7c60050e992414843fa1c10fcb3b1ff0b0a0a3d48bd8e789e25cdba6c472742a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 106                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| sendingWizId      | VARCHAR   | 6036                                                               |                                                              |
| receivingWizId    | VARCHAR   | 3508                                                               |                                                              |
| amountTransferred | VARCHAR   | 70000000000000                                                     |                                                              |
| reason            | VARCHAR   | 3                                                                  |                                                              |

## 13. Table: BasicTournament\_event\_PrizeClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-22 06:20:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8978856                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b8611c5f04402ed6b93a6afc33ed3aad9c79ec3f3e2459d85c5bea1b5c98bc2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 77                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| claimingWinnerId  | VARCHAR   | 3508                                                               |                                                              |
| prizeAmount       | VARCHAR   | 190828818913857076500                                              |                                                              |

## 14. Table: BasicTournament\_event\_Revive\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-05 09:17:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8876724                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ddcdc178f8ebf1e5fd137cf0779ef17600ef96b2d449435d5f16d42b2158e28 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| wizId             | VARCHAR   | 61                                                                 |                                                              |
| power             | VARCHAR   | 420000000000000                                                    |                                                              |

## 15. Table: BasicTournament\_event\_WizardElimination\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-13 07:07:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8925091                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1db7566fa9b3e4bae6da3c4a95bb606e00b0485c539a2aa3a1e31a4c373a6335 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd903896aacc543abeef0deea9b2a27496f762ad                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 5284                                                               |                                                              |

## 16. Table: BasicTournament\_v1\_event\_AscensionChallenged\_history

| Column              | Type      | Example                                                            | Description                                                  |
| ------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2019-12-01 23:16:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 9034923                                                            | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x322994dfdec9995daf2d3af80abc212309b31238ba722f462d3df63b6e71fc47 | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| ascendingWizardId   | VARCHAR   | 3313                                                               |                                                              |
| challengingWizardId | VARCHAR   | 4845                                                               |                                                              |
| commitment          | VARCHAR   | 0x00751c69d156e039f35bdb80e51b9822eea69663014d9b92edf56187af5fa74e |                                                              |

## 17. Table: BasicTournament\_v1\_event\_AscensionComplete\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-18 10:55:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8956130                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3eb3746e4047ee403ecbbc3a3ab9db9018b0ee24b260e393c04b4b013cdb7a5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 6519                                                               |                                                              |
| power             | VARCHAR   | 54960937500000                                                     |                                                              |

## 18. Table: BasicTournament\_v1\_event\_AscensionPairUp\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-27 07:44:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9008692                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec531e825dbb84a21b5c8fa83bde01870e9d1bb24c8bbea0f9724a528c764ed2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| wizardId1         | VARCHAR   | 3189                                                               |                                                              |
| wizardId2         | VARCHAR   | 3200                                                               |                                                              |

## 19. Table: BasicTournament\_v1\_event\_AscensionStart\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-18 23:25:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8959197                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa4cac18086ea1903baf2544a6ee2d8451cb6c700cebae996e2dd947cc1e505f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 1181                                                               |                                                              |

## 20. Table: BasicTournament\_v1\_event\_CEOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 23:01:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8761334                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x239c963b8cc0ddbf4b268157e1e745cd4225b02cedca07f73b3cdda2c74c1e5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| previousCeo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCeo            | VARCHAR   | 0x9fe2712d5bdcc4a7653352a595e2938ca94acde6                         |                                                              |

## 21. Table: BasicTournament\_v1\_event\_COOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 23:01:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8761334                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x239c963b8cc0ddbf4b268157e1e745cd4225b02cedca07f73b3cdda2c74c1e5a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 15                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| previousCoo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCoo            | VARCHAR   | 0xd880d895ce716afc1e5e21cb901b5093701842e4                         |                                                              |

## 22. Table: BasicTournament\_v1\_event\_DuelEnd\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-27 18:51:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9011332                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x865c35f5f0f25e35bde188f75619e054af01d00b01f0e3b1cfb61f4180733faa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| duelId            | VARCHAR   | 0x1375160ee6c7b0ff1e32ee5ff93961e7408d92539fd06b1c51239db64a0ef90c |                                                              |
| wizardId1         | VARCHAR   | 3699                                                               |                                                              |
| wizardId2         | VARCHAR   | 4908                                                               |                                                              |
| moveSet1          | VARCHAR   | 0x0404040404000000000000000000000000000000000000000000000000000000 |                                                              |
| moveSet2          | VARCHAR   | 0x0202020202000000000000000000000000000000000000000000000000000000 |                                                              |
| power1            | VARCHAR   | 0                                                                  |                                                              |
| power2            | VARCHAR   | 32620407773728466                                                  |                                                              |

## 23. Table: BasicTournament\_v1\_event\_DuelStart\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-27 22:31:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8824204                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa5b09982df821e7221a4465d78d9531e1604e4441838e8af1f37fba7bc06fefa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| duelId            | VARCHAR   | 0x28b9a88fdfe157be3747e1234eb5bdd061bbc1ee4831a3d365519130da5e42f4 |                                                              |
| wizardId1         | VARCHAR   | 4542                                                               |                                                              |
| wizardId2         | VARCHAR   | 6379                                                               |                                                              |
| timeoutBlock      | VARCHAR   | 8824607                                                            |                                                              |
| isAscensionBattle | VARCHAR   | false                                                              |                                                              |
| commit1           | VARCHAR   | 0xf63e1db26cd49a86cd9927ce1bcc34d5ea4d2eedb6298c5ee139d931d55d6c31 |                                                              |
| commit2           | VARCHAR   | 0x9322171116e68b7455752945cbf3a9e2a454d87c22c3fcdd8a310040a09cd56c |                                                              |

## 24. Table: BasicTournament\_v1\_event\_DuelTimeOut\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-26 00:47:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8812304                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e265f386cab114f7502e5514634412c90804c6163b1e074100e8132721c158d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 31                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| duelId            | VARCHAR   | 0xd34ec766355ffad55955ba439076c2bcd7ac5cd2a0afc1d4d4c732a6a50f8dea |                                                              |
| wizardId1         | VARCHAR   | 1889                                                               |                                                              |
| wizardId2         | VARCHAR   | 3324                                                               |                                                              |
| power1            | VARCHAR   | 65892285923336                                                     |                                                              |
| power2            | VARCHAR   | 0                                                                  |                                                              |

## 25. Table: BasicTournament\_v1\_event\_OneSidedCommitAdded\_history

| Column                | Type      | Example                                                            | Description                                                  |
| --------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp      | TIMESTAMP | 2019-11-25 20:40:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number         | INTEGER   | 9000490                                                            | The block number where this event was emitted                |
| transaction\_hash     | VARCHAR   | 0x613df6f74c71a2001a967947d92da582a855257a6e348c64d8968e274f27dc6f | Hash of the transactions in which this event was emitted     |
| log\_index            | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address     | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| committingWizardId    | VARCHAR   | 3364                                                               |                                                              |
| otherWizardId         | VARCHAR   | 1545                                                               |                                                              |
| committingWizardNonce | VARCHAR   | 5                                                                  |                                                              |
| otherWizardNonce      | VARCHAR   | 10                                                                 |                                                              |
| commitment            | VARCHAR   | 0xec042f5fe5c188bb4a8f48064afe1ca7c7417c6530f4c323c3847308f6c69ba2 |                                                              |

## 26. Table: BasicTournament\_v1\_event\_OneSidedCommitCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-30 19:23:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9028358                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x080a84517d4ffb5559f9f0ad3b4d37ee5a2bd4d45f4dc9164f86eed43da0bf8c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 4661                                                               |                                                              |

## 27. Table: BasicTournament\_v1\_event\_OneSidedRevealAdded\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2019-11-14 11:11:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 8932132                                                            | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0xe001be54995bf4410f24e4f11700a316774569d5b0d85a8118b6036b36a6d736 | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| duelId             | VARCHAR   | 0xacbc6161f3ce5613ec8b2bf3a8f537d86e93a876a4fcd4d3213ef44d55efbe48 |                                                              |
| committingWizardId | VARCHAR   | 6271                                                               |                                                              |
| otherWizardId      | VARCHAR   | 6730                                                               |                                                              |

## 28. Table: BasicTournament\_v1\_event\_PowerTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-22 10:11:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8979792                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca86437a08703cf781764d31ce24db72b0cda85632f780bc74f86be151d1e4f5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| sendingWizId      | VARCHAR   | 5761                                                               |                                                              |
| receivingWizId    | VARCHAR   | 2751                                                               |                                                              |
| amountTransferred | VARCHAR   | 457507833698763                                                    |                                                              |
| reason            | VARCHAR   | 2                                                                  |                                                              |

## 29. Table: BasicTournament\_v1\_event\_PrizeClaimed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-12-02 22:24:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9040395                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd4a7be292459185b0fc3d54a0b0ec1338e3b3098249bfb5bf3584c125e3ae5bc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 58                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| claimingWinnerId  | VARCHAR   | 4845                                                               |                                                              |
| prizeAmount       | VARCHAR   | 687209112384289801000                                              |                                                              |

## 30. Table: BasicTournament\_v1\_event\_Revive\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-26 07:13:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8813988                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf88d8bcce829efe15cc40241f026c61a28825af21a7d36500b0d9442b616d7c1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| wizId             | VARCHAR   | 4338                                                               |                                                              |
| power             | VARCHAR   | 2000000000000                                                      |                                                              |

## 31. Table: BasicTournament\_v1\_event\_WizardElimination\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-14 22:48:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8935033                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78acedc7aff6af49f990696dfd59f431047889accbac3faee5e7e5923e03b646 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x6d6c3beda37ba83a4962746c43e3a20db46399ec                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 1075                                                               |                                                              |

## 32. Table: InauguralGateKeeper\_event\_CEOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-11 23:48:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8723398                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc493cfceab6db0340c6133b5775c09c2607e13d0674420e459ebe6a5a1bf0c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x673b537956a28e40aaa8d929fd1b6688c1583dda                         | Address of the contract that produced the log                |
| previousCeo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCeo            | VARCHAR   | 0x9fe2712d5bdcc4a7653352a595e2938ca94acde6                         |                                                              |

## 33. Table: InauguralGateKeeper\_event\_CFOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-19 02:14:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8768544                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8a6d045709866745eec08daa99c707e72f2731df203d0617c9d212a6c766f511 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x673b537956a28e40aaa8d929fd1b6688c1583dda                         | Address of the contract that produced the log                |
| previousCfo       | VARCHAR   | 0x1607667f13da3d4960984a1e670b11755b46f49d                         |                                                              |
| newCfo            | VARCHAR   | 0x314414bea27d3d27ed2b9b9dc8a75a128744a1b1                         |                                                              |

## 34. Table: InauguralGateKeeper\_event\_COOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-11 23:48:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8723398                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc493cfceab6db0340c6133b5775c09c2607e13d0674420e459ebe6a5a1bf0c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 66                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x673b537956a28e40aaa8d929fd1b6688c1583dda                         | Address of the contract that produced the log                |
| previousCoo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCoo            | VARCHAR   | 0xd880d895ce716afc1e5e21cb901b5093701842e4                         |                                                              |

## 35. Table: InauguralGateKeeper\_v1\_event\_CEOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 22:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8761315                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x149af32ca148f0b6b3c76ccff7607d9aba151ed7aee9fdadf99eb88b82e277e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68132eb4bfd84b2d6a23ec4fb1b106f5c8574f2d                         | Address of the contract that produced the log                |
| previousCeo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCeo            | VARCHAR   | 0x9fe2712d5bdcc4a7653352a595e2938ca94acde6                         |                                                              |

## 36. Table: InauguralGateKeeper\_v1\_event\_CFOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 22:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8761315                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x149af32ca148f0b6b3c76ccff7607d9aba151ed7aee9fdadf99eb88b82e277e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 74                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68132eb4bfd84b2d6a23ec4fb1b106f5c8574f2d                         | Address of the contract that produced the log                |
| previousCfo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCfo            | VARCHAR   | 0xc09f4f0eae0b92ec1e3d93baeac46d8a5391483b                         |                                                              |

## 37. Table: InauguralGateKeeper\_v1\_event\_COOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-19 00:26:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8768050                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa694260c6f18f7c08e028d9896d378561e411a2f979f8c25ec0bca28433ce46b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 41                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x68132eb4bfd84b2d6a23ec4fb1b106f5c8574f2d                         | Address of the contract that produced the log                |
| previousCoo       | VARCHAR   | 0xd880d895ce716afc1e5e21cb901b5093701842e4                         |                                                              |
| newCoo            | VARCHAR   | 0x1607667f13da3d4960984a1e670b11755b46f49d                         |                                                              |

## 38. Table: WizardGuild\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-27 18:04:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13309334                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b43703a9fc0dd28701407f3dfb1469490352f8faa66f4939d5c8a9c090f0e24 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35b7838dd7507ada69610397a85310ae0abd5034                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x220c30ce36bbb22b57bd1c60e9ee4dcf44ca211d                         |                                                              |
| operator          | VARCHAR   | 0x6c869c06cfbaee230a48042570a975331402fbd4                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 39. Table: WizardGuild\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-12 02:02:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8917795                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ac50234d473cb8f828ebab3567bb998b5463e5ddb77b17aeb1cd934c1aeb6bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 357                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35b7838dd7507ada69610397a85310ae0abd5034                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x84ecb387395a1be65e133c75ff9e5fcc6f756db3                         |                                                              |
| approved          | VARCHAR   | 0x1337773c1797ba7bf2e76530cd43544fb47379db                         |                                                              |
| tokenId           | VARCHAR   | 3420                                                               |                                                              |

## 40. Table: WizardGuild\_event\_CEOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-11 23:38:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8723367                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9e2489c58ef93f3feee5bd3000b3a8e7396dd17618911390607b8c40eb3cd2b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 59                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35b7838dd7507ada69610397a85310ae0abd5034                         | Address of the contract that produced the log                |
| previousCeo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCeo            | VARCHAR   | 0x9fe2712d5bdcc4a7653352a595e2938ca94acde6                         |                                                              |

## 41. Table: WizardGuild\_event\_COOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-11 23:38:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8723367                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9e2489c58ef93f3feee5bd3000b3a8e7396dd17618911390607b8c40eb3cd2b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35b7838dd7507ada69610397a85310ae0abd5034                         | Address of the contract that produced the log                |
| previousCoo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCoo            | VARCHAR   | 0xd880d895ce716afc1e5e21cb901b5093701842e4                         |                                                              |

## 42. Table: WizardGuild\_event\_SeriesOpen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-12 00:07:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8723482                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x36a8c1c2d1dbf58b90c186bdda05bab23fa6854982de6e1176b0959dc4208f7c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35b7838dd7507ada69610397a85310ae0abd5034                         | Address of the contract that produced the log                |
| seriesIndex       | VARCHAR   | 0                                                                  |                                                              |
| reservedIds       | VARCHAR   | 5974                                                               |                                                              |

## 43. Table: WizardGuild\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-28 19:22:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9017091                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf94728e0327d331530a13e4e327a134f81934db238a282ae730b1ed5905a4358 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 33                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35b7838dd7507ada69610397a85310ae0abd5034                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x25aa18962135bfa28668af1397188fe3dd10353a                         |                                                              |
| to                | VARCHAR   | 0x85c7942567a64f442a710d6259806db4ae29f3b6                         |                                                              |
| tokenId           | VARCHAR   | 5104                                                               |                                                              |

## 44. Table: WizardGuild\_event\_WizardConjured\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 13:56:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8758918                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20aa9d4de3a4d1340c01040486e6607863891ec822780cb72a4b3ef7c4145df6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 103                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x35b7838dd7507ada69610397a85310ae0abd5034                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 6131                                                               |                                                              |
| affinity          | VARCHAR   | 1                                                                  |                                                              |
| innatePower       | VARCHAR   | 70000000000000                                                     |                                                              |

## 45. Table: WizardGuild\_v1\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-02 06:32:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16095352                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xea1d1205a09eae2b5bd96c1f980d020084bc99a58cfa0b0c407a9f19592ba7a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 141                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d8c864da1985525e0af0acbeef6562881827bd5                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x8211cb2f07cfce6328ba327595f8dc35c8f899b8                         |                                                              |
| operator          | VARCHAR   | 0x7bc8b1b5aba4df3be9f9a32dae501214dc0e4f3f                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 46. Table: WizardGuild\_v1\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-11-17 06:14:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8948889                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ca7283870d8460a55dacb8e89a1acd35f791f46b3ec7c234826d4bf37a5c03b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d8c864da1985525e0af0acbeef6562881827bd5                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x33ec2fed3e429a515ccdf361554f102ea36e0ceb                         |                                                              |
| approved          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| tokenId           | VARCHAR   | 295                                                                |                                                              |

## 47. Table: WizardGuild\_v1\_event\_CEOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 22:47:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8761265                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22b095e3d88d6bc98731ef9ec92a03a995b53aaf523d7cb61cdfaa383f857d81 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 51                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d8c864da1985525e0af0acbeef6562881827bd5                         | Address of the contract that produced the log                |
| previousCeo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCeo            | VARCHAR   | 0x9fe2712d5bdcc4a7653352a595e2938ca94acde6                         |                                                              |

## 48. Table: WizardGuild\_v1\_event\_COOTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 22:47:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8761265                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22b095e3d88d6bc98731ef9ec92a03a995b53aaf523d7cb61cdfaa383f857d81 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 52                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d8c864da1985525e0af0acbeef6562881827bd5                         | Address of the contract that produced the log                |
| previousCoo       | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newCoo            | VARCHAR   | 0xd880d895ce716afc1e5e21cb901b5093701842e4                         |                                                              |

## 49. Table: WizardGuild\_v1\_event\_SeriesOpen\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-17 23:09:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8761363                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5418d1707d971a913bd9ca025381598b3306f1be15218398d803ace7d8d2f20c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d8c864da1985525e0af0acbeef6562881827bd5                         | Address of the contract that produced the log                |
| seriesIndex       | VARCHAR   | 0                                                                  |                                                              |
| reservedIds       | VARCHAR   | 6133                                                               |                                                              |

## 50. Table: WizardGuild\_v1\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-01 08:01:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13719909                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7fc575f7c8a01249c9bcbf51b0d8994e3d1715bf95897bae09960fc0c06c2fa3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 86                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d8c864da1985525e0af0acbeef6562881827bd5                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xd6e2b9696dc45642ebb84bb789ed68d2354d774d                         |                                                              |
| to                | VARCHAR   | 0xfcee120094854fbfdc98ce8a80b8057bdeb928a7                         |                                                              |
| tokenId           | VARCHAR   | 6007                                                               |                                                              |

## 51. Table: WizardGuild\_v1\_event\_WizardConjured\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-22 06:39:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8788740                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3f4584155c4590efb5a617158ab24a31d80641c199cc489914060cbb3a54c57 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 60                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d8c864da1985525e0af0acbeef6562881827bd5                         | Address of the contract that produced the log                |
| wizardId          | VARCHAR   | 6195                                                               |                                                              |
| affinity          | VARCHAR   | 1                                                                  |                                                              |
| innatePower       | VARCHAR   | 70000000000000                                                     |                                                              |

## 52. Table: WizardPresale\_event\_ApprovalForAll\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-01 12:10:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8065555                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe6833592768b9679458618764c9d227b665058c713a3bf5fc9e5e86cae8d72ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2f4bdafb22bd92aa7b7552d270376de8edccbc1e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x41308f0538d32dae052e3524c82f47eae2e560f1                         |                                                              |
| operator          | VARCHAR   | 0xf0f8e38b1ffcabc94ebf6e4a70e7c1ca10b1737f                         |                                                              |
| approved          | VARCHAR   | true                                                               |                                                              |

## 53. Table: WizardPresale\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-18 03:41:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7781798                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ed8391fa5638f6bf5eace016e4df538176314b28fc5531be572c57a62678b77 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2f4bdafb22bd92aa7b7552d270376de8edccbc1e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc247b44a4cdee03433a79ca3f6864bdc9b138165                         |                                                              |
| approved          | VARCHAR   | 0x252a80a19686ce94b70dd4e0d3e6ae7a2b4cc06c                         |                                                              |
| tokenId           | VARCHAR   | 2311                                                               |                                                              |

## 54. Table: WizardPresale\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-07-26 18:38:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8227856                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9b6284982df7135b4b7dee57fbbf17375249930c14631a6dc8aa85456cd75fce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2f4bdafb22bd92aa7b7552d270376de8edccbc1e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xf499c157a2c7eecb14216260c61561e832d1a260                         |                                                              |
| to                | VARCHAR   | 0x74175e628c9c99fcb67332ffa3d411cae16260f5                         |                                                              |
| tokenId           | VARCHAR   | 3802                                                               |                                                              |

## 55. Table: WizardPresale\_event\_WizardSummoned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-24 16:11:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7823360                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa7f691a50fa0ed38301b31968b391efad3f83557db893fcb1e9399c30144b97 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 116                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2f4bdafb22bd92aa7b7552d270376de8edccbc1e                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 5307                                                               |                                                              |
| element           | VARCHAR   | 1                                                                  |                                                              |
| power             | VARCHAR   | 70000000000000                                                     |                                                              |
