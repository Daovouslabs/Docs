# mintbase

## 1. Table: ThingFactory\_event\_StoreLaunch\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-13 21:41:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11251838                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xded8f99fdc29ad364d8063715e5bb49e4bfc1408df098ff33a0dcecbc283b203 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 87                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0e6541374e9d7dee2c53c15a1a00fbe41c7b7198                         | Address of the contract that produced the log                |
| store             | VARCHAR   | 0x08902e073b5282fc94f6da1d32d5b4888aa26b13                         |                                                              |
| name              | VARCHAR   | cryptomex2020                                                      |                                                              |
| symbol            | VARCHAR   | ETH                                                                |                                                              |

## 2. Table: Thing\_event\_Minted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-04-02 21:38:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9795014                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x438b201659a20a8e15d07c3ac51bda00e9cc1a7f8a6426ae2aac6fbb5a1acb67 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0b23ad11e92fdf87eb5c9b0f24b9860f9c4689ee                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 100                                                                |                                                              |
| metaId            | VARCHAR   | OjZ2GaixwXmjOwM6Tgsw                                               |                                                              |
