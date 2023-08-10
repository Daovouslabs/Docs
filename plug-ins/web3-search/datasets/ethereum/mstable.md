# mstable

## 1. Table: MassetProxy\_event\_Swapped\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-27 09:01:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 13498486                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x93b7367bcf8fb9e719ddbc047fced9f47754f758dc8ca0cfb276d2309dbf5ee1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 541                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xe2f2a5c287993345a840db3b0845fbc70f5935a5                         | Address of the contract that produced the log                |
| swapper           | VARCHAR   | 0x27239549dd40e1d60f5b80b0c4196923745b1fd2                         |                                                              |
| input             | VARCHAR   | 0x57ab1ec28d129707052df4df418d58a2d46d5f51                         |                                                              |
| output            | VARCHAR   | 0x6b175474e89094c44da98b954eedeac495271d0f                         |                                                              |
| outputAmount      | VARCHAR   | 81856746661046557740905                                            |                                                              |
| scaledFee         | VARCHAR   | 32758162471448262712                                               |                                                              |
| recipient         | VARCHAR   | 0x27239549dd40e1d60f5b80b0c4196923745b1fd2                         |                                                              |
