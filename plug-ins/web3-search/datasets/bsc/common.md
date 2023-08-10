# common

## 1. Table: All\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-14 01:32:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3077388                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd97f8da0e0fcd45f4378fbd852359776461cbeeb69a1b1a5049f1718dbbc42c0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x039b5818e51dfec86c1d56a4668787af0ed1c068                         |                                                              |
| wad               | VARCHAR   | 1000000000000000000                                                |                                                              |

## 2. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-04 03:31:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7992335                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xae8873eb10f5df49d3d45f7e17a6ef1de612c921d0a2146188364116a142bcc7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 269                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc6c0f80966d0210c1e081e7522490cc8fdf2641e                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x436fed8e02520cfa3108664db52a341ac977494f                         |                                                              |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xbca1a99f4ff969301be2995a509bc393344e0303                         |                                                              |
| ids               | VARCHAR   | 87                                                                 |                                                              |
| values            | VARCHAR   | 1                                                                  |                                                              |

## 3. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-29 14:05:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11338181                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb20baa006224f03e5f94dd465f13f0482fdbea02f2e5e2b45fcf5e034cd3af70 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 587                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x740260fd7f93dc5d27beefc5f6ac4bc3b67f869c                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x00eb634a79cb4ed102be603843057ba7cef2da87                         |                                                              |
| from              | VARCHAR   | 0x00eb634a79cb4ed102be603843057ba7cef2da87                         |                                                              |
| to                | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| id                | VARCHAR   | 0                                                                  |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 4. Table: All\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-09-11 06:03:43+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 377481                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9a3b33df84546d0e18235c198eb3204577ad0d9da2b4b4b537a8cc611a00449a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x9f2b4211f564a44e95cfa4fd6010029037777777                         |                                                              |
| wad               | VARCHAR   | 90400000000000000000                                               |                                                              |
