# fei

## 1. Table: Fei\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 08:52:35+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17662200                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe19b7a0217c1a1c015d3e9cd86022c3c48315d6a98564da9051a6cd0fda35a23             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 40                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x9008d19f58aabd9ed0d60971565aa8510560ab41                                     |                                                              |
| spender           | VARCHAR   | 0x1111111254fb6c44bac0bed2854e76f90643097d                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640551127146829789167182589742 |                                                              |

## 2. Table: Fei\_event\_Burning\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-17 10:41:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13632461                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3d0f3ddec643982d15fa2b8a50df7db4624856c256030429d76e90ca47fc31b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         | Address of the contract that produced the log                |
| \_to              | VARCHAR   | 0x146ee6ff7c476fb0e84a8a110c5d1409a2685c19                         |                                                              |
| \_burner          | VARCHAR   | 0x17305f0e18318994a57b494078cac866a857f7b6                         |                                                              |
| \_amount          | VARCHAR   | 912122612257814592644139                                           |                                                              |

## 3. Table: Fei\_event\_CoreUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-14 21:23:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14006029                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x07754cc45b372744158b61973800ae0fd20a2159a27bbd20231e53c5bbe8914a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 47                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         | Address of the contract that produced the log                |
| \_core            | VARCHAR   | 0x10ffa0cd36bc16b355d21a08df4a552c4a9fec10                         |                                                              |

## 4. Table: Fei\_event\_Minting\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-09-16 13:45:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13237093                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x198a50e3e2c603c1b5e89e698fde8857c52116b1176c303ad84146e07359ea13 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         | Address of the contract that produced the log                |
| \_to              | VARCHAR   | 0x146ee6ff7c476fb0e84a8a110c5d1409a2685c19                         |                                                              |
| \_minter          | VARCHAR   | 0xe1578b4a32eaefcd563a9e6d0dc02a4213f673b7                         |                                                              |
| \_amount          | VARCHAR   | 643111115836996780465265                                           |                                                              |

## 5. Table: Fei\_event\_Paused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-07 23:14:29+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12195615                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x20f0c7ff27fa4a7fa80d2cd1996533a2886ef12476124a446d6c1786fec0e12f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 57                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xb8f482539f2d3ae2c9ea6076894df36d1f632775                         |                                                              |

## 6. Table: Fei\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-29 00:11:31+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15042307                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x987469b5985913d241e8a759566ab89da1995f06a22f74909d2310f7296cd4f0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 309                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x3bb1e66aa91a284259478dedfe0a8994bd9e1767                         |                                                              |
| to                | VARCHAR   | 0x185ab80a77d362447415a5b347d7cd86ecacc87c                         |                                                              |
| value             | VARCHAR   | 549860242114945121024                                              |                                                              |

## 7. Table: Fei\_event\_Unpaused\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-04-11 19:58:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12220739                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x69f85b7b22597967cba8e8dd5bcc7b41e87f894b1601e8758ebfb05542c27baf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 93                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x956f47f50a910163d8bf957cf5846d573e7f87ca                         | Address of the contract that produced the log                |
| account           | VARCHAR   | 0xb8f482539f2d3ae2c9ea6076894df36d1f632775                         |                                                              |
