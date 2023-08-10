# renbtc

## 1. Table: RenERC20LogicV1\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-06-29 07:42:52+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16279150                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4280c83c820ecbb31d1328da8a0c7692f1898048b5a8a1db8cbd96659ed5d059             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 107                                                                            | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdbf31df14b66535af65aac99c32e9ea844e14501                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x0be5149120375a4b5ba59352d55173c9b0283c3d                                     |                                                              |
| spender           | VARCHAR   | 0x11111112542d85b3ef69ae05771c2dccff4faa26                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913127701935 |                                                              |

## 2. Table: RenERC20LogicV1\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-22 06:36:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 38379105                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfdf9769198a13da6b7141adeedad8be8a5be32f5b413135d3f07b46114ef9933 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 663                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xdbf31df14b66535af65aac99c32e9ea844e14501                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x4fd19e59a1041e82acb3ecc6773ee99913076868                         |                                                              |
| to                | VARCHAR   | 0x786ea8c02b77bbf0363a3fba135e1e3ebb326ec1                         |                                                              |
| value             | VARCHAR   | 166                                                                |                                                              |
