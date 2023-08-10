# tether

## 1. Table: EURT\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-29 18:29:17+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20749568                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4b4290a357bc09abe6080578b25c518616d8530c1b1b5044bc0d55ed34ee53ce | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 639                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bdf330f423ea880ff95fc41a280fd5ecfd3d09f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xbabe61887f1de2713c6f97e567623453d3c79f67                         |                                                              |
| value             | VARCHAR   | 42997875072                                                        |                                                              |

## 2. Table: USDT\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-13 16:51:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 10813952                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x376efe38ded420273d25e4e3ed404bdb57feeb494ed4a26f1297f5016fd0601e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 202                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc2132d05d31c914a87c6611c10748aeb04b58e8f                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xfcd76d7929dcb381c47d2f162e7d264a36861c63                         |                                                              |
| value             | VARCHAR   | 500000000                                                          |                                                              |
