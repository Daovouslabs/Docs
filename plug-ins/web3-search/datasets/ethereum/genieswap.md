# genieswap

## 1. Table: GenieSwap\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-09 20:31:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13386696                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x41e0cff0fa895d7b97e574165adf23f797aed633007e1aa03cae5992b9f09441 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 250                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0a267cf51ef038fc00e71801f5a524aec06e4f07                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x073ab1c0cad3677cde9bdb0cdeedc2085c029579                         |                                                              |
| newOwner          | VARCHAR   | 0xe6f3503e20a5102e995219885b2d63be7fa9dfc8                         |                                                              |
