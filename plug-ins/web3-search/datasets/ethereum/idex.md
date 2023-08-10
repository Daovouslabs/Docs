# idex

## 1. Table: Exchange\_call\_trade\_history

| Column             | Type      | Example                                                                                               | Description                                                                                                            |
| ------------------ | --------- | ----------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2018-09-09 04:22:24+00:00                                                                             | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 6298047                                                                                               | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x8c6390d026511ec907cdd2d991fb1efc34bb082f6efcc9afc2b615be234730ae                                    | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 58                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x2a0c0dbecc7e4d658f48e01e3fa353f44050c208                                                            | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                     | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                  | Error in case input parsing failed                                                                                     |
| tradeValues        | ARRAY     | \['209790000000000000', '49950000000000', '10000', '37946034', '209790000000000000', '442', '10000000 |                                                                                                                        |
| tradeAddresses     | ARRAY     | \['0x0000000000000000000000000000000000000000', '0x41875C2332B0877cDFAA699B641402b7D4642c32', '0x0088 |                                                                                                                        |
| v                  | ARRAY     | \['27', '28']                                                                                         |                                                                                                                        |
| rs                 | ARRAY     | \['0xad06b3eb8af16c123f03df61d86cd938d7f6d3133f6189ae31b2da5b2527dfb4', '0x55f426ff8eab3a8439748c6596 |                                                                                                                        |

## 2. Table: Exchange\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-05-02 18:31:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9988421                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x089ffd0463a42d6eb802b1f0a39d2a2bbed35fe190cdff0b8d76b599d5be0647 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2a0c0dbecc7e4d658f48e01e3fa353f44050c208                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| user              | VARCHAR   | 0xb170f1da873df11500c074adc74cb113f50d7990                         |                                                              |
| amount            | VARCHAR   | 1994750000000000000                                                |                                                              |
| balance           | VARCHAR   | 1994750000000000000                                                |                                                              |

## 3. Table: Exchange\_event\_SetOwner\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2018-02-17 23:43:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5109420                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x864421208718841cebcf1c6ce5afe57521efd1d22a5ad445e2bddfa3ed0a5ff9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2a0c0dbecc7e4d658f48e01e3fa353f44050c208                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x33daedabab9085bd1a94460a652e7ffff592dfe3                         |                                                              |
| newOwner          | VARCHAR   | 0xf7ef39b200edd24bbb5fe9708dd8459b0e2c0c13                         |                                                              |

## 4. Table: Exchange\_event\_Withdraw\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2017-11-30 19:23:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 4651715                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x49ef04630993bc015e0233fde3174df1ed8003c6f088d1dae15b98ac9703f0f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 10                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2a0c0dbecc7e4d658f48e01e3fa353f44050c208                         | Address of the contract that produced the log                |
| token             | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| user              | VARCHAR   | 0xe2ce9087328eca90f35e3ed3d348bf3b17c3aad9                         |                                                              |
| amount            | VARCHAR   | 992350732540992358                                                 |                                                              |
| balance           | VARCHAR   | 0                                                                  |                                                              |
