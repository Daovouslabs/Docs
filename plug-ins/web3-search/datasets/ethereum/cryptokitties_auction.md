# cryptokitties\_auction

## 1. Table: SaleClockAuction\_event\_AuctionCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-10-15 22:05:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11063030                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8ace583be8bf4316974f1bbfbecfa54c6e243eba1fff7095131d955e904666bb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 115                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb1690c08e213a35ed9bab7b318de14420fb57d8c                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 433467                                                             |                                                              |

## 2. Table: SaleClockAuction\_event\_AuctionCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2020-01-30 02:57:22+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 9381019                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x92a5f965ce5d4019acca50e2e5a672781e968612f41673462f0515c85548c67c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 102                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb1690c08e213a35ed9bab7b318de14420fb57d8c                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 1823133                                                            |                                                              |
| startingPrice     | VARCHAR   | 6800000000000000                                                   |                                                              |
| endingPrice       | VARCHAR   | 0                                                                  |                                                              |
| duration          | VARCHAR   | 15573600                                                           |                                                              |

## 3. Table: SaleClockAuction\_event\_AuctionSuccessful\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-01-04 23:10:45+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11590918                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe490c0bcda5a361678deac5ba1d08eb9db154e752ae17a97a9e6d88dfaa44869 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 189                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb1690c08e213a35ed9bab7b318de14420fb57d8c                         | Address of the contract that produced the log                |
| tokenId           | VARCHAR   | 1318021                                                            |                                                              |
| totalPrice        | VARCHAR   | 4467736111111112                                                   |                                                              |
| winner            | VARCHAR   | 0xceb1b68d2103ae9344b1933c492fe7f576a64272                         |                                                              |

## 4. Table: SaleClockAuction\_event\_Pause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 5. Table: SaleClockAuction\_event\_Unpause\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
