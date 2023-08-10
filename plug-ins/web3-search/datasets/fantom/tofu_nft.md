# tofu\_nft

## 1. Table: MarketNG\_event\_EvAuctionRefund\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-06-03 21:15:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39716944                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe0ce0731d7654ccf9f2907b8cfe833c2abac2bad678ad9866263c31ce7832eeb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86232f68b5bf2a3a03851d98556352512a3b12b9                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 2709214                                                            |                                                              |
| bidder            | VARCHAR   | 0xfe7cfc4d67d1113964c946182cb25cb653098e37                         |                                                              |
| refund            | VARCHAR   | 2000000000000000000                                                |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2023-07-10 21:36:32+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 65545527                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd24f2bec502f79a80e8dc2667b69f2294dc56dbe875b332d98cd60207c1c61e2 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x86232f68b5bf2a3a03851d98556352512a3b12b9                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 2312942                                                            |                                                              |
| inventory         | VARCHAR   | \[object Object]                                                   |                                                              |

## 4. Table: MarketNG\_event\_EvMarketSignerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-11-19 01:51:39+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22467635                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9f0ad2ed407c21b4bd0a493288f5e59d4ccb3ae043815141531a75bb7323e94e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 4                                                                  | Integer of the log index position in the block of this event |
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
| block\_timestamp  | TIMESTAMP | 2021-11-19 01:51:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22467631                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdfbbc39efc21159da00d777d804088ddf99a3e37debc5e8cf24a4db75fd57bc0 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 45                                                                 | Integer of the log index position in the block of this event |
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
