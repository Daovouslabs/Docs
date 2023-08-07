# chainlink

## 1. Table: AccessControlledOffchainAggregator\_event\_AddedAccess\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-19 15:47:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2370326                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xca025939b5b6c272e196fc327490c4b41a647eb5497054104c131e24222fad70 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ae17556f9698fc47c365a746ab9cddcb17f3809                         | Address of the contract that produced the log                |
| user              | VARCHAR   | 0x87121f6c9a9f6e90e59591e4cf4804873f54a95b                         |                                                              |

## 2. Table: AccessControlledOffchainAggregator\_event\_AnswerUpdated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 08:17:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3346501                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfb6aa43d7a5e405a67669196884a272423d897d1531936a841fce8da3dbaaa6d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 14                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5d041081725468aa43e72ff0445fde2ad1ade775                         | Address of the contract that produced the log                |
| current           | VARCHAR   | 99808582                                                           |                                                              |
| roundId           | VARCHAR   | 96                                                                 |                                                              |
| updatedAt         | VARCHAR   | 1637914624                                                         |                                                              |

## 3. Table: AccessControlledOffchainAggregator\_event\_BillingAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-22 21:40:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15435681                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xed291af1ee89f95597d1deeec8d59a32677a979c48c43b7666a1c6116617d3dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x52df0481c6d2ad7e50889afd03c8ddd8413ac63d                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x2be843e2a5907fff0b7c9337b5058617bfec2bfe                         |                                                              |

## 4. Table: AccessControlledOffchainAggregator\_event\_BillingSet\_history

| Column                  | Type      | Example                                                            | Description                                                  |
| ----------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp        | TIMESTAMP | 2021-07-13 01:03:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number           | INTEGER   | 101796                                                             | The block number where this event was emitted                |
| transaction\_hash       | VARCHAR   | 0xe5a611c87d9d50341038dc344797d0b65925786b31b4f75fdb9e33109b2697d7 | Hash of the transactions in which this event was emitted     |
| log\_index              | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address       | VARCHAR   | 0xfc06bb03a9e1d8033f87ea6a682cbd65477a43b9                         | Address of the contract that produced the log                |
| maximumGasPrice         | VARCHAR   | 1000                                                               |                                                              |
| reasonableGasPrice      | VARCHAR   | 100                                                                |                                                              |
| microLinkPerEth         | VARCHAR   | 104073000                                                          |                                                              |
| linkGweiPerObservation  | VARCHAR   | 760000                                                             |                                                              |
| linkGweiPerTransmission | VARCHAR   | 4750000                                                            |                                                              |

## 5. Table: AccessControlledOffchainAggregator\_event\_CheckAccessDisabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 6. Table: AccessControlledOffchainAggregator\_event\_CheckAccessEnabled\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 7. Table: AccessControlledOffchainAggregator\_event\_ConfigSet\_history

| Column                    | Type      | Example                                                                                              | Description                                                  |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp          | TIMESTAMP | 2022-04-12 14:59:34+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number             | INTEGER   | 9696434                                                                                              | The block number where this event was emitted                |
| transaction\_hash         | VARCHAR   | 0x54ff6ae8e521e3a750b7ec7c6cecdd36e341768d993f4cceccc5b7e612b295ca                                   | Hash of the transactions in which this event was emitted     |
| log\_index                | INTEGER   | 0                                                                                                    | Integer of the log index position in the block of this event |
| contract\_address         | VARCHAR   | 0xb39bfad6295724e01e079ee3aa78a378eff6deb0                                                           | Address of the contract that produced the log                |
| previousConfigBlockNumber | VARCHAR   | 0                                                                                                    |                                                              |
| configCount               | VARCHAR   | 1                                                                                                    |                                                              |
| signers                   | VARCHAR   | 0xcdE24C6ee1151CdeB4DebB4A7C037999aF155FA4,0xa789F747f352D877C6c233909Ef1ecc15330DE49,0x92F6f38Bfc39 |                                                              |
| transmitters              | VARCHAR   | 0xA82d4EdB72dD3D167D00058F2404658F4E9A010A,0xC76b9d4B13717f959ea45Ec6e3Db9C3F9304d7d5,0x51c5C8e22675 |                                                              |
| threshold                 | VARCHAR   | 3                                                                                                    |                                                              |
| encodedConfigVersion      | VARCHAR   | 1                                                                                                    |                                                              |
| encoded                   | VARCHAR   | 0x00000000000000000000000000000000000000000000000000000000000000200000000000000000000000000000000000 |                                                              |

## 8. Table: AccessControlledOffchainAggregator\_event\_NewRound\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-14 15:46:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9799100                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2f9dd52d94cb1c69fcc302e888d95a39668c79a77aa4830f46acc8160a10edfa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0ae17556f9698fc47c365a746ab9cddcb17f3809                         | Address of the contract that produced the log                |
| roundId           | VARCHAR   | 293                                                                |                                                              |
| startedBy         | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| startedAt         | VARCHAR   | 1649951165                                                         |                                                              |

## 9. Table: AccessControlledOffchainAggregator\_event\_NewTransmission\_history

| Column            | Type      | Example                                                                                             | Description                                                  |
| ----------------- | --------- | --------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 11:28:04+00:00                                                                           | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 90259270                                                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9bae8e62c7dfeea584b8d66b011ecd153c49f46c650ed7dcfe59cd11bd40b09d                                  | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                                                   | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x076577765a3e66db410ecc1372d0b0db503a42c5                                                          | Address of the contract that produced the log                |
| aggregatorRoundId | VARCHAR   | 23223                                                                                               |                                                              |
| answer            | VARCHAR   | 329807120                                                                                           |                                                              |
| transmitter       | VARCHAR   | 0x01f4e56d5ee46e84edf8595ca7a7b62a3306de76                                                          |                                                              |
| observations      | VARCHAR   | 329628869,329690000,329754912,329800000,329807120,329807120,329820000,329824976,329824976,330300000 |                                                              |
| observers         | VARCHAR   | 0x09070503010604000208                                                                              |                                                              |
| rawReportContext  | VARCHAR   | 0x00000000000000000000001daf840b23e94d5dcad494e96683231c0002b37c02                                  |                                                              |

## 10. Table: AccessControlledOffchainAggregator\_event\_OraclePaid\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| transmitter       | VARCHAR   |                                                              |             |
| payee             | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |

## 11. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-08 19:12:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14094535                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x85fb1f2b8bca77c7eee3d174715552cd26512814701a3805e089168cdd6869b3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf1cd5cb759f8e21c98a4367b665f43d607e8885                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x88e104d83599dab09050b4fe9486b3dfa2d3c0de                         |                                                              |
| to                | VARCHAR   | 0x2f3b388eb017613eb51f06843dfef12db1fdd3c5                         |                                                              |

## 12. Table: AccessControlledOffchainAggregator\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-08 20:02:54+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14097055                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x524aed001d44375e7f1489164cda5eb493aef042ca4c353aa01bd0b3242929a0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbf1cd5cb759f8e21c98a4367b665f43d607e8885                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x88e104d83599dab09050b4fe9486b3dfa2d3c0de                         |                                                              |
| to                | VARCHAR   | 0x2f3b388eb017613eb51f06843dfef12db1fdd3c5                         |                                                              |

## 13. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferRequested\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| transmitter       | VARCHAR   |                                                              |             |
| current           | VARCHAR   |                                                              |             |
| proposed          | VARCHAR   |                                                              |             |

## 14. Table: AccessControlledOffchainAggregator\_event\_PayeeshipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-07-13 00:14:27+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 101633                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a11d648f0566c520a86fef2228583c193b0d4b258db109821b57a04900548d9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3607e46698d218b3a5cae44bf381475c0a5e2ca7                         | Address of the contract that produced the log                |
| transmitter       | VARCHAR   | 0x27c56a6d40f20a33349f0822201fbc10d455be66                         |                                                              |
| previous          | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0x797de2909991c66c66d8e730c8385bbab8d18ea6                         |                                                              |

## 15. Table: AccessControlledOffchainAggregator\_event\_RemovedAccess\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| user              | VARCHAR   |                                                              |             |

## 16. Table: AccessControlledOffchainAggregator\_event\_RequesterAccessControllerSet\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-25 17:40:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12944390                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac7b3e3792cfcf1817fb6f8b6caa3d8e6e71cb70baa142e011cbc3a84c894355 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc195ba27455182e3bb6f86dab5838901604ba72c                         | Address of the contract that produced the log                |
| old               | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| current           | VARCHAR   | 0xf1c3c8c14c31a5f74614572e922cd8f4fc626185                         |                                                              |

## 17. Table: AccessControlledOffchainAggregator\_event\_RoundRequested\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-17 10:00:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 102051862                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb29c17af6174839c9e146c077bfcc5ee58b44b13761622e2412460e3a4c1cd0f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf867a76dc4445a2e39f3217fa15d6a9edc0eab61                         | Address of the contract that produced the log                |
| requester         | VARCHAR   | 0xdbfb137861cbfd05e81fd295cf273476487dee89                         |                                                              |
| configDigest      | VARCHAR   | 0x993ee62ac86d01f33df4807bb089d8e2                                 |                                                              |
| epoch             | VARCHAR   | 0                                                                  |                                                              |
| round             | VARCHAR   | 0                                                                  |                                                              |

## 18. Table: AccessControlledOffchainAggregator\_event\_ValidatorConfigSet\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousValidator | VARCHAR   |                                                              |             |
| previousGasLimit  | VARCHAR   |                                                              |             |
| currentValidator  | VARCHAR   |                                                              |             |
| currentGasLimit   | VARCHAR   |                                                              |             |

## 19. Table: EACAggregatorProxy\_call\_confirmAggregator\_history

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
| \_aggregator       | VARCHAR   |                                                                                                                        |             |
