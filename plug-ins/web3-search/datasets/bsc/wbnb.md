# wbnb

## 1. Table: WBNB\_event\_Deposit\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-12 08:57:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29032501                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39fc62fa07a7be11b19089712a0fe2066ea96c7b434376af400effe656ce0b6c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 553                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         | Address of the contract that produced the log                |
| dst               | VARCHAR   | 0x00000000000e8716b4e2d12400a01474cdfad760                         |                                                              |
| wad               | VARCHAR   | 9070738505376189                                                   |                                                              |

## 2. Table: WBNB\_event\_Withdrawal\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-05 06:46:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3716566                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x90ac5fbfd2f5d697011c530c7c8180ca94182024ab08fc7176ba3c416193dd2f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 5                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         | Address of the contract that produced the log                |
| src               | VARCHAR   | 0x039b5818e51dfec86c1d56a4668787af0ed1c068                         |                                                              |
| wad               | VARCHAR   | 17086616678273983042                                               |                                                              |
