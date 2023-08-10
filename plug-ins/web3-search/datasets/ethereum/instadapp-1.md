# instadapp

## 1. Table: InstaIndex\_event\_LogAccountCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-08-03 01:35:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10583886                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3b2155248167f2f51faf60467a48f09f57b662f01f363efb087cf3990666f84 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 224                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2971adfa57b20e5a416ae5a708a8655a9c74f723                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xca5c59946910d16a73f5c74977ea50eadca2ca6a                         |                                                              |
| owner             | VARCHAR   | 0xca5c59946910d16a73f5c74977ea50eadca2ca6a                         |                                                              |
| account           | VARCHAR   | 0xbdddae3e46e2f49069c698aa9a080f75c80f3572                         |                                                              |
| origin            | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 2. Table: InstaIndex\_event\_LogNewAccount\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-19 20:50:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12071451                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcc972d2183c8aa0bab04d5f57e2c093fd426939cd17be91ce2c7f5fde1edeb14 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 134                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2971adfa57b20e5a416ae5a708a8655a9c74f723                         | Address of the contract that produced the log                |
| \_newAccount      | VARCHAR   | 0xfe02a32cbe0cb9ad9a945576a5bb53a3c123a3a3                         |                                                              |
| \_connectors      | VARCHAR   | 0x7d53e606308a2e0a1d396f30dc305cc7f8483436                         |                                                              |
| \_check           | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 3. Table: InstaIndex\_event\_LogNewCheck\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-19 19:44:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9904784                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x206f2036b78d395e6854420b4367d0ae4c7c450e260b06c9322c885605fb825c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 75                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2971adfa57b20e5a416ae5a708a8655a9c74f723                         | Address of the contract that produced the log                |
| accountVersion    | VARCHAR   | 1                                                                  |                                                              |
| check             | VARCHAR   | 0x1879bee186bffba9a8b1cad8181bbfb218a5aa61                         |                                                              |

## 4. Table: InstaIndex\_event\_LogNewMaster\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-03 21:52:18+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9801621                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7977dedddc36596f6f4400e1eb0c49c02460672b7ec67101722c7fe540b1c8f2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 70                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2971adfa57b20e5a416ae5a708a8655a9c74f723                         | Address of the contract that produced the log                |
| master            | VARCHAR   | 0xfcd22438ad6ed564a1c26151df73f6b33b817b56                         |                                                              |

## 5. Table: InstaIndex\_event\_LogUpdateMaster\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-04 08:05:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9804320                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdaac53b6511d001c603f0c60d0901fd79949857ea3e0c6276d3f9ea6d72c693a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 79                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2971adfa57b20e5a416ae5a708a8655a9c74f723                         | Address of the contract that produced the log                |
| master            | VARCHAR   | 0xfcd22438ad6ed564a1c26151df73f6b33b817b56                         |                                                              |

## 6. Table: InstaRegistry\_event\_Created\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-06-16 07:54:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7968272                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcb2edbccc495d67d4fe9c639bf70c4d08c6bd88e8360c2e2b9b56b038aca7d8b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 34                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x498b3bfabe9f73db90d252bcd4fa9548cd0fd981                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x400463516b26fb08b64ef7ec3fc9c001f1659c98                         |                                                              |
| owner             | VARCHAR   | 0x400463516b26fb08b64ef7ec3fc9c001f1659c98                         |                                                              |
| proxy             | VARCHAR   | 0x9f94c214bd9064ac698dbb85940c073d37619189                         |                                                              |
