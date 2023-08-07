# tofu\_nft

## 1. Table: MarketNG\_event\_EvAuctionRefund\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-03 03:38:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7334884                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4beb5f9d6d366da722353c5fbc0758a1cef04f3d2e65690c1ef13d21b0e58196 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bc8b1b5aba4df3be9f9a32dae501214dc0e4f3f                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 1545658                                                            |                                                              |
| bidder            | VARCHAR   | 0x917a7277903148cda75c4e761ed7f483470ea28c                         |                                                              |
| refund            | VARCHAR   | 197455134318750000                                                 |                                                              |

## 2. Table: MarketNG\_event\_EvCouponSpent\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| id                | VARCHAR   |                                                              |             |
| couponId          | VARCHAR   |                                                              |             |

## 3. Table: MarketNG\_event\_EvInventoryUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-22 11:04:02+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 113774431                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc8ca17e572e243134f87bac55ec9a07463af0ed6b04f452b09fdd9ec43d1aecb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bc8b1b5aba4df3be9f9a32dae501214dc0e4f3f                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 5740826                                                            |                                                              |
| inventory         | VARCHAR   | \[object Object]                                                   |                                                              |

## 4. Table: MarketNG\_event\_EvMarketSignerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-19 02:49:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3137925                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4ee2c7b1c7f24f0d58ece05c1497a451b7a7287de00faf14bb23b187b72369be | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bc8b1b5aba4df3be9f9a32dae501214dc0e4f3f                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x660c8251ca9ee617621ce4d3ca3c95e1a57ff67e                         |                                                              |
| isRemoval         | VARCHAR   | false                                                              |                                                              |

## 5. Table: MarketNG\_event\_EvSettingsUpdated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |

## 6. Table: MarketNG\_event\_EvSwapped\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| req               | VARCHAR   |                                                              |             |
| signature         | VARCHAR   |                                                              |             |
| swapper           | VARCHAR   |                                                              |             |

## 7. Table: MarketNG\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-19 02:49:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3137922                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x17c80d7362c6e4c16c67a02a277fc9d8dcd4f93bb387fada50261125d81a8db8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x7bc8b1b5aba4df3be9f9a32dae501214dc0e4f3f                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| newOwner          | VARCHAR   | 0x079a889eb69013d451ecf45377258948116e2b3e                         |                                                              |

## 8. Table: MarketNG\_event\_Paused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |

## 9. Table: MarketNG\_event\_Unpaused\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| account           | VARCHAR   |                                                              |             |
