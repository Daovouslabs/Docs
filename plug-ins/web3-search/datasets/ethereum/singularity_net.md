# singularity\_net

## 1. Table: SingularityNetToken\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-19 23:41:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10693609                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x38bd7b270c24aaf28164c92f37efb0a22dc3b909d030180c86f86999dc39dc58 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 132                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8eb24319393716668d768dcec29356ae9cffe285                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x77d353cc81377b01f7aebff0a9785d5b9416ebfb                         |                                                              |
| spender           | VARCHAR   | 0xe4c9194962532feb467dce8b3d42419641c6ed2e                         |                                                              |
| value             | VARCHAR   | 600000000000                                                       |                                                              |

## 2. Table: SingularityNetToken\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-22 18:17:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13277078                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcfe8f805b1a4fa598bb12ebe360b13211bc5b8ff039eccf0bce6d5ad0e7fad0f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 90                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8eb24319393716668d768dcec29356ae9cffe285                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0xcb2cd1c1ac5db07380b68587c2fd33609aef0c47                         |                                                              |
| value             | VARCHAR   | 3395262735941                                                      |                                                              |

## 3. Table: SingularityNetToken\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-21 18:08:37+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4772418                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec238fb79eb957e959895c5a6c46b5e69a23bc9c159a51a4220400681f306c2e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8eb24319393716668d768dcec29356ae9cffe285                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x9b9de0c3bb10a7593e1c17036268b4dd4f3c81e1                         |                                                              |
| newOwner          | VARCHAR   | 0xc4aad17558fa95c8937d0856b2dad74c1a7a095f                         |                                                              |

## 4. Table: SingularityNetToken\_event\_Pause\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-12-21 18:05:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4772402                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe02dfbe2bf0974fd2a3d696039d0913d8ac067bc93f38badb96b30a8cf7dd952 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8eb24319393716668d768dcec29356ae9cffe285                         | Address of the contract that produced the log                |

## 5. Table: SingularityNetToken\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-25 21:12:09+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12110487                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdda932e05144f4f53de4d0225d6f1fe7e56de1601adb5e39dabc0cb5d95f3df0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 179                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8eb24319393716668d768dcec29356ae9cffe285                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000007f150bd6f54c40a34d7c3d5e9f56                         |                                                              |
| to                | VARCHAR   | 0x3d2d3c4446e8a82445418523b9b5b376765e55a8                         |                                                              |
| value             | VARCHAR   | 436605823850                                                       |                                                              |

## 6. Table: SingularityNetToken\_event\_Unpause\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-01-18 21:05:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4931102                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5dc9eeee7854c07349fcae1a1d5aeca4fca6c94b1caaba6208d0e71b78ac0931 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8eb24319393716668d768dcec29356ae9cffe285                         | Address of the contract that produced the log                |
