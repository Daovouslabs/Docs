# tofu\_nft

## 1. Table: MarketNG\_event\_EvAuctionRefund\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-14 12:19:21+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16938538                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8f2f13af0fdc66491f9b1aea0af583c4d7de01fdecce959bb9688fac459e1bbb | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 400                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x449d05c544601631785a7c062dcdff530330317e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 2059552                                                            |                                                              |
| bidder            | VARCHAR   | 0x4165ac75516763dae3481a5143f31f7b11ed618b                         |                                                              |
| refund            | VARCHAR   | 5267500000000000                                                   |                                                              |

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
| block\_timestamp  | TIMESTAMP | 2023-03-07 04:04:19+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26248299                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb6f4793f159430c9e993b1703b56a24211bb1eaac8b2f9a4beb2c665a11589f3 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x449d05c544601631785a7c062dcdff530330317e                         | Address of the contract that produced the log                |
| id                | VARCHAR   | 5787284                                                            |                                                              |
| inventory         | VARCHAR   | \[object Object]                                                   |                                                              |

## 4. Table: MarketNG\_event\_EvMarketSignerUpdate\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-10-01 11:08:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11391736                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x8159ac1b7f65e0ac360a83c3e6471dabb020fb1ec46b6d6c9cd1bd23f2b08176 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 237                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x449d05c544601631785a7c062dcdff530330317e                         | Address of the contract that produced the log                |
| addr              | VARCHAR   | 0x5cd67f547e4904b25901810a5f68372f2c66f375                         |                                                              |
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
| block\_timestamp  | TIMESTAMP | 2022-02-21 12:33:42+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 15449836                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x843314af0c978fae6ce78a80f78d6a1c20c3a1e1ebc0695b708f806c6bc48e53 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 607                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x449d05c544601631785a7c062dcdff530330317e                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0x079a889eb69013d451ecf45377258948116e2b3e                         |                                                              |
| newOwner          | VARCHAR   | 0x5f6ffc02d221d8cb3f35c580fa91d80598ebd5db                         |                                                              |

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
