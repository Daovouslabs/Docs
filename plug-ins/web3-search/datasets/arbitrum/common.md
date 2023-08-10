# common

## 1. Table: All\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-08 16:11:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29126802                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8340e334d14dff8c8d7b89105254146541dee55e06d110035885737d51733439 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x104f1459a2ffea528121759b238bb609034c2f01                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x8630fbd88346561a58bf1ad901fb128ea3521925                         |                                                              |
| wad               | VARCHAR   | 3148356434696039                                                   |                                                              |

## 2. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-06 23:49:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 51323322                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfedcf5a40dafa59a5cb2cb833163c0450ccc4dc6ea6ac4cb7339cf6484b754cc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xf4f935f4272e6fd9c779cf0036589a63b48d77a7                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0xb3598b108f59afec664974dfd96330de48ef2d4d                         |                                                              |
| from              | VARCHAR   | 0xf9287855066fd96c8b6977987e7ad633749f74a4                         |                                                              |
| to                | VARCHAR   | 0xb3598b108f59afec664974dfd96330de48ef2d4d                         |                                                              |
| ids               | VARCHAR   |                                                                    |                                                              |
| values            | VARCHAR   |                                                                    |                                                              |

## 3. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-28 14:17:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 1719358                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8afd6ab76e13d5d0eb3cf0948a18d0e944384dba347a2861716cc9372577c799 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x039ffdc819a9429d8452435d2559ca91e6b00af7                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x4780461eb5428728767284fd5ade58890620b595                         |                                                              |
| from              | VARCHAR   | 0xeb36c0793139928cddd6cc64714d1c20c9e1813a                         |                                                              |
| to                | VARCHAR   | 0xda087ccc5ce34bfec327a27ca0ff74cd2914d51f                         |                                                              |
| id                | VARCHAR   | 10000                                                              |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 4. Table: All\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-23 16:06:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 104152358                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x24e4f6b0d991ba957fb68a4e07a51a970b9b808c4b32e19467a90c55fb49e2a8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2d9c0e1b4f97efc6aa8984ddc632cfc50f8b212d                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x0aacc6124269f9591a5fcb33d34654918c151221                         |                                                              |
| wad               | VARCHAR   | 130576357806646102                                                 |                                                              |
