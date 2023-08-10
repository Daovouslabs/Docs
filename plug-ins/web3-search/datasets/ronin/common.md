# common

## 1. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| operator          | VARCHAR   |                                                              |             |
| from              | VARCHAR   |                                                              |             |
| to                | VARCHAR   |                                                              |             |
| ids               | VARCHAR   |                                                              |             |
| values            | VARCHAR   |                                                              |             |

## 2. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 21:32:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26394941                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcec53167b90bf20053c05aa5b20065998cf1fc55a9b1a9e1b78062e3b62baa8a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc25970724f032af21d801978c73653c440cf787c                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x96d6c47e5f34311f5b1b6ec2a028bd78d19f45ab                         |                                                              |
| from              | VARCHAR   | 0x96d6c47e5f34311f5b1b6ec2a028bd78d19f45ab                         |                                                              |
| to                | VARCHAR   | 0x1f59ce6aa7672eec7858a6e93c20313b24a5f093                         |                                                              |
| id                | VARCHAR   | 1000010                                                            |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |
