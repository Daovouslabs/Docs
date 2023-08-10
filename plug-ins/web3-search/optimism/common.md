# common

## 1. Table: All\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-21 08:19:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4664444                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd0e509564990597063ce7a40370c7cf97e4ff9c032e50fb982c6328075634dbe | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4200000000000000000000000000000000000006                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x00000000000013adddc0919642d45f5d9df09502                         |                                                              |
| wad               | VARCHAR   | 145776562846222059                                                 |                                                              |

## 2. Table: All\_event\_TransferBatch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-21 15:29:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107177297                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3c2462e97fe8845b54976e705a3673e6e7218e337b4e6caed4302da530db104 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2f05e799c61b600c65238a9df060caba63db8e78                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x2f05e799c61b600c65238a9df060caba63db8e78                         |                                                              |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x8ab10ecf5f4149c9251ef0a524db21d0b041ee65                         |                                                              |
| ids               | VARCHAR   | 1                                                                  |                                                              |
| values            | VARCHAR   | 1                                                                  |                                                              |

## 3. Table: All\_event\_TransferSingle\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-23 20:46:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 100859839                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc20cd6458ffa170802cfb251cccf85524c9655219bdc5966a1ff12a9992d72ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0856c0e5ddcfc71ad07d765ddcabac0eac5b283a                         | Address of the contract that produced the log                |
| operator          | VARCHAR   | 0x1e0049783f008a0085193e00003d00cd54003c71                         |                                                              |
| from              | VARCHAR   | 0x1d3d6781d7709f1d6dfd1c9d9bd1cb46588ee796                         |                                                              |
| to                | VARCHAR   | 0x38015ea5728cc7378ac4501d2f218565919e1843                         |                                                              |
| id                | VARCHAR   | 0                                                                  |                                                              |
| value             | VARCHAR   | 1                                                                  |                                                              |

## 4. Table: All\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-20 14:19:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2466948                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xad8aa960cbe876f1466ed49ab17137e36ee0579340983d4112c3fc30f8155f4c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4200000000000000000000000000000000000006                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x05c4a00abd985c647fd24ae135310ad7e6a6df6d                         |                                                              |
| wad               | VARCHAR   | 201193027233042834796                                              |                                                              |
