# oneplanet

## 1. Table: OnePlanet\_call\_cancel\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-03 06:44:08+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37612565                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5333447ea93ea58229d58ed5787d292ea51acd45a3d452f44b1fcbc3b977efdd                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 18                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xcbbecf690e030d096794f7685a1bf4a58378a575                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0x494a23373F82636b29b21C821d5C98C763893548,0x0000000000000000000000000000000000000000,2,0x09421f5334 |                                                                                                                        |

## 2. Table: OnePlanet\_call\_fulfillAdvancedOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-03-18 08:58:08+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 40483581                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x7e8ecc4b3aadcf48dee4c57eebb07fca6276dbb9b134a345fd5943bacb4ff08d                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 61                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xcbbecf690e030d096794f7685a1bf4a58378a575                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrder       | VARCHAR   | 0xd40bB6C49c3f0B09317B781E61AD994EF510E2D9,0x0000000000000000000000000000000000000000,3,0x0686113B49 |                                                                                                                        |
| criteriaResolvers   | VARCHAR   |                                                                                                      |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient           | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |

## 3. Table: OnePlanet\_call\_fulfillAvailableAdvancedOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-06-07 04:33:16+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 43622541                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0x3f957b7046531f4fc63c1b877bfba03c6121c78e243b39ee79b2131175d0432c                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 39                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0xcbbecf690e030d096794f7685a1bf4a58378a575                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders            | VARCHAR   | 0x79A01FB5E7818AD33F74390fc773701D5D40d9E4,0x0000000000000000000000000000000000000000,2,0x88345f12E6 |                                                                                                                        |
| criteriaResolvers         | VARCHAR   |                                                                                                      |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0,2,0                                                                                          |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,0,0,1,1,1,2,1,0,2,1,0,2,0,1,2,2,2                                                                  |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient                 | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 3                                                                                                    |                                                                                                                        |

## 4. Table: OnePlanet\_call\_fulfillAvailableOrders\_history

| Column                    | Type      | Example                                                                                                                | Description |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp          | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number             | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash         | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index        | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address            | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address               | VARCHAR   | Address of the called contract                                                                                         |             |
| status                    | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error                     | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| orders                    | VARCHAR   |                                                                                                                        |             |
| offerFulfillments         | VARCHAR   |                                                                                                                        |             |
| considerationFulfillments | VARCHAR   |                                                                                                                        |             |
| fulfillerConduitKey       | VARCHAR   |                                                                                                                        |             |
| maximumFulfilled          | VARCHAR   |                                                                                                                        |             |

## 5. Table: OnePlanet\_call\_fulfillBasicOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-19 04:25:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 45251038                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xfd68c8177b6b8b1d0599f9b48ba4c7508cccb2ac1104d1d77d0708daeee6c084                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 37                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xcbbecf690e030d096794f7685a1bf4a58378a575                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| parameters         | VARCHAR   | 0x0000000000000000000000000000000000000000,0,1365000000000000000,0x320825e149c2Fea0B5017D9e9b081713e |                                                                                                                        |

## 6. Table: OnePlanet\_call\_fulfillOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-02-05 16:56:39+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 38947052                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x97045a5f433eeeb5a554e69a2021fddf74a728105cb61038718dd8ab7b93e8e4                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 62                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xcbbecf690e030d096794f7685a1bf4a58378a575                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order               | VARCHAR   | 0x606bC2c0eA822dE6f901c3fd16ECe5a5793e3899,0x0000000000000000000000000000000000000000,2,0xBE01981E8f |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |

## 7. Table: OnePlanet\_call\_getCounter\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| offerer            | VARCHAR   |                                                                                                                        |             |

## 8. Table: OnePlanet\_call\_getOrderHash\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| order              | VARCHAR   |                                                                                                                        |             |

## 9. Table: OnePlanet\_call\_getOrderStatus\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| orderHash          | VARCHAR   |                                                                                                                        |             |

## 10. Table: OnePlanet\_call\_incrementCounter\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |

## 11. Table: OnePlanet\_call\_information\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |

## 12. Table: OnePlanet\_call\_matchAdvancedOrders\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| advancedOrders     | VARCHAR   |                                                                                                                        |             |
| criteriaResolvers  | VARCHAR   |                                                                                                                        |             |
| fulfillments       | VARCHAR   |                                                                                                                        |             |

## 13. Table: OnePlanet\_call\_matchOrders\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| orders             | VARCHAR   |                                                                                                                        |             |
| fulfillments       | VARCHAR   |                                                                                                                        |             |

## 14. Table: OnePlanet\_call\_name\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |

## 15. Table: OnePlanet\_call\_validate\_history

| Column             | Type      | Example                                                                                                                | Description |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp   | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number      | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash  | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address     | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address        | VARCHAR   | Address of the called contract                                                                                         |             |
| status             | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error              | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| orders             | VARCHAR   |                                                                                                                        |             |

## 16. Table: OnePlanet\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newCounter        | VARCHAR   |                                                              |             |
| offerer           | VARCHAR   |                                                              |             |

## 17. Table: OnePlanet\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-11-11 13:04:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 35478243                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x43912d2e1c8f9d2e744e46f40c589c79c475ab323e99e836676e3b0c13c97401 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 149                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcbbecf690e030d096794f7685a1bf4a58378a575                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x0816d3fdbbef1e7ed87e77c74e48985ef1b8ed950cb57186428fe90e003e309a |                                                              |
| offerer           | VARCHAR   | 0x01650a260f652c3fe649324efdce386746171e81                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 18. Table: OnePlanet\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-18 19:05:38+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45236596                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xcdded83287ec3b8243e2b92e961e1f162d8856b37265ef6b5e41b4ac3d5a531f                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 168                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xcbbecf690e030d096794f7685a1bf4a58378a575                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x8cfde0a456b732ee8101e8eccbf2551fefc839f1097727dc93b62f33c0f0409e                                   |                                                              |
| offerer           | VARCHAR   | 0x8bca9f3016a33b1e34135d5f536e46ed541f1a28                                                           |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| recipient         | VARCHAR   | 0x2ac6a9338182c40fbc8c98ba522c3612ee75b9e9                                                           |                                                              |
| offer             | VARCHAR   | 2,0x51Cf70671791b8ea366c8C44e33b4d8e219a5CA0,134,1                                                   |                                                              |
| consideration     | VARCHAR   | 0,0x0000000000000000000000000000000000000000,0,12800000000000000000,0x8bCA9f3016A33b1e34135D5f536e46 |                                                              |

## 19. Table: OnePlanet\_event\_OrderValidated\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| orderHash         | VARCHAR   |                                                              |             |
| offerer           | VARCHAR   |                                                              |             |
| zone              | VARCHAR   |                                                              |             |
