# synthetix

## 1. Table: Synth\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-20 13:33:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 99965723                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf7fcfecb3398eba724b5a8621fad6796f59eba383f4921436caf727853493d58 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c6f28f2f1a3c87f0f938b96d27520d9751ec8d9                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x00409fc839a2ec2e6d12305423d37cd011279c09                         |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                         |                                                              |
| value             | VARCHAR   | 25100000000000000000                                               |                                                              |

## 2. Table: Synth\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-24 01:30:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3802953                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x693d4b9038b8f34bf1f326c5aeb4eef3008f66cd41d3aeb27ef52b84dd77a9bc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x81ddfac111913d3d5218dea999216323b7cd6356                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0xde910777c787903f78c89e7a0bf7f4c435cbb1fe                         |                                                              |
| newOwner          | VARCHAR   | 0x6d4a64c57612841c2c6745db2a4e4db34f002d20                         |                                                              |

## 3. Table: Synth\_event\_OwnerNominated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-24 15:13:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 422746                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x47a8370abdaa3a42104fa6c82bcc81bf59ee56667c5aa82031d16a57fee261f4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x298b9b95708152ff6968aafd889c6586e9169f1d                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0x6d4a64c57612841c2c6745db2a4e4db34f002d20                         |                                                              |

## 4. Table: Synth\_event\_TargetUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-09 21:16:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11086818                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9337691734592ee6f6fddc083cedc4eb18b228e05df960a7b898872e2609ce5f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c6f28f2f1a3c87f0f938b96d27520d9751ec8d9                         | Address of the contract that produced the log                |
| newTarget         | VARCHAR   | 0xdfa2d3a0d32f870d87f8a0d7aa6b9cdeb7bc5adb                         |                                                              |

## 5. Table: Synth\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-21 20:30:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2536983                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5cabacef5ea49bd10e0a97e29ed0699eb3b32d9a9be14a72940b93f906a2da3c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8c6f28f2f1a3c87f0f938b96d27520d9751ec8d9                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc0f184c6c4832b3ed861bd5b05722792ffa64abd                         |                                                              |
| to                | VARCHAR   | 0xeb197d4d5a42cc24f288b554aba70df2d17a7dcb                         |                                                              |
| value             | VARCHAR   | 239795547193255979806                                              |                                                              |

## 6. Table: Synthetix\_event\_AccountFlaggedForLiquidation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-10 03:35:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36588201                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf0effdac7580c2b456a9c99c1c56f5f973a4f1f7f8972e408e17783d172484fe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x61c7bc9b335e083c30c8a81b93575c361cde93e2                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xa5d07a4eb94751a22cfe5abe845bf4235ae23670                         |                                                              |
| deadline          | VARCHAR   | 1668094552                                                         |                                                              |

## 7. Table: Synthetix\_event\_AccountLiquidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-12 21:25:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 97803573                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe9a0909da4d42aec9e3a5bc6219cea3d4ac97648724f7e5e8ed843a84c68d832 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8700daec35af8ff88c16bdf0418774cb3d7599b4                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xe334e30309dbf1ae8b237026a767da7316e10203                         |                                                              |
| snxRedeemed       | VARCHAR   | 3771399821692761003                                                |                                                              |
| amountLiquidated  | VARCHAR   | 5161750880058638350                                                |                                                              |
| liquidator        | VARCHAR   | 0xe334e30309dbf1ae8b237026a767da7316e10203                         |                                                              |

## 8. Table: Synthetix\_event\_AccountRemovedFromLiquidation\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-31 15:30:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 33142068                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfbc5cc697ef52bb1b0f56ecd0ecb4a77aa590a82c759fef82b3fe5c29ce13066 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x61c7bc9b335e083c30c8a81b93575c361cde93e2                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0x60ca6c29b5cc36eef58690de1eb0da11bb4f7876                         |                                                              |
| time              | VARCHAR   | 1667230257                                                         |                                                              |

## 9. Table: Synthetix\_event\_Approval\_history

| Column            | Type      | Example                                                                       | Description                                                  |
| ----------------- | --------- | ----------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-04 16:45:26+00:00                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17701445                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb40b90855321221cec94172789dca88d90d88d5f93006eb0db7208a70a39be36            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8700daec35af8ff88c16bdf0418774cb3d7599b4                                    | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xacf1222153e2b795cc35c57c32edd8b8eae86279                                    |                                                              |
| spender           | VARCHAR   | 0x00000000000013adddc0919642d45f5d9df09502                                    |                                                              |
| value             | VARCHAR   | 57896044618658097711785492504343953926634992332820282019728792003956564819968 |                                                              |

## 10. Table: Synthetix\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-09 04:38:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3360011                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc39977e94e96afdf1a9ce9964c017720c66207c5b9ac7c640577574555904626 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 168                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8700daec35af8ff88c16bdf0418774cb3d7599b4                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x3c5c3677b46b2b90811fee2dcffda0eaa3826b19                         |                                                              |
| newOwner          | VARCHAR   | 0x6d4a64c57612841c2c6745db2a4e4db34f002d20                         |                                                              |

## 11. Table: Synthetix\_event\_OwnerNominated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-23 13:54:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 83167822                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8fa7f785f2979bcb4370d92fd6fb45cc90699a767768b816ca6524544176bd1e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 182                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8700daec35af8ff88c16bdf0418774cb3d7599b4                         | Address of the contract that produced the log                |
| newOwner          | VARCHAR   | 0x6d4a64c57612841c2c6745db2a4e4db34f002d20                         |                                                              |

## 12. Table: Synthetix\_event\_TargetUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-14 06:02:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8222849                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x000577b6982f827fb713573235bca161819bdb55748d83d793c9a9329125f042 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 329                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8700daec35af8ff88c16bdf0418774cb3d7599b4                         | Address of the contract that produced the log                |
| newTarget         | VARCHAR   | 0xc66a263f2c7c1af0bd70c6ca4bff5936f3d6ef9f                         |                                                              |

## 13. Table: Synthetix\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-11 11:45:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3439586                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac8e53a40b58946fa8fadf844584979f9fe2aa45595f3d62cf9d90f907f7a3cd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8700daec35af8ff88c16bdf0418774cb3d7599b4                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xc80dd50fd6702f81df2f02221161938bebbb5cd7                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| value             | VARCHAR   | 1632707459974953478834                                             |                                                              |
