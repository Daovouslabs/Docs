# graph\_protocol

## 1. Table: GraphTokenLockManager\_event\_FunctionCallAuth\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 16:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17785624                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90b89d1a5fbabf31452ab4517a03847029907fd53200090587553c0c1aea72de | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 257                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfcf78ac094288d7200cfdb367a8cd07108dfa128                         | Address of the contract that produced the log                |
| caller            | VARCHAR   | 0x6fc78dcc8a949d1530035bd577dcb21e9787100e                         |                                                              |
| sigHash           | VARCHAR   | 0xfc837ce2                                                         |                                                              |
| target            | VARCHAR   | 0xca82c7ce3388b0b5d307574099ac57d7a00d509f                         |                                                              |
| signature         | VARCHAR   | setL2WalletAddressManually(address)                                |                                                              |

## 2. Table: GraphTokenLockManager\_event\_MasterCopyUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-16 21:35:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11466643                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf73486cc233e3c0434d6645dacf5f5e9ba2193a7a4025542a6e504c28e22fdf3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfcf78ac094288d7200cfdb367a8cd07108dfa128                         | Address of the contract that produced the log                |
| masterCopy        | VARCHAR   | 0xbe5e630383b5baecf0db7b15c50d410edd5a2255                         |                                                              |

## 3. Table: GraphTokenLockManager\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-19 21:51:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13058287                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xef2ed5847fe9aa3c703bf93cf4ada6900fbf4393a97733cca5f74a8b940d9d6b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 512                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfcf78ac094288d7200cfdb367a8cd07108dfa128                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x06590a641dc3eb43f2cebe435576389f209116da                         |                                                              |
| newOwner          | VARCHAR   | 0x6fc78dcc8a949d1530035bd577dcb21e9787100e                         |                                                              |

## 4. Table: GraphTokenLockManager\_event\_ProxyCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-23 00:02:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11708439                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xabb1e5b609d3a931eb9456f1efe7e42ef15b56a5bdaa3c9ad346f2bb67c1e793 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 241                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfcf78ac094288d7200cfdb367a8cd07108dfa128                         | Address of the contract that produced the log                |
| proxy             | VARCHAR   | 0x48392a1624585c7462943108bd7622e941bc4be0                         |                                                              |

## 5. Table: GraphTokenLockManager\_event\_TokenDestinationAllowed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-27 16:33:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17785624                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90b89d1a5fbabf31452ab4517a03847029907fd53200090587553c0c1aea72de | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 258                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfcf78ac094288d7200cfdb367a8cd07108dfa128                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0xca82c7ce3388b0b5d307574099ac57d7a00d509f                         |                                                              |
| allowed           | VARCHAR   | true                                                               |                                                              |

## 6. Table: GraphTokenLockManager\_event\_TokenLockCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-22 12:40:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11705344                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3589a9bf82c4c0e6661abc4a56f43c9e6a3b255b452ce92e447a0e9f964b8b8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 71                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfcf78ac094288d7200cfdb367a8cd07108dfa128                         | Address of the contract that produced the log                |
| contractAddress   | VARCHAR   | 0xf736cf2cc8be57fef94e9ed3b2ead612b0c1fe5e                         |                                                              |
| initHash          | VARCHAR   | 0x15c668ec430585f67ffab33c7a3fc1e1fe8911912fdfa2c7014fb5ea8f43f04e |                                                              |
| beneficiary       | VARCHAR   | 0x91fd285b190be3685c1305a6a965570d7e3b8137                         |                                                              |
| token             | VARCHAR   | 0xc944e90c64b2c07662a292be6244bdf05cda44a7                         |                                                              |
| managedAmount     | VARCHAR   | 333333330000000000000000                                           |                                                              |
| startTime         | VARCHAR   | 1608224400                                                         |                                                              |
| endTime           | VARCHAR   | 1734454800                                                         |                                                              |
| periods           | VARCHAR   | 16                                                                 |                                                              |
| releaseStartTime  | VARCHAR   | 0                                                                  |                                                              |
| vestingCliffTime  | VARCHAR   | 0                                                                  |                                                              |
| revocable         | VARCHAR   | 2                                                                  |                                                              |

## 7. Table: GraphTokenLockManager\_event\_TokensDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-14 23:18:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12241127                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2c344d4cff7640739c421db3ef9335c95bf2e984106374875af2e69293a14ce0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 80                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfcf78ac094288d7200cfdb367a8cd07108dfa128                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x06590a641dc3eb43f2cebe435576389f209116da                         |                                                              |
| amount            | VARCHAR   | 133333330000000000000000                                           |                                                              |

## 8. Table: GraphTokenLockManager\_event\_TokensWithdrawn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
