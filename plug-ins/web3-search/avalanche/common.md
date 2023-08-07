# common

## 1. Table: All\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-22 01:29:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 278766                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe09deaec799b084cd652625e17c319af12dbe2b6ea1195bfff05b034fca30918 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x0a440509c34877f183495cc3961ce6b1113a0754                         |                                                              |
| wad               | VARCHAR   | 2000000000000000000                                                |                                                              |

## 2. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-30 00:25:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17972108                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70f0451bc7a4bf2d56be15915529e9f94cfab96bdba0e292ae9576e92def9863 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 17                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc4957dc87e1cbd031621f9aae8346c35384d4e69                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x346579e4c7713026513b45a153f9f43d9fc118f4                         |                                                              |
| from              | VARCHAR   | 0x16c1a2b3dd8863b1ea6a593088702ec787135d20                         |                                                              |
| to                | VARCHAR   | 0x346579e4c7713026513b45a153f9f43d9fc118f4                         |                                                              |
| ids               | VARCHAR   | 2002                                                               |                                                              |
| values            | VARCHAR   | 9                                                                  |                                                              |

## 3. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-12 22:57:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2305929                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14d61e37fe3b4b9ef4ba61c5fb2799e045c0164eb1b0bf91759201c71fe59862 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xfd3a10715775f8b7fd308c7a8065022bfb67df34                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x2614170d08a4391b0f06c5e23f232711a60ffc3f                         |                                                              |
| from              | VARCHAR   | 0x2614170d08a4391b0f06c5e23f232711a60ffc3f                         |                                                              |
| to                | VARCHAR   | 0x2614170d08a4391b0f06c5e23f232711a60ffc3f                         |                                                              |
| id                | VARCHAR   | 1                                                                  |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 4. Table: All\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 10:18:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29962001                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd3de58984cd0b22ed9d5aec286217427e91ab465e5203e862ae2f822faf9c230 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 38                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb31f66aa3c1e785363f0875a1b74e27b85fd66c7                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x03e16374498b1a46823d1b95c7aaf3f8cd527f18                         |                                                              |
| wad               | VARCHAR   | 16849712096792977                                                  |                                                              |
