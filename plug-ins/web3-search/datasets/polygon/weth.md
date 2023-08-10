# weth

## 1. Table: WETH\_call\_deposit\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-13 17:16:19+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 27094934                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xb4e516b014050cf9d97d2cc55db869e512ff9b036b10ab0baefc611797cf5278 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 8                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 0                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| user               | VARCHAR   | 0x608cfc1575b56a82a352f14d61be100fa9709d75                         |                                                                                                                        |
| depositData        | VARCHAR   | 0x8f4f2da22e8ac8f11e15f9fc141cddbb5deea8800186560abb6e68c5496619a9 |                                                                                                                        |

## 2. Table: WETH\_call\_withdraw\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-09-02 07:20:25+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 18653720                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x37457063f35d68d02460747e5999d617ee77d6f74559e7c0582fd2d9c44faf91 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 1000000000000000000                                                |                                                                                                                        |

## 3. Table: WETH\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 00:33:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9140352                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x592738ccfbc08b4154c22f8c0e0c08f16f43c3b36f689fc25be2facd0ffa38e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 30                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x400a0a8fde5eb8bb365cda143e241b0f767c9c97                         |                                                              |
| value             | VARCHAR   | 150627588206894900                                                 |                                                              |
