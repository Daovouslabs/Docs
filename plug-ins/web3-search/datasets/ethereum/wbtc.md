# wbtc

## 1. Table: WBTC\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-12 03:45:59+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17029353                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa571509d6b5ed7339eb51cc243d864fd18441085665aca5e877b866818c161ff             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 277                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xdef719dfc4f1c346b5aa87cc76a202e15d910f29                                     |                                                              |
| spender           | VARCHAR   | 0x000000000022d473030f116ddee9f6b43ac78ba3                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 2. Table: WBTC\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-24 14:20:14+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11516801                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3e55b0f56aaccd6be6481e2b6079fa04c55fbe708697390bb00137434ec308cb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 94                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         | Address of the contract that produced the log                |
| burner            | VARCHAR   | 0xca06411bd7a7296d7dbdd0050dfc846e95febeb7                         |                                                              |
| value             | VARCHAR   | 55000000000                                                        |                                                              |

## 3. Table: WBTC\_event\_MintFinished\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 4. Table: WBTC\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-21 18:29:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11700431                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45efef8f065a365dc1259ea2ff3efc158cde397ae8d45a90115646665555c29f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 50                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         | Address of the contract that produced the log                |
| to                | VARCHAR   | 0x808e4981f6287b13711b78de9d7c169e5d180643                         |                                                              |
| amount            | VARCHAR   | 54978000000                                                        |                                                              |

## 5. Table: WBTC\_event\_OwnershipRenounced\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| previousOwner     | VARCHAR   |                                                              |             |

## 6. Table: WBTC\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-11-24 21:48:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 6766297                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x25423584547d5f849c590352f2a38de98b4475b1982041e9c35223fd1746b223 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 100                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x8b41783ad99fcbeb8d575fa7a7b5a04fa0b8d80b                         |                                                              |
| newOwner          | VARCHAR   | 0xca06411bd7a7296d7dbdd0050dfc846e95febeb7                         |                                                              |

## 7. Table: WBTC\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 8. Table: WBTC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2019-10-08 01:42:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8698491                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xec1957528758eef4ecf33c69708b9e290a3527c899ac02ebf896e635f7c0a8bf | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 65                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2260fac5e5542a773aa44fbcfedf7c193bc2c599                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x9787ffbd8ac920317ba43333913419f14489aa5f                         |                                                              |
| to                | VARCHAR   | 0x9ae49c0d7f8f9ef4b864e004fe86ac8294e20950                         |                                                              |
| value             | VARCHAR   | 5696307                                                            |                                                              |

## 9. Table: WBTC\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
