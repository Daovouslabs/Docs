# frax

## 1. Table: FRAXStablecoin\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-05 06:40:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17847045                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x307f66141f9e5d07e08c79c84942d2cc75c3d6c1a323efcd5e0109669e7d0902 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xdfe201cedc41f970d43f95674d6b4be02de784dd                         |                                                              |
| spender           | VARCHAR   | 0x0cd6f267b2086bea681e922e19d40512511be538                         |                                                              |
| value             | VARCHAR   | 50001000000000000000000                                            |                                                              |

## 2. Table: FRAXStablecoin\_event\_FRAXBurned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-15 18:55:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16835212                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa499a1fe1c473f27637dac606dfa21aa47c4bb51cb56acdb9aacadafa8c9baa1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 82                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0ed8fa7fc63a8eb5487e7f87caf1ab3914ea4eca                         |                                                              |
| to                | VARCHAR   | 0xcf37b62109b537fa0cb9a90af4ca72f6fb85e241                         |                                                              |
| amount            | VARCHAR   | 10000000000000000000000000                                         |                                                              |

## 3. Table: FRAXStablecoin\_event\_FRAXMinted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-30 21:04:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12929240                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcbfd27b29882775f1027858325a393d6d50e72a91f9898cf4514cec92251d228 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x96665d63c1b53f8335e3c9287ee255f306c93c45                         |                                                              |
| to                | VARCHAR   | 0x96665d63c1b53f8335e3c9287ee255f306c93c45                         |                                                              |
| amount            | VARCHAR   | 2000000000000000000000000                                          |                                                              |

## 4. Table: FRAXStablecoin\_event\_RoleAdminChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| role              | VARCHAR   |                                                              |             |
| previousAdminRole | VARCHAR   |                                                              |             |
| newAdminRole      | VARCHAR   |                                                              |             |

## 5. Table: FRAXStablecoin\_event\_RoleGranted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-16 17:42:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11465581                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c3339f6e08324aea59d21f2bb68f184f5a5fd1da7605e17b0508f23c5e19673 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 43                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000 |                                                              |
| account           | VARCHAR   | 0xa448833bece66fd8803ac0c390936c79b5fd6edf                         |                                                              |
| sender            | VARCHAR   | 0xa448833bece66fd8803ac0c390936c79b5fd6edf                         |                                                              |

## 6. Table: FRAXStablecoin\_event\_RoleRevoked\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-21 02:56:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16230232                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfe3c8b561161b89b169600fb91928e26cd54825b8d0b739a5845a4a8001e0dd3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 253                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         | Address of the contract that produced the log                |
| role              | VARCHAR   | 0xb25402418ad555013210365a422f9f1206b2dd00719998db06f8a1fbe014641b |                                                              |
| account           | VARCHAR   | 0x234d953a9404bf9dbc3b526271d440cd2870bcd2                         |                                                              |
| sender            | VARCHAR   | 0x234d953a9404bf9dbc3b526271d440cd2870bcd2                         |                                                              |

## 7. Table: FRAXStablecoin\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-07 05:00:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11989355                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x429fd5e32caf158879c177f09b0c3d5a410ef15ef7de52809e975e79341648e7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 181                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x853d955acef822db058eb8505911ed77f175b99e                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xfd0a40bc83c5fae4203dec7e5929b446b07d1c76                         |                                                              |
| to                | VARCHAR   | 0x00000000000017c75025d397b91d284bbe8fc7f2                         |                                                              |
| value             | VARCHAR   | 6143036129579436456229                                             |                                                              |
