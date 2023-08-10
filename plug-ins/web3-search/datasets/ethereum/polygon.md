# polygon

## 1. Table: PolygonZkEVM\_event\_SequenceBatches\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 07:28:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17840133                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe6ab7731e6671ff6e204aeaad72435b361b2a69101b16cfcf88bb03e3248bd5d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5132a183e9f3cb7c848b0aac5ae0c4f0491b7ab2                         | Address of the contract that produced the log                |
| numBatch          | VARCHAR   | 435122                                                             |                                                              |

## 2. Table: PolygonZkEVM\_event\_VerifyBatchesTrustedAggregator\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-03 11:28:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17179901                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xeb523a728a08588e0ac0f62cd8939ddd1e4618aa2ec7348032a552f74d78c9b2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 49                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x5132a183e9f3cb7c848b0aac5ae0c4f0491b7ab2                         | Address of the contract that produced the log                |
| numBatch          | VARCHAR   | 10461                                                              |                                                              |
| stateRoot         | VARCHAR   | 0x2c9b8d56d22949f79954fa73581dd291b6d0bf8e51f978aaf4d485b3cc57de09 |                                                              |
| aggregator        | VARCHAR   | 0xda87c4a76922598ac0272f4d9503a35071d686ea                         |                                                              |

## 3. Table: PolygonZkEVM\_event\_VerifyBatches\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| numBatch          | VARCHAR   |                                                              |             |
| stateRoot         | VARCHAR   |                                                              |             |
| aggregator        | VARCHAR   |                                                              |             |
