# aztec

## 1. Table: RollupProcessorV2\_event\_RollupProcessed\_history

| Column                 | Type      | Example                                                            | Description                                                  |
| ---------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp       | TIMESTAMP | 2022-08-11 04:16:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number          | INTEGER   | 15318546                                                           | The block number where this event was emitted                |
| transaction\_hash      | VARCHAR   | 0xe017db27bbcd6b7b363d20df2894fbfd440ff2bc2439938b26a2da030900e9a6 | Hash of the transactions in which this event was emitted     |
| log\_index             | INTEGER   | 73                                                                 | Integer of the log index position in the block of this event |
| contract\_address      | VARCHAR   | 0xff1f2b4adb9df6fc8eafecdcbf96a2b351680455                         | Address of the contract that produced the log                |
| rollupId               | VARCHAR   | 1103                                                               |                                                              |
| nextExpectedDefiHashes | VARCHAR   |                                                                    |                                                              |
| sender                 | VARCHAR   | 0xa173bddf4953c1e8be2ca0695cfc07502ff3b1e7                         |                                                              |

## 2. Table: RollupProcessor\_event\_RollupProcessed\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-12-04 07:42:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13738563                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xab9cb87a8239a3948bf6e6b91189fc362a99268a4e398de76a8e22fcb8963b70 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 366                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x737901bea3eeb88459df9ef1be8ff3ae1b42a2ba                         | Address of the contract that produced the log                |
| rollupId          | VARCHAR   | 1341                                                               |                                                              |
| dataRoot          | VARCHAR   | 0x26899ac6a5d55f316d74e059db636f9f0fe07ee0a584e1304b6db38d94e88a0c |                                                              |
| nullRoot          | VARCHAR   | 0x0412b22aa2bf331a9877e1be41c111b19198893b2104a5742fb03f2d6f399950 |                                                              |
| rootRoot          | VARCHAR   | 0x0537e3faa8427657e8019a8d18444f44efd86975aedcdb12c8e391cd5a35534d |                                                              |
| dataSize          | VARCHAR   | 173568                                                             |                                                              |
