# aura

## 1. Table: AuraBalInitialStaking\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-16 11:54:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14973167                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdd0fb73972418507d6742a239dd028614ca348de1ffb6cf96050845531c16354 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc47162863a12227e5c3b0860715f9cf721651c0c                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 2000000000000000000000000                                          |                                                              |

## 2. Table: AuraBalInitialStaking\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-01 01:25:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15053619                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd7e2f550881521ace56659b2da0ca98f965bb2bc185378814dbc6fe5321799fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 274                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc47162863a12227e5c3b0860715f9cf721651c0c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xf0cf2338ea5a498bc6c30976fc39660d23509468                         |                                                              |
| reward            | VARCHAR   | 117372540102027759546                                              |                                                              |
| locked            | VARCHAR   | true                                                               |                                                              |

## 3. Table: AuraBalInitialStaking\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-28 20:40:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15041520                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x278bba99ff628e291b8c7178cb388483b4b5b1073bdd0373cbc3e1fb42319f74 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc47162863a12227e5c3b0860715f9cf721651c0c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x42fd445e08c89e264695e3687d3fd3547c75d6b2                         |                                                              |
| amount            | VARCHAR   | 201455626289267735843                                              |                                                              |

## 4. Table: AuraBalInitialStaking\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-17 09:08:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15159285                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x920aace0843d835639ace9316fdf86c9d03d7f8357f59d33b0d45437a5d8ec6d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 393                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc47162863a12227e5c3b0860715f9cf721651c0c                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xfd9994cf969749540a0076448b1c0f72b58af1c2                         |                                                              |
| amount            | VARCHAR   | 394387736951093130228                                              |                                                              |

## 5. Table: AuraLocker\_event\_BlacklistModified\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |
| blacklisted       | VARCHAR   |                                                              |             |

## 6. Table: AuraLocker\_event\_DelegateChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 00:26:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17567143                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2392524c8649ec0bce56ff4cee32f7699fa13b05c485829969a1dc63afdc6990 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fa73f1e5d8a792c80f426fc8f84fbf7ce9bbcac                         | Address of the contract that produced the log                |
| delegator         | VARCHAR   | 0xc7755a379a5b56dfab57b9cad804428effabc817                         |                                                              |
| fromDelegate      | VARCHAR   | 0x45f2015f4d52e1a126565ad8ede9fe7ec9414165                         |                                                              |
| toDelegate        | VARCHAR   | 0x3cde8fa1c73afe0828f672d197e082463c2ac8e2                         |                                                              |

## 7. Table: AuraLocker\_event\_DelegateCheckpointed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 21:28:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17830002                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x589dec9086222a00c6386e25c8ba32f03dc7f2b758bd2c0d3ded7a19a923140a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 235                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fa73f1e5d8a792c80f426fc8f84fbf7ce9bbcac                         | Address of the contract that produced the log                |
| delegate          | VARCHAR   | 0x0d9a5678e73e5bbc0ee09faf8e550b196c76fdad                         |                                                              |

## 8. Table: AuraLocker\_event\_KickIncentiveSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| rate              | VARCHAR   |                                                              |             |
| delay             | VARCHAR   |                                                              |             |

## 9. Table: AuraLocker\_event\_KickReward\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 23:40:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17382167                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x822b804a6ce8ecd42c640f3026173569e6989a23529fcaa0e95a4bd1a5bd6df7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fa73f1e5d8a792c80f426fc8f84fbf7ce9bbcac                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x5809083c15165bb5995111bfad33837c4f43fcb4                         |                                                              |
| \_kicked          | VARCHAR   | 0x3eedb85da27cac4ec83ab5a8a38f18b0edbc7042                         |                                                              |
| \_reward          | VARCHAR   | 9991625854343562010                                                |                                                              |

## 10. Table: AuraLocker\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 10:58:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932220                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf1ee91a229614832c6564328022200046451d0f2d22b1cf00eb3a2b51688338 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 834                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fa73f1e5d8a792c80f426fc8f84fbf7ce9bbcac                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xa28ea848801da877e1844f954ff388e857d405e5                         |                                                              |

## 11. Table: AuraLocker\_event\_Recovered\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_token           | VARCHAR   |                                                              |             |
| \_amount          | VARCHAR   |                                                              |             |

## 12. Table: AuraLocker\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-30 00:41:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17588593                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0ca5e6ec6a8b5a8434d5cb6e1984e90867e975714a5ad165f48252f0ea96bf2d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fa73f1e5d8a792c80f426fc8f84fbf7ce9bbcac                         | Address of the contract that produced the log                |
| \_token           | VARCHAR   | 0x616e8bfa43f920657b3497dbf40d6b1a02d4608d                         |                                                              |
| \_reward          | VARCHAR   | 1298681690702656341559                                             |                                                              |

## 13. Table: AuraLocker\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-11 07:26:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16382065                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7630088ffb82b62b87bad4ebdc15f8bfd00c2b948b088a1cb9ba48296532bb4a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 217                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fa73f1e5d8a792c80f426fc8f84fbf7ce9bbcac                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0xd14f076044414c255d2e82cceb1cb00fb1bba64c                         |                                                              |
| \_rewardsToken    | VARCHAR   | 0x616e8bfa43f920657b3497dbf40d6b1a02d4608d                         |                                                              |
| \_reward          | VARCHAR   | 53952586153853934918                                               |                                                              |

## 14. Table: AuraLocker\_event\_Shutdown\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 15. Table: AuraLocker\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-04 21:46:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16978255                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe4584f3f055872047de7ebb56a626506ef6b97f9f763fb9cf6ee894567a0de25 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 190                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fa73f1e5d8a792c80f426fc8f84fbf7ce9bbcac                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x012f11883b03d2c6c56706cae752343396bdd72b                         |                                                              |
| \_paidAmount      | VARCHAR   | 237196894572817179124                                              |                                                              |
| \_lockedAmount    | VARCHAR   | 237196894572817179124                                              |                                                              |

## 16. Table: AuraLocker\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-16 06:57:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16639651                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdf9e4153eb4291097e73456c605b422ab276e5c18fab700461d0302be6fd86f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 628                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3fa73f1e5d8a792c80f426fc8f84fbf7ce9bbcac                         | Address of the contract that produced the log                |
| \_user            | VARCHAR   | 0x922339aacfa3eb3e7d9f990f8aa25f8518902bba                         |                                                              |
| \_amount          | VARCHAR   | 7578733624485331425503                                             |                                                              |
| \_relocked        | VARCHAR   | true                                                               |                                                              |

## 17. Table: BaseRewardPoolV2\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-16 11:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17705440                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6998b7805ab4788846d4d350a5e66be56df48cfdaa8a16d4322f0707778683c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 359                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00a7ba8ae7bca0b10a32ea1f8e2a1da980c6cad2                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 17841876448720690712005                                            |                                                              |

## 18. Table: BaseRewardPoolV2\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 17:21:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17543723                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7af3eb20007bd98c50c28ed3f020de21eedb9eb53d7f15634525870fb27ddf51 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 160                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00a7ba8ae7bca0b10a32ea1f8e2a1da980c6cad2                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x26f539a0fe189a7f228d7982bf10bc294fa9070c                         |                                                              |
| reward            | VARCHAR   | 76195205289738795417                                               |                                                              |

## 19. Table: BaseRewardPoolV2\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-30 17:24:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17373203                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x285a38202eba4e491784b9955497209dd4e4968f70dc888c40bf277703fa9bdc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 420                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00a7ba8ae7bca0b10a32ea1f8e2a1da980c6cad2                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x4b0987bef3f966354c6ecd22f6d844d621ee5077                         |                                                              |
| amount            | VARCHAR   | 359789109489602230276                                              |                                                              |

## 20. Table: BaseRewardPoolV2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 01:15:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17738184                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3860cff75fef54413e4f8163879c8ad4ef020d61fdcc99d6a405f68a4b30a405 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 212                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00a7ba8ae7bca0b10a32ea1f8e2a1da980c6cad2                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x7372ece4c18beabc19981a53b557be90dcbd2b66                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 3754797308500994255313                                             |                                                              |

## 21. Table: BaseRewardPoolV2\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-04 05:56:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17405314                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x693274e65bf9dbac307d54ea9fb8dad62fef1090bc56666c0183848c1dea0de0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 143                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00a7ba8ae7bca0b10a32ea1f8e2a1da980c6cad2                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x064a4887f6a19093517bfbf67f216d187378e111                         |                                                              |
| amount            | VARCHAR   | 29463289106740563832                                               |                                                              |

## 22. Table: BoosterV2\_event\_Deposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-23 06:08:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16888372                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x36004cf0bb29549ba07b8095edd940a480097e45725f6e9b8fba3b5b47cd3233 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 176                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa57b8d98dae62b26ec3bcc4a365338157060b234                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x21b7641470b6d78a24310ffd785bbff7361c6b28                         |                                                              |
| poolid            | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 577744563067508029282                                              |                                                              |

## 23. Table: BoosterV2\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-15 09:12:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17264213                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x91b954f7f4b5fe96f37f9bfcc520e6908142ee96d220a545ab9c6fb64c7793f9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa57b8d98dae62b26ec3bcc4a365338157060b234                         | Address of the contract that produced the log                |
| lpToken           | VARCHAR   | 0x793f2d5cd52dfafe7a1a1b0b3988940ba2d6a63d                         |                                                              |
| gauge             | VARCHAR   | 0x8a88c1f44854c61a466ab55614f6a7778473418b                         |                                                              |
| token             | VARCHAR   | 0x602d9aed23dadba4cba7acc9474badb4ec9a9a4b                         |                                                              |
| rewardPool        | VARCHAR   | 0x61672a679e0065f35892e2b428736be8c5c3a159                         |                                                              |
| stash             | VARCHAR   | 0x2581baf9b4e280624f8dd486e11c646ceb7bd844                         |                                                              |
| pid               | VARCHAR   | 96                                                                 |                                                              |

## 24. Table: BoosterV2\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 19:57:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16349977                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5ee8d172e0f129e67c4ce874ec520a7ed0ed2a16ac440bd013e2f71c35add524 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 267                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa57b8d98dae62b26ec3bcc4a365338157060b234                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x8feeaa5f3bcc9700fb8d44fc1ba018a958f67bfe                         |                                                              |
| poolid            | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 36182593581588445262                                               |                                                              |

## 25. Table: Booster\_event\_Deposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-02 00:35:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15456057                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0425621512202b9329615af75586ef6188c62f3cbfb41e0244c06e3c6eb19cba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1255                                                               | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x9c9cebfe89ac87a5195f75a6a6964f7ba140e7b5                         |                                                              |
| poolid            | VARCHAR   | 3                                                                  |                                                              |
| amount            | VARCHAR   | 3586643561764668568                                                |                                                              |

## 26. Table: Booster\_event\_FactoriesUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 11:23:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932314                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x526e9f1d8b8e3c38e5b651d64dfe4ca6bb5e7c40981705302dd87b2828813fac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 113                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| rewardFactory     | VARCHAR   | 0x45aad11f2fa2c215bc9686eb6f06d46e0474f356                         |                                                              |
| stashFactory      | VARCHAR   | 0x95171c9ef5ca540a6d3502e9547fcfe022458eb5                         |                                                              |
| tokenFactory      | VARCHAR   | 0xb6ce51dee8bd4a2fd11c01205414dc26f0b453ac                         |                                                              |

## 27. Table: Booster\_event\_FeeInfoChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-04 14:56:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15675503                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51e5d823c9bc60a63f10a1f569a697977266be783f390094927a5f60ddbd1b22 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| feeDistro         | VARCHAR   | 0x7b50775383d3d6f0215a8f290f2c9e2eebbeceb2                         |                                                              |
| active            | VARCHAR   | false                                                              |                                                              |

## 28. Table: Booster\_event\_FeeInfoUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-23 15:16:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15013564                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3b007c625897e88da82748fc166a0843731c77347a8ce732e1d00ff5131c288a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| feeDistro         | VARCHAR   | 0x26743984e3357efc59f2fd6c1afdc310335a61c9                         |                                                              |
| lockFees          | VARCHAR   | 0x5e5ea2048475854a5702f5b8468a51ba1296efcc                         |                                                              |
| feeToken          | VARCHAR   | 0xba100000625a3754423978a60c9317c58a424e3d                         |                                                              |

## 29. Table: Booster\_event\_FeeManagerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 11:26:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932331                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf55fabf0b85b1b091642e86437a9e9cd93af9beb22930ff6178f743d0f23700b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 24                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| newFeeManager     | VARCHAR   | 0x5fea4413e3cc5cf3a29a49db41ac0c24850417a0                         |                                                              |

## 30. Table: Booster\_event\_FeesUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-01 07:58:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15451696                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2205a4a55cfc5e0e0bb49c78ec2fd28317f91e5b3e0bf52f5525731b2f95020c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 170                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| lockIncentive     | VARCHAR   | 1500                                                               |                                                              |
| stakerIncentive   | VARCHAR   | 950                                                                |                                                              |
| earmarkIncentive  | VARCHAR   | 50                                                                 |                                                              |
| platformFee       | VARCHAR   | 0                                                                  |                                                              |

## 31. Table: Booster\_event\_PoolAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-21 13:55:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15582183                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x10ec5b6dc8b0a0975ca11188552b35f3aae85df48a6237d63b6da1b2e3224e72 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 330                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| lpToken           | VARCHAR   | 0x0fd5663d4893ae0d579d580584806aadd2dd0b8b                         |                                                              |
| gauge             | VARCHAR   | 0x6eb7cdcd15417abf120ffe404b9b88141ca952b7                         |                                                              |
| token             | VARCHAR   | 0x77bf0442454397146d59b164502925dbe694797a                         |                                                              |
| rewardPool        | VARCHAR   | 0xd84ebc73e484ba614ed201e333416b18b48d9727                         |                                                              |
| stash             | VARCHAR   | 0x47862a1d469837c83ae446543b1ecdae425d68af                         |                                                              |
| pid               | VARCHAR   | 36                                                                 |                                                              |

## 32. Table: Booster\_event\_PoolManagerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 11:19:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932297                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0491994a587bbf0f7a54575aef0f68aa1cf3cb44ce2b9e057815231566d8cb84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| newPoolManager    | VARCHAR   | 0x16a04e58a77ab1ce561a37371dfb479a8594947a                         |                                                              |

## 33. Table: Booster\_event\_RewardContractsUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 11:19:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14932294                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2e2aadc124a68c698fbb802e45a1251fcf848cc5874a642d194ed8390ff15360 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 56                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| lockRewards       | VARCHAR   | 0x5e5ea2048475854a5702f5b8468a51ba1296efcc                         |                                                              |
| stakerRewards     | VARCHAR   | 0xd9e863b7317a66fe0a4d2834910f604fd6f89c6c                         |                                                              |

## 34. Table: Booster\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 04:16:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16345301                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb1053e51fe095d3949c3c4b42e2fbbf6996a3cf5ce6d316735fe9ca951affc3f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7818a1da7bd1e64c199029e86ba244a9798eee10                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x12adde99768a82871eaaecfbdb065b12c56f0578                         |                                                              |
| poolid            | VARCHAR   | 21                                                                 |                                                              |
| amount            | VARCHAR   | 7198704718116771127                                                |                                                              |

## 35. Table: PoolMigrator\_call\_migrate\_history

| Column             | Type      | Example                                                                        | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-18 05:25:35+00:00                                                      | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16852550                                                                       | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x15a93e7c30a9b82c4692309aac8663fcf0b8944543676ad09c1c0dc136360e96             | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 92                                                                             | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                           | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x12adde99768a82871eaaecfbdb065b12c56f0578                                     | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                              | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                           | Error in case input parsing failed                                                                                     |
| \_fromPids         | VARCHAR   | 20                                                                             |                                                                                                                        |
| \_toPids           | VARCHAR   | 0                                                                              |                                                                                                                        |
| \_amounts          | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                                                                                        |

## 36. Table: RewardPoolV1\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-18 03:49:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15557864                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x35ca9187be41140100328aeb1ed1d1d6561b051449892101d60ef716f076a9dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 683                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08b8a86b9498ac249bf4b86e14c5d4187085a239                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xb188b1cb84fb0ba13cb9ee1292769f903a9fec59                         |                                                              |
| owner             | VARCHAR   | 0xa2815c834e7aa4ac010aec8b213b71e1f84de3e8                         |                                                              |
| assets            | VARCHAR   | 131768130471164544608                                              |                                                              |
| shares            | VARCHAR   | 131768130471164544608                                              |                                                              |

## 37. Table: RewardPoolV1\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-10 17:44:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15116315                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc22db5d9250e021acd01ac1044b34079c236fe354282664f945b1a22bdc95921 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 311                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc531a6135142b1532433e334e215eb2f32b069c1                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 2785311954983891868768                                             |                                                              |

## 38. Table: RewardPoolV1\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-30 16:52:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16941369                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xffed34f8fdbfecaca7762d42c02cdc12a85ccf39b165f3c59357f8712cb3976b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 173                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcc2f52b57247f2bc58fec182b9a60dac5963d010                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xd34427950f74a15bd18d1be4cb3dd5dd65f9eb1f                         |                                                              |
| reward            | VARCHAR   | 474816615948937190564                                              |                                                              |

## 39. Table: RewardPoolV1\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-07 23:36:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15493186                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x56ded0b0e01f99b7dc61b933d605e5bedaea3d51e231be7eea86c0bfca973d27 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 112                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x10ca519614b0f3463890387c24819001affc5152                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xc07c56e8df0ec6e82d38f708037df9c8700891bd                         |                                                              |
| amount            | VARCHAR   | 2146427359474945840                                                |                                                              |

## 40. Table: RewardPoolV1\_event\_Transfer\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| value             | VARCHAR   |                                                              |             |

## 41. Table: RewardPoolV1\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-21 01:53:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16229915                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8390a6a392239ad5a0d8a490fd2f7cef4b09a0c5530e8a6f6dc8402bd4738668 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 144                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x05df1e87f41f793d9e03d341cdc315b76595654c                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x12adde99768a82871eaaecfbdb065b12c56f0578                         |                                                              |
| receiver          | VARCHAR   | 0x12adde99768a82871eaaecfbdb065b12c56f0578                         |                                                              |
| owner             | VARCHAR   | 0x4cccf16faf12590dc9a93255224e699fa2197bca                         |                                                              |
| assets            | VARCHAR   | 791639487162863819350                                              |                                                              |
| shares            | VARCHAR   | 791639487162863819350                                              |                                                              |

## 42. Table: RewardPoolV1\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-07 04:38:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16352569                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x167198ed94f0a8178b97e31e2f1625760f728b7975142244456282cf24beeea2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd84ebc73e484ba614ed201e333416b18b48d9727                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x9cab29b34d1606e869535fea17a6be56eb4e8006                         |                                                              |
| amount            | VARCHAR   | 148898616643424585852                                              |                                                              |

## 43. Table: RewardPoolV2\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-26 15:39:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17564544                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5166370a75a85def0f22aeae20fbfc441bd0ba041e640c07635f9b71098bfab0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd26948e7a0223700e3c3cdea21ca2471abcb8d47                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x9e6121e89dd50b5d02362a9fdb7ec1fad3d15725                         |                                                              |
| owner             | VARCHAR   | 0x9e6121e89dd50b5d02362a9fdb7ec1fad3d15725                         |                                                              |
| assets            | VARCHAR   | 93292849345160748                                                  |                                                              |
| shares            | VARCHAR   | 93292849345160748                                                  |                                                              |

## 44. Table: RewardPoolV2\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-18 20:59:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17509190                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x16f7bd8379ce2f54b5c1785cf6a181b9c1c375868fb61de04370016de591004a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 262                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe39570ef26fb9a562bf26f8c708b7433f65050af                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 293855529000903461857                                              |                                                              |

## 45. Table: RewardPoolV2\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-08 14:16:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17649575                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbe55c59a58f682e76d1d9e47370abdf41dae65893e23437b5856aebb3502bd1b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 361                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe4683fe8f53da14ca5dac4251eadfb3aa614d528                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x0b28c1c956b72a5a4475a9aae13d90084e7291ca                         |                                                              |
| reward            | VARCHAR   | 374984431827473715832                                              |                                                              |

## 46. Table: RewardPoolV2\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 00:05:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17028268                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xedba39c0feec5969cb52ef0138e9b70b657fbd2d4eeece2da69e5d01ea75f47e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 278                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001b78cec62dcfdc660e06a91eb1bc966541d758                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x79fd406d5bf0faf56d2721e679f3d68b975414d6                         |                                                              |
| amount            | VARCHAR   | 3899389391379166354                                                |                                                              |

## 47. Table: RewardPoolV2\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 08:15:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17242882                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0befdc155e681d545e06545bde059e5f88ce528462ea40fa5f317575867b368b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001b78cec62dcfdc660e06a91eb1bc966541d758                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xc0dd85720e3bc7959890127b5d3af2d29f6c74f4                         |                                                              |
| value             | VARCHAR   | 21416233671912739584                                               |                                                              |

## 48. Table: RewardPoolV2\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-20 03:31:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17518250                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x021a5572f4348034f7fab88bdf2ce5fb5891e3112b49cd46e7dbf10bb3b2be0f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 159                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x228054e9c056f024fc724f515a2a8764ae175ed6                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0xcd36ed329d338c88775d6f499e99265989deba53                         |                                                              |
| receiver          | VARCHAR   | 0xcd36ed329d338c88775d6f499e99265989deba53                         |                                                              |
| owner             | VARCHAR   | 0x3c5aac016ef2f178e8699d6208796a2d67557fe2                         |                                                              |
| assets            | VARCHAR   | 330776847619231859638                                              |                                                              |
| shares            | VARCHAR   | 330776847619231859638                                              |                                                              |

## 49. Table: RewardPoolV2\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 13:21:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17849033                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb9cf723f34e7a398213a6c0d2bd760fe4c35a26015d95208cd5fb0202ee548c8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdd1fe5ad401d4777ce89959b7fa587e569bf125d                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x04f1977c6849a0f31e152715ecf77871e2f83612                         |                                                              |
| amount            | VARCHAR   | 356276592447264254373                                              |                                                              |

## 50. Table: auraBALDepositorWrapper\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-25 14:02:23+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17770577                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x184de47a17215baf234fa1315459b37b23052e123f507fedc5d1efef2635eafa | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 176                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 8                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x68655ad9852a99c87c0934c7290bb62cfa5d4123                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 116738573618384530867                                              |                                                                                                                        |
| \_minOut           | VARCHAR   | 41099118985623607387                                               |                                                                                                                        |
| \_lock             | VARCHAR   | false                                                              |                                                                                                                        |
| \_stakeAddress     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                                                                                        |

## 51. Table: auraBALDepositorWrapper\_call\_depositor\_history

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

## 52. Table: auraBALDepositor\_call\_depositAll\_history

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
| \_lock             | VARCHAR   |                                                                                                                        |             |
| \_stakeAddress     | VARCHAR   |                                                                                                                        |             |

## 53. Table: auraBALDepositor\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-06-09 11:45:47+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14932405                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2f190353704228ee638188dbcf8d5ddef325c95fbb4166c71a2358cf08262af3 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 38                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xead792b55340aa20181a80d6a16db6a0ecd1b827                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_amount           | VARCHAR   | 115559823758891957564                                              |                                                                                                                        |
| \_lock             | VARCHAR   | true                                                               |                                                                                                                        |

## 54. Table: auraBALRewardPool\_event\_RewardAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-06 02:18:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15686030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc9ebf872bc093cf1d0427badb1f32896c2a0f9dbccbbd198223dcf893ca33bdc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 532                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5e5ea2048475854a5702f5b8468a51ba1296efcc                         | Address of the contract that produced the log                |
| reward            | VARCHAR   | 18033180599768500024004                                            |                                                              |

## 55. Table: auraBALRewardPool\_event\_RewardPaid\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-22 00:49:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17531706                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x68bafe0ef9e2438c23136755f1c65a69549784319f0efd9bfbacfe8f8d9dc06a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 167                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5e5ea2048475854a5702f5b8468a51ba1296efcc                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xca03836463e356f80b81e3e3134b8cee56469645                         |                                                              |
| reward            | VARCHAR   | 1427342668723285811                                                |                                                              |

## 56. Table: auraBALRewardPool\_event\_Staked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-21 02:52:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15381440                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x74230685613b4e97c2e0708ae4f0e3a409cf35d054cc7bc9384f5253d639fbed | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 220                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5e5ea2048475854a5702f5b8468a51ba1296efcc                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x09fa38eba245bb68354b8950fa2fe71f02863393                         |                                                              |
| amount            | VARCHAR   | 4944695109905883899                                                |                                                              |

## 57. Table: auraBALRewardPool\_event\_Withdrawn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-30 11:44:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15050186                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x22ccdfb146e02babfc2d8a85e28a3709c63efb0fd6499fb08a8684d792b241ee | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 55                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5e5ea2048475854a5702f5b8468a51ba1296efcc                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x36cc7b13029b5dee4034745fb4f24034f3f2ffc6                         |                                                              |
| amount            | VARCHAR   | 10000000000000000000000                                            |                                                              |
