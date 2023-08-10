# boba

## 1. Table: OVM\_CanonicalTransactionChain\_event\_SequencerBatchAppended\_history

| Column               | Type      | Example                                                            | Description                                                  |
| -------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp     | TIMESTAMP | 2021-11-18 08:34:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number        | INTEGER   | 13638274                                                           | The block number where this event was emitted                |
| transaction\_hash    | VARCHAR   | 0x18f5c5abfa7408f1ede389898e2702c9b75be7347b36dcf4a34bf95d9b3555e7 | Hash of the transactions in which this event was emitted     |
| log\_index           | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address    | VARCHAR   | 0xfbd2541e316948b259264c02f370ed088e04c3db                         | Address of the contract that produced the log                |
| \_startingQueueIndex | VARCHAR   | 6356                                                               |                                                              |
| \_numQueueElements   | VARCHAR   | 0                                                                  |                                                              |
| \_totalElements      | VARCHAR   | 49333                                                              |                                                              |

## 2. Table: StateCommitmentChain\_event\_StateBatchAppended\_history

| Column              | Type      | Example                                                                                              | Description                                                  |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp    | TIMESTAMP | 2022-11-08 03:24:47+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number       | INTEGER   | 15922608                                                                                             | The block number where this event was emitted                |
| transaction\_hash   | VARCHAR   | 0x94df92081f352330c8e0d2ceb82dc6e5a0c2ab0dccc77104d1cf300f07fdeabd                                   | Hash of the transactions in which this event was emitted     |
| log\_index          | INTEGER   | 202                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address   | VARCHAR   | 0xde7355c971a5b733fe2133753abd7e5441d441ec                                                           | Address of the contract that produced the log                |
| \_batchIndex        | VARCHAR   | 11305                                                                                                |                                                              |
| \_batchRoot         | VARCHAR   | 0x0bfb8d1d37a8464ff91eb9ebb38698fb969a0031e42cff5308eee5404cc5534c                                   |                                                              |
| \_batchSize         | VARCHAR   | 37                                                                                                   |                                                              |
| \_prevTotalElements | VARCHAR   | 869169                                                                                               |                                                              |
| \_extraData         | VARCHAR   | 0x000000000000000000000000000000000000000000000000000000006369cbff0000000000000000000000005558c63d5b |                                                              |
