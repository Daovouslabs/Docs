# frax

## 1. Table: FRAX\_event\_TokenBurned\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-29 01:59:46+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 20723950                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfc64d45ff490f50d43f94b4f63170221aa7b5c7afe1c6f6d6edf1957d41b4721 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 72                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45c32fa6df82ead1e2ef74d17b76547eddfaff89                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x6e1a844afff1aa2a8ba3127db83088e196187110                         |                                                              |
| amount            | VARCHAR   | 114818871568690608219472                                           |                                                              |

## 2. Table: FRAX\_event\_TokenMinted\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-12 19:46:34+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 36752517                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x94e0d0161f1dfa899636bf4a5867ee821edf1009403615d62bb04a0013d6635f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45c32fa6df82ead1e2ef74d17b76547eddfaff89                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xdcb5a4b6ee39447d700f4fa3303b1d1c25ea9ca7                         |                                                              |
| to                | VARCHAR   | 0x6f7f18c15b97dc9fac48ae7f986989f97d25dbc7                         |                                                              |
| amount            | VARCHAR   | 750000000000000000000000                                           |                                                              |

## 3. Table: FRAX\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-16 15:12:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 27209445                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x09ff8c57492080c5c0b1c441dc3a07969d366e1737d007192e14d0e6c2649820 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 758                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x45c32fa6df82ead1e2ef74d17b76547eddfaff89                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xb5600746f947c25c0cbc36429f87e6c88f9d6a88                         |                                                              |
| to                | VARCHAR   | 0x9aa9baaf1e4cfea1560cc5dd19f4351b49e299f4                         |                                                              |
| value             | VARCHAR   | 240449033008236151320                                              |                                                              |
