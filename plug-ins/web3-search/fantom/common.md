# common

## 1. Table: All\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-11 14:11:26+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 55562791                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x70164583231fd0b2a59a625124e5051714862314ef30e54f2937732018bf739c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07887afcbf106a70e77d5876755cb72d3522fae3                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x6ca3052e6d4b46c3437fa4c7235a0907805aaec8                         |                                                              |
| wad               | VARCHAR   | 2029329                                                            |                                                              |

## 2. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 00:43:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36162419                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x31e73bf1802644a2d76a0bb1a6d816b3f92e4a615e900fc5dfd00b7368a13caa | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xba856fb681852a122712466567f5011e1ebe9bbf                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x6125fd14b6790d5f66509b7aa53274c93dae70b9                         |                                                              |
| from              | VARCHAR   | 0x6f982737e7d97607317a55810b2c8fa913ef0873                         |                                                              |
| to                | VARCHAR   | 0x6125fd14b6790d5f66509b7aa53274c93dae70b9                         |                                                              |
| ids               | VARCHAR   | 315                                                                |                                                              |
| values            | VARCHAR   | 1                                                                  |                                                              |

## 3. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                                     | Description                                                  |
| ----------------- | --------- | --------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-29 22:19:59+00:00                                                   | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 53019666                                                                    | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe605989969838c92520463c7bbeb288c5aaa5e073d42ba2f4efee4a487d3d54a          | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                          | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x07bbb494cc048da39b5a11938f405424c66b75fb                                  | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x864d1a96d1bffda4842cc163db22269185d4c738                                  |                                                              |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                                  |                                                              |
| to                | VARCHAR   | 0xfe817b00f2cd0e062a5f66067e9a9ef789144cbf                                  |                                                              |
| id                | VARCHAR   | 904625697166532776746648320380374280103671755200316906558262375061821325312 |                                                              |
| value             | VARCHAR   | 12078084345119                                                              |                                                              |

## 4. Table: All\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-15 19:52:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 60014038                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2deb52fe2f29b9b353222306e4906a96bd557696916d9876e82a18042d9859a6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x040993fbf458b95871cd2d73ee2e09f4af6d56bb                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xb68c83be9d7c89585e2b9fa3050baa9d421b9d34                         |                                                              |
| wad               | VARCHAR   | 200000000000000000000                                              |                                                              |
