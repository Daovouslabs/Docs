# arrakis

## 1. Table: arrakis\_vault\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-11 01:42:07+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14752017                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcbc0875abfeb5144c3f3e84848711971066bcc8974c37d86c03ebef7e9e43995             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                              | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x18d53f4953ad14236602da05efafc0df4f5d064d                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x881dd85238ca7a71d12e6499405c9a51a25355c6                                     |                                                              |
| spender           | VARCHAR   | 0xdc5bbb7f25a05259b2bd559936771f8fc0e2c4cb                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: arrakis\_vault\_event\_Burned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-17 22:51:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15556387                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b329b209c8b9a4c0904864bab440321b69f3371b872ca26c6010e3639e398e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xabddafb225e10b90d798bb8a886238fb835e2053                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0xed3a954c0adfc8e3f85d92729c051ff320648e30                         |                                                              |
| burnAmount        | VARCHAR   | 441772598315524042572                                              |                                                              |
| amount0Out        | VARCHAR   | 334256978730368878676588                                           |                                                              |
| amount1Out        | VARCHAR   | 116608452962                                                       |                                                              |
| liquidityBurned   | VARCHAR   | 451018250006163210586                                              |                                                              |

## 3. Table: arrakis\_vault\_event\_FeesEarned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-21 19:20:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14050758                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc7d5f9fb48fda1a6548cf36f2f5b329ef1be2001765645dd9f51a72060277b01 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 246                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x26c2251801d2cfb5461751c984dc3eaa358bdf0f                         | Address of the contract that produced the log                |
| feesEarned0       | VARCHAR   | 744574828998774619950                                              |                                                              |
| feesEarned1       | VARCHAR   | 600628268563986353                                                 |                                                              |

## 4. Table: arrakis\_vault\_event\_Minted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-30 10:35:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16519079                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3ac3dad6999643c59f26ec346546c9b2879472f31a237ca99da52bae99a99a5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x857e0b2ed0e82d5cdeb015e77ebb873c47f99575                         | Address of the contract that produced the log                |
| receiver          | VARCHAR   | 0xe84adc0964ee34ce0319df3418636ed6a4117b97                         |                                                              |
| mintAmount        | VARCHAR   | 7380006454751001417                                                |                                                              |
| amount0In         | VARCHAR   | 51455157319999999999                                               |                                                              |
| amount1In         | VARCHAR   | 136563120676106149                                                 |                                                              |
| liquidityMinted   | VARCHAR   | 7596006827569342986                                                |                                                              |

## 5. Table: arrakis\_vault\_event\_Rebalance\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 21:32:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17808544                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9500a1c7c50d9d6a28a5ad227692bd1cef69a950da46b11300436db670e668c9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 341                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x50379f632ca68d36e50cfbc8f78fe16bd1499d1e                         | Address of the contract that produced the log                |
| lowerTick\_       | VARCHAR   | -276326                                                            |                                                              |
| upperTick\_       | VARCHAR   | -276322                                                            |                                                              |
| liquidityBefore   | VARCHAR   | 533943016751256576657207                                           |                                                              |
| liquidityAfter    | VARCHAR   | 533956190180653914165880                                           |                                                              |

## 6. Table: arrakis\_vault\_event\_SetManagerFee\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-23 13:59:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13861836                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa03d07257e7b7b3b520967a259043150ec8d980e6eb64f7d644565524d14ab53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 316                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x77a56c01b83d48be9142be30299d4656d24b560e                         | Address of the contract that produced the log                |
| managerFee        | VARCHAR   | 9750                                                               |                                                              |

## 7. Table: arrakis\_vault\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 18:35:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14354231                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb696f588f8767eac666175a2be3802ff5132095e055375acd4a39d8ebe422983 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 437                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x18d53f4953ad14236602da05efafc0df4f5d064d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x5993bad196c8786baaedb5a5868f338fe6ce4cc2                         |                                                              |
| value             | VARCHAR   | 248053704650208556639                                              |                                                              |

## 8. Table: arrakis\_vault\_event\_UpdateAdminTreasury\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldAdminTreasury  | VARCHAR   |                                                              |             |
| newAdminTreasury  | VARCHAR   |                                                              |             |

## 9. Table: arrakis\_vault\_event\_UpdateGelatoParams\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-01-11 15:11:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 13984966                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0x96516529ec5ae1d7dc56445f42f20d2ee5f26ee2f4a2af96e09c738d544936ad | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 156                                                                | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0x61a0c8d4945a61bf26c13e07c30af1f1ca67b473                         | Address of the contract that produced the log                |
| gelatoRebalanceBPS     | VARCHAR   | 0                                                                  |                                                              |
| gelatoWithdrawBPS      | VARCHAR   | 1000                                                               |                                                              |
| gelatoSlippageBPS      | VARCHAR   | 0                                                                  |                                                              |
| gelatoSlippageInterval | VARCHAR   | 0                                                                  |                                                              |

## 10. Table: arrakis\_vault\_event\_UpdateManagerParams\_history

| Column                 | Type      | Example                                                      | Description |
| ---------------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp       | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number          | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash      | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index             | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address      | VARCHAR   | Address of the contract that produced the log                |             |
| managerFeeBPS          | VARCHAR   |                                                              |             |
| managerTreasury        | VARCHAR   |                                                              |             |
| gelatoRebalanceBPS     | VARCHAR   |                                                              |             |
| gelatoSlippageBPS      | VARCHAR   |                                                              |             |
| gelatoSlippageInterval | VARCHAR   |                                                              |             |

## 11. Table: factory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-03 14:22:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13734073                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5268922a158bfd7fd37327f5f741076b83234405ae303c03314f0c9c1bb83b73 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 415                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xea1aff9dbffd1580f6b81a3ad3589e66652db7d9                         | Address of the contract that produced the log                |
| uniPool           | VARCHAR   | 0x92560c178ce069cc014138ed3c2f5221ba71f58a                         |                                                              |
| manager           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| pool              | VARCHAR   | 0x47ed8d441016967f8f885382e44234efe3b5893b                         |                                                              |
