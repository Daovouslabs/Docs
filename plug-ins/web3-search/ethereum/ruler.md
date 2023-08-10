# ruler

## 1. Table: AdminUpgradeabilityProxy\_event\_AdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousAdmin     | VARCHAR   |                                                              |             |
| newAdmin          | VARCHAR   |                                                              |             |

## 2. Table: AdminUpgradeabilityProxy\_event\_Upgraded\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-13 19:40:06+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12032163                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x76a180a981b5b2149e7cfc5ccfd44510c674614f08763687f999aaf679391e05 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 278                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf19f4490a7fccfef2dab8199acdb2dc1b9027c18                         | Address of the contract that produced the log                |
| implementation    | VARCHAR   | 0x2446b411a95630f719ef8c78f195ecdaf3fd5e94                         |                                                              |

## 3. Table: BonusRewards\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-16 01:51:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12046811                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9ab1c8a98293f3de51812c4e3427ba8782354f60d40082a66582ae51330827d3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 243                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3423c8af3a95d9fee7ec06c4e0e905d4fd559f89                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0xde6b2a06407575b98724818445178c1f5fd53361                         |                                                              |
| lpToken           | VARCHAR   | 0x52890a0c018fbab21794ad18e15f87fdb57fb975                         |                                                              |
| amount            | VARCHAR   | 23197692465859590789097                                            |                                                              |

## 4. Table: BonusRewards\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-03 07:36:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11963973                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6978a06c210795c8acec3bdca5b2240fe592f80995b6dc4deccb2472392170a7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3423c8af3a95d9fee7ec06c4e0e905d4fd559f89                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xdd79dc5b781b14ff091686961adc5d47e434f4b0                         |                                                              |
| newOwner          | VARCHAR   | 0x49b8a0893b83a171d7d461198b69a0b1bb4dd0ed                         |                                                              |

## 5. Table: BonusRewards\_event\_PausedStatusUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |
| old               | VARCHAR   |                                                              |             |
| \_new             | VARCHAR   |                                                              |             |

## 6. Table: BonusRewards\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-28 14:52:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12329581                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x78a9204ed8e198b050ff491588a467367c46b16e6502316682914fb8f8149555 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3423c8af3a95d9fee7ec06c4e0e905d4fd559f89                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x809e7b210f8c599ceafc3cff49f4863b2da07c59                         |                                                              |
| lpToken           | VARCHAR   | 0x1daf17e6d1d9ed6aa9fe9910ae17be98c2c4e6ba                         |                                                              |
| amount            | VARCHAR   | 9084498701649259895360                                             |                                                              |

## 7. Table: Oracle\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-01 20:31:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11954503                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac69108b65a03b3ece4f86dda581b3a758aea7127f5df982be21e21de73eff3d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 78                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1447db893bc4f6767460ad72359dead840339c6a                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x2f80e5163a7a774038753593010173322ea6f9fe                         |                                                              |

## 8. Table: RULER\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-24 05:54:24+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12099841                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6c6d15e1034b29a72f1b315f7d565fb05c25514e1172f5432890deff07324d69             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 255                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2aeccb42482cc64e087b6d2e5da39f5a7a7001f8                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xdcf231d20d0061885dbaa310c9db6f97a5bfd175                                     |                                                              |
| spender           | VARCHAR   | 0x01f7fd324b366380d2145dfa6c7a76fdb75f17b9                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 9. Table: RULER\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-03 04:00:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11963008                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe6d93062d42072de1ea443a0c5a9491b091e870041ea0951adeb1b9ff95390be | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 285                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2aeccb42482cc64e087b6d2e5da39f5a7a7001f8                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xdd79dc5b781b14ff091686961adc5d47e434f4b0                         |                                                              |

## 10. Table: RULER\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-04 01:45:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12565066                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x11c9c2956d93cd719a468385767e33b82c0dbadcd9ca9cd0cbafec12d1ac184d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2aeccb42482cc64e087b6d2e5da39f5a7a7001f8                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x000000000029f5c1eee7c85c30c0e40197fbec9b                         |                                                              |
| to                | VARCHAR   | 0xb1eecfea192907fc4bf9c4ce99ac07186075fc51                         |                                                              |
| value             | VARCHAR   | 257201680434550617342                                              |                                                              |

## 11. Table: RulerZap\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-03 04:23:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11963116                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f90e2fd3c731f98bf2ee81aa1c265a5084e6549b9f3b11dc0ab8b2d10c5e850 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbd856654ba2b6dc12c55a7bff9730ed5b056b1b1                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x2f80e5163a7a774038753593010173322ea6f9fe                         |                                                              |
