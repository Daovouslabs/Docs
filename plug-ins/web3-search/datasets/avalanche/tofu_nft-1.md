# tofu\_nft

## 1. Table: MarketNG\_event\_EvAuctionRefund\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-05-05 18:17:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14313212                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7e4fef13e3ae3ecd8c1df6a01ee00501504c9d2be6e3743a5b3b2c4db902283f | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86232f68b5bf2a3a03851d98556352512a3b12b9                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 2420641                                                            |                                                              |
| bidder            | VARCHAR   | 0x1c70364ecf3d7221270c074a4ebedb7621b1a9d3                         |                                                              |
| refund            | VARCHAR   | 212000000000000000                                                 |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2022-05-11 08:15:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14546747                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x4a5f95b49ddc2c7d1bdff69a95248f4afacf5195017deaf38eb7688e33bb3a16 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 23                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86232f68b5bf2a3a03851d98556352512a3b12b9                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 2253478                                                            |                                                              |
| inventory         | VARCHAR   | \[object Object]                                                   |                                                              |

## 4. Table: MarketNG\_event\_EvMarketSignerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-18 04:03:58+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7092777                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xecb0b4151575464b027287e59e4833349055bafd65c5b8486945e3733e4d67a5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86232f68b5bf2a3a03851d98556352512a3b12b9                         | Address of the contract that produced the log                |
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
| block\_timestamp  | TIMESTAMP | 2021-11-18 04:03:50+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7092774                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa95b3c0c3f78e22407bb21041505eb9da9c716b1e63f268585596f8f2cc5f6df | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86232f68b5bf2a3a03851d98556352512a3b12b9                         | Address of the contract that produced the log                |
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
