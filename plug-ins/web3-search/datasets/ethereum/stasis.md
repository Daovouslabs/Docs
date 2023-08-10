# stasis

## 1. Table: EURS\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-08-29 09:52:25+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6234015                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc767d169797a855ca568ef10d85984249b9a37d4bf7c44fd7ebbba1ce7394b88 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 26                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdb25f211ab05b1c97d595516f45794528a807ad8                         | Address of the contract that produced the log                |
| \_from            | VARCHAR   | 0xe9baa6f938e8fe64daa028cb856379d792eb1b42                         |                                                              |
| \_to              | VARCHAR   | 0x8df9e3ec00ba27415b679e033179377766a299e1                         |                                                              |
| \_value           | VARCHAR   | 850                                                                |                                                              |
