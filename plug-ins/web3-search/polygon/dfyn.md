# dfyn

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-07 12:43:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 23441028                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xee6c52b6baf2a57640b6d3d4d3d4857187d99c2fa71b21976ffa67a7bf56b7a7 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 336                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe7fb3e833efe5f9c441105eb65ef8b261266423b                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x017b98bf90324934ff826ce55bd98a0027b133a6                         |                                                              |
| token1            | VARCHAR   | 0x4c28f48448720e9000907bc2611f73022fdce1fa                         |                                                              |
| pair              | VARCHAR   | 0xc68640cd3b3905f302b2b25a9924ee449b33381b                         |                                                              |
| \_uint            | VARCHAR   | 1425                                                               |                                                              |

## 2. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-13 18:05:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45038077                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc0f45b1c075af24e13fc1c59456c7be488fa8c67644757c150d20af23dc4369e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 127                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xd776c65b2a7a5832b4172742bf8c40cc062c678e                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x00d00f85b8dc34abf9ddad0864804d367d3bd58f                         |                                                              |
| amount0In         | VARCHAR   | 7680126733906168253                                                |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 6587380                                                            |                                                              |
| to                | VARCHAR   | 0x0097692463fd591aef388851fe2d756505f498ac                         |                                                              |

## 3. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-10 09:06:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 34162117                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9bd8a84ea9d7aafc01ad05d6df1a8de43bf5a6a983c1093a8666ea0357e8dc34 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 120                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16d57b97efc221ee6abfa491f363b316e7da4e08                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xba8765802198e5c19f2ba8fe9b0da2b225927aaf                         |                                                              |
| value             | VARCHAR   | 97306459882150979952                                               |                                                              |

## 4. Table: UniswapV2Router02\_call\_swapExactETHForTokens\_history

| Column             | Type      | Example                                                                               | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-09 07:46:14+00:00                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37854925                                                                              | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbab59cf8cea9bfb37dc02173c5a6f9fb838702cba5c460d3c7c0096bc7f5d6f6                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 96                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa102072a4c07f06ec3b4900fdc4c7b80b6c57429                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                  | Error in case input parsing failed                                                                                     |
| amountOutMin       | VARCHAR   | 6458853481863178                                                                      |                                                                                                                        |
| path               | VARCHAR   | 0x4c28f48448720e9000907BC2611F73022fdcE1fA,0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619 |                                                                                                                        |
| to                 | VARCHAR   | 0x0e32afc8e858f900ec1b63c14a5cf1c5138e6333                                            |                                                                                                                        |
| deadline           | VARCHAR   | 1673251526                                                                            |                                                                                                                        |
