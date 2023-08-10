# kleros

## 1. Table: KlerosLiquid\_event\_AppealDecision\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-11 13:23:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16605792                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xaeb601813a7363f42f3957500bd40e65e89741c2c6507c9ab67178284bcd78c7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 236                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x988b3a538b618c7a603e1c11ab82cd16dbe28069                         | Address of the contract that produced the log                |
| \_disputeID       | VARCHAR   | 1504                                                               |                                                              |
| \_arbitrable      | VARCHAR   | 0xc5e9ddebb09cd64dfacab4011a0d5cedaf7c9bdb                         |                                                              |

## 2. Table: KlerosLiquid\_event\_AppealPossible\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-01 11:01:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16311485                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2dcf90d4a1d08b24f3458ee2a5e4fe0f92cd6490d4dbf85204f92916bb6f99b6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 152                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x988b3a538b618c7a603e1c11ab82cd16dbe28069                         | Address of the contract that produced the log                |
| \_disputeID       | VARCHAR   | 1443                                                               |                                                              |
| \_arbitrable      | VARCHAR   | 0xc5e9ddebb09cd64dfacab4011a0d5cedaf7c9bdb                         |                                                              |

## 3. Table: KlerosLiquid\_event\_DisputeCreation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-12 19:22:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8728555                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb092eca031a696ac2bc4aef6301cf5ab5e9cf3e8e45fc636f224674a9590c1e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x988b3a538b618c7a603e1c11ab82cd16dbe28069                         | Address of the contract that produced the log                |
| \_disputeID       | VARCHAR   | 114                                                                |                                                              |
| \_arbitrable      | VARCHAR   | 0xebcf3bca271b26ae4b162ba560e243055af0e679                         |                                                              |

## 4. Table: KlerosLiquid\_event\_Draw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-03-13 01:27:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7357775                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1445246fff4afbef522150ff969ce979a0c10e3b5863a660a3b9572d2ad64323 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x988b3a538b618c7a603e1c11ab82cd16dbe28069                         | Address of the contract that produced the log                |
| \_address         | VARCHAR   | 0xfc898b18a70ce49579f8d79a32e29928c15b4bc8                         |                                                              |
| \_disputeID       | VARCHAR   | 11                                                                 |                                                              |
| \_appeal          | VARCHAR   | 0                                                                  |                                                              |
| \_voteID          | VARCHAR   | 0                                                                  |                                                              |

## 5. Table: KlerosLiquid\_event\_NewPeriod\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-27 13:29:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17570989                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x46f9930b030bb964016bd998495046c9fc83e420b8cb25420bb72da23d531333 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 242                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x988b3a538b618c7a603e1c11ab82cd16dbe28069                         | Address of the contract that produced the log                |
| \_disputeID       | VARCHAR   | 1581                                                               |                                                              |
| \_period          | VARCHAR   | 4                                                                  |                                                              |

## 6. Table: KlerosLiquid\_event\_NewPhase\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-05-10 14:47:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7733377                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5e41c31c40de3361b5d6727f92307b5a853582ccb70977cda29e4fea3d38b8f1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 114                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x988b3a538b618c7a603e1c11ab82cd16dbe28069                         | Address of the contract that produced the log                |
| \_phase           | VARCHAR   | 1                                                                  |                                                              |

## 7. Table: KlerosLiquid\_event\_StakeSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-06-02 01:37:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10183509                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae7c9a15a96bb78fbf5bb7664ba419967d6701f390dcce7e86790d42ae07f15c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x988b3a538b618c7a603e1c11ab82cd16dbe28069                         | Address of the contract that produced the log                |
| \_address         | VARCHAR   | 0x0053546e2034c25805eba84055cc6cff7fad1307                         |                                                              |
| \_subcourtID      | VARCHAR   | 0                                                                  |                                                              |
| \_stake           | VARCHAR   | 1000000000000000000000                                             |                                                              |
| \_newTotalStake   | VARCHAR   | 1000000000000000000000                                             |                                                              |

## 8. Table: KlerosLiquid\_event\_TokenAndETHShift\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-19 22:15:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7991325                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x32a3dffdf5a40ece4f835bd075fab14f891ba91b634ff595782a5d89f81a14ac | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 44                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x988b3a538b618c7a603e1c11ab82cd16dbe28069                         | Address of the contract that produced the log                |
| \_address         | VARCHAR   | 0x60da07cfb273051aa9827dabffcd298c305cd00d                         |                                                              |
| \_disputeID       | VARCHAR   | 93                                                                 |                                                              |
| \_tokenAmount     | VARCHAR   | 0                                                                  |                                                              |
| \_ETHAmount       | VARCHAR   | 65000000000000000                                                  |                                                              |
