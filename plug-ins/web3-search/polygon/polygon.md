# polygon

## 1. Table: ChildChain\_event\_NewToken\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-30 17:01:04+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 905                                                                | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf3aca97caac3013bdfb224c4e682eff23dd5ad6fc8080f01b204c0ef3082498a | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd9c7c4ed4b66858301d0cb28cc88bf655fe34861                         | Address of the contract that produced the log                |
| rootToken         | VARCHAR   | 0x96cddf45c0cd9a59876a2a29029d7c54f6e54ad3                         |                                                              |
| token             | VARCHAR   | 0xa35363cff92980f8268299d0132d5f45834a9527                         |                                                              |
| \_decimals        | VARCHAR   | 0                                                                  |                                                              |

## 2. Table: ChildChain\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-30 16:59:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 849                                                                | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88e3ab569326b52e9dd8a5f72545d89d8426bbf536f3bfaf31e023fb459ca373 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd9c7c4ed4b66858301d0cb28cc88bf655fe34861                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xa2d9846c352ca61dcb20d6aad40cec1d1b228a78                         |                                                              |

## 3. Table: ChildChain\_event\_StateSyncerAddressChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-30 16:59:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 849                                                                | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x88e3ab569326b52e9dd8a5f72545d89d8426bbf536f3bfaf31e023fb459ca373 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd9c7c4ed4b66858301d0cb28cc88bf655fe34861                         | Address of the contract that produced the log                |
| previousAddress   | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newAddress        | VARCHAR   | 0x0000000000000000000000000000000000001001                         |                                                              |

## 4. Table: ChildChain\_event\_TokenDeposited\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-26 18:05:56+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14960000                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1ecf53fbaeb01244f52786194e8c6e13971ac37c477b39ce724d971f419a2ea2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 475                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd9c7c4ed4b66858301d0cb28cc88bf655fe34861                         | Address of the contract that produced the log                |
| rootToken         | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| childToken        | VARCHAR   | 0x84000b263080bc37d1dd73a29d92794a6cf1564e                         |                                                              |
| user              | VARCHAR   | 0xf2d02d5fd269240241dba9217b77833bb207bcec                         |                                                              |
| amount            | VARCHAR   | 1993734693740000000000                                             |                                                              |
| depositCount      | VARCHAR   | 127930133                                                          |                                                              |

## 5. Table: ChildChain\_event\_TokenWithdrawn\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| rootToken         | VARCHAR   |                                                              |             |
| childToken        | VARCHAR   |                                                              |             |
| user              | VARCHAR   |                                                              |             |
| amount            | VARCHAR   |                                                              |             |
| withrawCount      | VARCHAR   |                                                              |             |

## 6. Table: WMATIC\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-10-19 06:09:12+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 5928806                                                            | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbe4bee16c7e6bbb706c9768c1bd543116004fa471bd50a8ba3ddb33423baf949 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 7. Table: WMATIC\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-02-11 08:06:09+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 24806400                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x4eb4e623f4807891b3a1b86643a9b4fd2a26ee881feac4546e9be311a874d061 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 3                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| wad                | VARCHAR   | 3597924883830410314067                                             |                                                                                                                        |

## 8. Table: WMATIC\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 11:22:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 25762757                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4dae7a9c9fdd1d9cda026d3edc5d33deb3bee7bd73a02fd828c544471c9ad7a7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 138                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x00e84bb0591349f38e91e79d4c8e3125d60206c7                         |                                                              |
| wad               | VARCHAR   | 1000000000000000000                                                |                                                              |

## 9. Table: WMATIC\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-10 07:52:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 8109635                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4f98e375dd2c7bcd65c4a1bcc2bf04185c3ba686369e0a08ed9e984e37f72a96 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x6e7a5fafcec6bb1e78bae2a1f0b612012bf14827                         |                                                              |
| dst               | VARCHAR   | 0x019ba0325f1988213d448b3472fa1cf8d07618d7                         |                                                              |
| wad               | VARCHAR   | 58863885742738908512                                               |                                                              |

## 10. Table: WMATIC\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-11-27 00:36:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7552512                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x44928992b6878d2810577225d79ca4cdf9021fef77cb72b5aea1c03db5427c9e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 6                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0d500b1d8e8ef31e21c99d1db9a6444d3adf1270                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0xa5e0829caced8ffdd4de3c43696c57f7d7a678ff                         |                                                              |
| wad               | VARCHAR   | 912891575758252894985                                              |                                                              |
