# gro

## 1. Table: LPTokenStaker\_event\_LogAddPool\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-30 14:14:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13327543                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2f3920d9b8080db5c108488bf0c6436644e1b7d68c1abd180fb79ba1847effd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 122                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| pid               | VARCHAR   | 3                                                                  |                                                              |
| allocPoint        | VARCHAR   | 100                                                                |                                                              |
| lpToken           | VARCHAR   | 0x3adb04e127b9c0a5d36094125669d4603ac52a0c                         |                                                              |

## 2. Table: LPTokenStaker\_event\_LogClaim\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-01 20:15:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13533241                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8b88a81a7dc57f0d4727795520645ae515414c9d09611be8072df4f8ea06550c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x5b4672cffee5e64a2a7d17c157abdb4edffbe3df                         |                                                              |
| pid               | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 77338789921603351138                                               |                                                              |

## 3. Table: LPTokenStaker\_event\_LogDeposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-31 13:05:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13524952                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfa874b5e02c816b2236424e1adbdd590a23ad362aa0a79dfa09bd13da19e685c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 164                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x3b3962aa97861138c24244eb2f794d86f1be6255                         |                                                              |
| pid               | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 500000000000000000000                                              |                                                              |

## 4. Table: LPTokenStaker\_event\_LogEmergencyWithdraw\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |
| pid               | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 5. Table: LPTokenStaker\_event\_LogGroPerBlock\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-17 17:44:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14024467                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9890a71021364a9ae28a7b60fa72409c7d92fe28c6d7c2dc0bccff1d857c8652 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 67                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| newGro            | VARCHAR   | 3500000000000000000                                                |                                                              |

## 6. Table: LPTokenStaker\_event\_LogLpTokenAdded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-30 14:14:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13327543                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb2f3920d9b8080db5c108488bf0c6436644e1b7d68c1abd180fb79ba1847effd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 121                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x3adb04e127b9c0a5d36094125669d4603ac52a0c                         |                                                              |

## 7. Table: LPTokenStaker\_event\_LogMaxGroPerBlock\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-01 16:27:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13334554                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x60995a096de42a626796cdeb4bc686f8417c39fcdf09ba06f4e8af3955156906 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 225                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| newMax            | VARCHAR   | 20000000000000000000                                               |                                                              |

## 8. Table: LPTokenStaker\_event\_LogNewManagment\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-30 11:18:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13326779                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x12863f6d1b50de30281e7307539533f4f4c8baa7960c4d21da88e799e104aab8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 81                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| newManager        | VARCHAR   | 0x3c1f2e6ec3de7811e2daa2b8e132cdcd8e39851c                         |                                                              |

## 9. Table: LPTokenStaker\_event\_LogNewMigrator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-24 12:00:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14268673                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa83b2b60c56de143c3a8ffad8d143bcb595faa91b292d392e65d43bb4f1972bd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 98                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| newMigrator       | VARCHAR   | 0xc8f64799c1cdf2c40161b98df86e36ee6a8f1275                         |                                                              |

## 10. Table: LPTokenStaker\_event\_LogNewVester\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-13 13:08:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13410162                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe58b111dfeffe5aa6948a04a7e0dc03baa328452350cb9403919e1a98628b2a1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| newVester         | VARCHAR   | 0xa28693bf01dc261887b238646bb9636cb3a3730b                         |                                                              |

## 11. Table: LPTokenStaker\_event\_LogSetPool\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-01 15:21:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13531932                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe7e95078bde50f64d9f40bc2b56d96a46859eacc67d75f684bbd2af723fa8729 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 411                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| pid               | VARCHAR   | 5                                                                  |                                                              |
| allocPoint        | VARCHAR   | 110                                                                |                                                              |

## 12. Table: LPTokenStaker\_event\_LogUpdatePool\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-15 21:55:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14012636                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x237a2b1481bb4b31618602b85083e648572789c9553d26f0a338630cbd2cd19d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 211                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| pid               | VARCHAR   | 2                                                                  |                                                              |
| lastRewardBlock   | VARCHAR   | 14012636                                                           |                                                              |
| lpSupply          | VARCHAR   | 669827062593299567                                                 |                                                              |
| accGroPerShare    | VARCHAR   | 888521963725556164                                                 |                                                              |

## 13. Table: LPTokenStaker\_event\_LogWithdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-05 19:24:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13360911                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x532cc41f2d5decd17855e505647f7411d3053c54e66480840ee56f3e9e0d441c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 596                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x15ac0a1c970f2414679586c7111d2b56bab22aa5                         |                                                              |
| pid               | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 8330984805810057127366                                             |                                                              |

## 14. Table: LPTokenStaker\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-30 10:11:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13326459                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6aa88299d491c09d3168719bd8434c9ec76baa841edfbb8d1ca8b952dc3c4cca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x001c249c09090d79dc350a286247479f08c7aad7                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xba5edf9dad66d9d81341eef8131160c439dba91b                         |                                                              |
