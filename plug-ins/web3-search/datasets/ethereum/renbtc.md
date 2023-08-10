# renbtc

## 1. Table: RenERC20LogicV1\_call\_burn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-06-28 14:32:56+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 10354827                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2154598d62618a03b2d843267086218f0967397d646c73590be73856646a50d2 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 33                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xeb4c2781e4eba804ce9a9803c67d0893436bb27d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_from             | VARCHAR   | 0x8afd7b9ff404ad18fed4275d3e44e63eaa15158a                         |                                                                                                                        |
| \_amount           | VARCHAR   | 282748085                                                          |                                                                                                                        |

## 2. Table: RenERC20LogicV1\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2020-12-25 23:41:49+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11525803                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xfd4982eca2760273a03a01c4907119dc29e329937830acb88904f2a284cb8c6b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 23                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,0,1                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xeb4c2781e4eba804ce9a9803c67d0893436bb27d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| \_to               | VARCHAR   | 0x32666b64e9fd0f44916e1378efb2cfa3b3b96e80                         |                                                                                                                        |
| \_amount           | VARCHAR   | 299150250                                                          |                                                                                                                        |

## 3. Table: RenERC20LogicV1\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-12-02 02:39:58+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11370446                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1e873d87db2c23907d9db5b5aa9f3b62937d0243fbd205dffe5b75eb3fd0c86b             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 96                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb4c2781e4eba804ce9a9803c67d0893436bb27d                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x303985ba2209b5c0c745885fa6fdd2ec1feb81a5                                     |                                                              |
| spender           | VARCHAR   | 0x02af7c867d6ddd2c87decec2e4aff809ee118fbb                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007910873570645 |                                                              |

## 4. Table: RenERC20LogicV1\_event\_LogRateChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| \_rate            | VARCHAR   |                                                              |             |

## 5. Table: RenERC20LogicV1\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-03-24 23:02:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9736971                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa0be8f8e050e75d5639b70b1ad43ef1d071bf1ca1d0742242d48adae55575f44 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb4c2781e4eba804ce9a9803c67d0893436bb27d                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0xfe45ab17919759cfa2ce35215ead5ca4d1fc73c7                         |                                                              |

## 6. Table: RenERC20LogicV1\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-10 19:28:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11029591                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfaad31609b69c4531ca3a149796c8f2058712bc27c83a2cce56be39e718750b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 219                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xeb4c2781e4eba804ce9a9803c67d0893436bb27d                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x81fbef4704776cc5bba0a5df3a90056d2c6900b3                         |                                                              |
| to                | VARCHAR   | 0x0865e5fdfc82868c51398b22709b2d44d8880baf                         |                                                              |
| value             | VARCHAR   | 2136695                                                            |                                                              |
