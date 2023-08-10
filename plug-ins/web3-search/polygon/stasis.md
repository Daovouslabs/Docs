# stasis

## 1. Table: EURS\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-26 03:36:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 21807866                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdc68b979eb6c073078d689e59833092d05a14046a4f17aafcc1c99ae7266cf90 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 628                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe111178a87a3bff0c8d18decba5798827539ae99                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xe26ae3d881f3d5def58d795f611753804e7a6b26                         |                                                              |
| to                | VARCHAR   | 0x933fe0dd67211cd05274cb0259477f713f25e92f                         |                                                              |
| value             | VARCHAR   | 6421223                                                            |                                                              |
