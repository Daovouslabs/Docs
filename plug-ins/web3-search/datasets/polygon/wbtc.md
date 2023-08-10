# wbtc

## 1. Table: WBTC\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-11 14:27:54+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 18993424                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x016dbf3e90d6b8917bea052b02f4f3c236bcba45bac9422c0b4d8b83e75eff30             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1110                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1bfd67037b42cf73acf2047067bd4f2c47d9bfd6                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x000000e28faa823d5b53ff6c2922c28335840375                                     |                                                              |
| spender           | VARCHAR   | 0x216b4b4ba9f3e719726886d34a177484278bfcae                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129637482 |                                                              |

## 2. Table: WBTC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-18 18:28:15+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41681152                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4570682739f751b9cc5a85340d215b892e17cf08a983daba9d3f4df465c0f7b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 133                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1bfd67037b42cf73acf2047067bd4f2c47d9bfd6                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xa1cfb393607d1a6888d273b762832ed14c8b56b1                         |                                                              |
| to                | VARCHAR   | 0xbadffffffff3f678866b558e3fd0a2a4deb4dc48                         |                                                              |
| value             | VARCHAR   | 310967                                                             |                                                              |
