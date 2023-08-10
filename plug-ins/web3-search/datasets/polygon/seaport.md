# seaport

## 1. Table: SeaportV12\_call\_cancel\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-13 18:34:44+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 39254869                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x429a195b492c43896e1335daacd5b3388b972be51c61ac38d782fbfd0862b57a                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 65                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0x4Cf438eb380F0D2fbac5aFA46E3066850E039365,0x0000000000000000000000000000000000000000,2,0x672f466B13 |                                                                                                                        |

## 2. Table: SeaportV12\_call\_fulfillAdvancedOrder\_history

| Column              | Type      | Example                                                                                                                | Description |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------------------------- | ----------- |
| block\_timestamp    | TIMESTAMP | Timestamp of the block where this event was emitted                                                                    |             |
| block\_number       | INTEGER   | The block number where this event was emitted                                                                          |             |
| transaction\_hash   | VARCHAR   | Hash of the transactions in which this event was emitted                                                               |             |
| transaction\_index  | INTEGER   | Integer of the transactions index position in the block                                                                |             |
| trace\_address      | VARCHAR   | Comma separated list of trace address in call tree                                                                     |             |
| to\_address         | VARCHAR   | Address of the called contract                                                                                         |             |
| status              | INTEGER   | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |             |
| error               | VARCHAR   | Error in case input parsing failed                                                                                     |             |
| advancedOrder       | VARCHAR   |                                                                                                                        |             |
| criteriaResolvers   | VARCHAR   |                                                                                                                        |             |
| fulfillerConduitKey | VARCHAR   |                                                                                                                        |             |
| recipient           | VARCHAR   |                                                                                                                        |             |

## 3. Table: SeaportV12\_call\_fulfillAvailableAdvancedOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-02-15 00:09:06+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 39300762                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0x1e6097048bcddfdf62a891fd70bbae55332844928199786dd674667bc802dfb0                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 109                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders            | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,1,0x7ceB23fD6b |                                                                                                                        |
| criteriaResolvers         | VARCHAR   | 0,1,0,284,0xaf85b9071dfafeac1409d3f1d19bafc9bc7c37974cde8df0ee6168f0086e539c,0x47c90510b0076b1143ac9 |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0                                                                                              |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,1,1,1,0,2,1,2,0,3,1,3,0,0,1,0                                                                      |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient                 | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 2                                                                                                    |                                                                                                                        |

## 4. Table: SeaportV12\_call\_fulfillAvailableOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-02-15 00:18:27+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 39301016                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0x7c3fbca2189f36712870fe6ed48e79bb0cbc1ed890c6d4bc9ca38365f31e9d58                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 54                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders                    | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,1,0x7ceB23fD6b |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0                                                                                              |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,1,1,1,0,2,1,2,0,3,1,3,0,0,1,0                                                                      |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 2                                                                                                    |                                                                                                                        |

## 5. Table: SeaportV12\_call\_fulfillBasicOrder\_efficient\_6GL6yc\_history

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
| parameters         | VARCHAR   |                                                                                                                        |             |

## 6. Table: SeaportV12\_call\_fulfillBasicOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-15 01:25:31+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 39302739                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf0f3f77a63ebe22dced73856a9fbd83b99974724ea2df7d42b8137e6555eac2b                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 53                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| parameters         | VARCHAR   | 0x672f466B13eE1856C32f8bD956730D8Eff28bF16,299,1,0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x000000 |                                                                                                                        |

## 7. Table: SeaportV12\_call\_fulfillOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-02-14 19:25:08+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 39293284                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x206c17afb675b20a35442e7868e84272c92be3b6112bb90b14b0814f65bf2ad6                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 113                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order               | VARCHAR   | 0x4Cf438eb380F0D2fbac5aFA46E3066850E039365,0x0000000000000000000000000000000000000000,2,0x672f466B13 |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |

## 8. Table: SeaportV12\_call\_getContractOffererNonce\_history

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
| contractOfferer    | VARCHAR   |                                                                                                                        |             |

## 9. Table: SeaportV12\_call\_getCounter\_history

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

## 10. Table: SeaportV12\_call\_getOrderHash\_history

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

## 11. Table: SeaportV12\_call\_getOrderStatus\_history

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

## 12. Table: SeaportV12\_call\_incrementCounter\_history

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

## 13. Table: SeaportV12\_call\_information\_history

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

## 14. Table: SeaportV12\_call\_matchAdvancedOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-15 18:32:35+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 39329849                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x0557b4345ebd8735d8a9604c44889577e1293e2f51ed6e9cc69c4bce926238e1                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 75                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0x1108f964b384f1dCDa03658B24310ccBc48E226F,0x0000000000000000000000000000000000000000,1,0x7ceB23fD6b |                                                                                                                        |
| criteriaResolvers  | VARCHAR   | 0,1,0,299,0x0a0a1bcadd9f6a5539376fa82276e043ae3cb4499daaaf8136572ecb1f9f0d60,0x2c5aad21376c135770bb8 |                                                                                                                        |
| fulfillments       | VARCHAR   | 1,0,0,0,0,0,0,1,0,0,0,2,0,0,0,3,0,0,1,0                                                              |                                                                                                                        |
| recipient          | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                                                           |                                                                                                                        |

## 15. Table: SeaportV12\_call\_matchOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-13 19:35:45+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 39256289                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x574c9ad217457bb97216693f5da0f249797fe81568c917f5d61fdccab7fd7bf5                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 86                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0xAF2A8f2B064a89Bc3537a46EF6175bf0afAe0398,0x0000000000000000000000000000000000000000,2,0x672f466B13 |                                                                                                                        |
| fulfillments       | VARCHAR   | 0,0,0,4,1,0,0,0,1,0,0,1,1,0,0,2,1,0,0,3                                                              |                                                                                                                        |

## 16. Table: SeaportV12\_call\_name\_history

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

## 17. Table: SeaportV12\_call\_validate\_history

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

## 18. Table: SeaportV12\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| newCounter        | VARCHAR   |                                                              |             |
| offerer           | VARCHAR   |                                                              |             |

## 19. Table: SeaportV12\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-10 16:21:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39140937                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xd6404c2a323755887f30cbbdacab5bffc1cd749264e6879df9f93ff0671d90dc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 198                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x0d6dc60c7fbfd1a6cc479dc6760ea5cf4a6ca2c1e9bbc419453711580d53ad87 |                                                              |
| offerer           | VARCHAR   | 0xfba662e1a8e91a350702cf3b87d0c2d2fb4ba57f                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 20. Table: SeaportV12\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-15 01:26:13+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39302759                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb16c4483d4b0dcf8fedae52562a5424e54f0455533046fd9ba4a9e24e798c93a                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 120                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x5b811d049e956de224bb263be5c4a65cda1fe31ceb51ff6254ce5b8b0fb119de                                   |                                                              |
| offerer           | VARCHAR   | 0x4d41232b0d963afb52cd0354da5819b259f133bd                                                           |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| recipient         | VARCHAR   | 0x1108f964b384f1dcda03658b24310ccbc48e226f                                                           |                                                              |
| offer             | VARCHAR   | 1,0x7ceB23fD6bC0adD59E62ac25578270cFf1b9f619,0,2000000000000000                                      |                                                              |
| consideration     | VARCHAR   | 2,0x672f466B13eE1856C32f8bD956730D8Eff28bF16,299,1,0x4d41232B0d963AFb52cd0354DA5819b259F133BD,1,0x7c |                                                              |

## 21. Table: SeaportV12\_event\_OrderValidated\_history

| Column                                          | Type                                                                                                                                                                                                                  | Example                                                      | Description |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp                                | TIMESTAMP                                                                                                                                                                                                             | Timestamp of the block where this event was emitted          |             |
| block\_number                                   | INTEGER                                                                                                                                                                                                               | The block number where this event was emitted                |             |
| transaction\_hash                               | VARCHAR                                                                                                                                                                                                               | Hash of the transactions in which this event was emitted     |             |
| log\_index                                      | INTEGER                                                                                                                                                                                                               | Integer of the log index position in the block of this event |             |
| contract\_address                               | VARCHAR                                                                                                                                                                                                               | Address of the contract that produced the log                |             |
| orderHash                                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters                                 | STRUCT\<offerer STRING, zone STRING, offer STRING, consideration STRING, orderType STRING, startTime STRING, endTime STRING, zoneHash STRING, salt STRING, conduitKey STRING, totalOriginalConsiderationItems STRING> |                                                              |             |
| orderParameters.offerer                         | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.zone                            | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.offer                           | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.consideration                   | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.orderType                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.startTime                       | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.endTime                         | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.zoneHash                        | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.salt                            | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.conduitKey                      | VARCHAR                                                                                                                                                                                                               |                                                              |             |
| orderParameters.totalOriginalConsiderationItems | VARCHAR                                                                                                                                                                                                               |                                                              |             |

## 22. Table: SeaportV12\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-15 18:32:35+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 39329849                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0557b4345ebd8735d8a9604c44889577e1293e2f51ed6e9cc69c4bce926238e1                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 339                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000006c7676171937c444f6bde3d6282                                                           | Address of the contract that produced the log                |
| orderHashes       | VARCHAR   | 0x00cadcd8f97abb2e1ea7cd159bcfdb97c94b80ae60078cd9e8fcbb6e54bd455d,0x616bfded677586871293f7c9352ff3a |                                                              |

## 23. Table: SeaportV14\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-31 21:25:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43382545                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1d20ac9119d45771442abc31d854ac9dc81218c1f4ba98138807fbe5a138ccf4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 461                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 198737073495519272666259299906869653404                            |                                                              |
| offerer           | VARCHAR   | 0x4899285cdd1146ebd360aa7727ed020bd1a7a3e1                         |                                                              |

## 24. Table: SeaportV14\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-04 23:02:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 45916449                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x98dff13b19c1708c579fa2df85df56e8e18a14c47380a6639786921b71e6cb40 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1069                                                               | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x0f0185f27a2ab9250be13f6a8a844cf72ceea993942c1206e6893872a3fdf060 |                                                              |
| offerer           | VARCHAR   | 0x00000052223266cf3d9ef1f19d6b59f1a912c357                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 25. Table: SeaportV14\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-13 08:28:50+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42647188                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7a2943a755c23f207851e7d42b716905b8c6ecc9d3a16bb5ebf91539d7f04bf0                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 191                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                                                           | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xa5b4cb1f4226a69212a6d6211b89fec26c8104f3e19ce77a308be33e24b64f7e                                   |                                                              |
| offerer           | VARCHAR   | 0x69d7ada0df0df425dec8ec30767371f978349b9a                                                           |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                              |
| recipient         | VARCHAR   | 0x001355977bf24a81143f24db9d6170f3e79dec07                                                           |                                                              |
| offer             | VARCHAR   | 2,0xBFbF690E9D4929c95Ff63a38262fe6381d974D78,429,1                                                   |                                                              |
| consideration     | VARCHAR   | 0,0x0000000000000000000000000000000000000000,0,28000000000000000000,0x69d7ADa0df0Df425DEc8EC30767371 |                                                              |

## 26. Table: SeaportV14\_event\_OrderValidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-23 14:16:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 40677130                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x2b4c99dbdc3332559e0e8048c6038c8626ef730f2c3525d326636bf0b32934ca | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 11                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000001ad428e4906ae43d8f9852d0dd6                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x8696c536279a36ad33cf77b620d47ad133175bd3c5c5e54462298a3e42a6a47c |                                                              |
| orderParameters   | VARCHAR   | \[object Object]                                                   |                                                              |

## 27. Table: SeaportV14\_event\_OrdersMatched\_history

| Column            | Type      | Example                                                                                              | Description                                                  |
| ----------------- | --------- | ---------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-05 03:38:51+00:00                                                                            | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 44697468                                                                                             | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0216744ee637b60c5c6743039a11e080eeb8c92bd668ed36c93aa5d287f0d06e                                   | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 256                                                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000000000adc04c56bf30ac9d3c0aaf14dc                                                           | Address of the contract that produced the log                |
| orderHashes       | VARCHAR   | 0xe866782fb29ab35d7bf3620c0314185aeb278365bba439d258d3a6306a977341,0xf14c012047c75e3dd03a121e560c10a |                                                              |

## 28. Table: Seaport\_call\_cancel\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-10 21:37:36+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 42549142                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9798cc096fc4596dd85ad09b11a2079cfbcad1b79a976a6a44149d336c79b084                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 43                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0xA8b968A4e11588aAC3B4F40E44E5cEF5E046DafD,0xa8b33992Baa4047A39899a4A25b48E70A9293219,3,0xBA6a05ef46 |                                                                                                                        |

## 29. Table: Seaport\_call\_fulfillAdvancedOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-05-16 05:48:11+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 42763483                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x00d74dd8de77516580d9bcee8bf54ae589872999a83d8f0db9d88d9383bddec2                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 17                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrder       | VARCHAR   | 0x6F75DDD866B9E390f9f668235C3219432EAa0eE3,0x2fe9CAf29F5667dC79425cDAb206E62aA01703BD,2,0x9CA723600f |                                                                                                                        |
| criteriaResolvers   | VARCHAR   |                                                                                                      |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |
| recipient           | VARCHAR   | 0x040b4a13a044f8a07d454e862e2c580d6088a8b8                                                           |                                                                                                                        |

## 30. Table: Seaport\_call\_fulfillAvailableAdvancedOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2022-10-20 09:23:24+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 34572000                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0x224593d4c956189f855605411286619e837884b5b5a6294cdd1a122b207aa5a9                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 41                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders            | VARCHAR   | 0x945f96041e347677864C3F09E54d4945591A270e,0x0000000000000000000000000000000000000000,3,0xA604060890 |                                                                                                                        |
| criteriaResolvers         | VARCHAR   |                                                                                                      |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0,1,0                                                                                              |                                                                                                                        |
| considerationFulfillments | VARCHAR   |                                                                                                      |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000007b02230091a7ed01230072f7006a004d60a8d4e71d599b8104250f0000                                   |                                                                                                                        |
| recipient                 | VARCHAR   | 0x0000000000000000000000000000000000000000                                                           |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 2                                                                                                    |                                                                                                                        |

## 31. Table: Seaport\_call\_fulfillAvailableOrders\_history

| Column                    | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp          | TIMESTAMP | 2023-02-16 01:43:37+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number             | INTEGER   | 39341011                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash         | VARCHAR   | 0xf215a56ad6a7ef821ba30120cceecc5b55ec4a8361ddee94d46c3d3f23f589ae                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index        | INTEGER   | 40                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address            | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address               | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status                    | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error                     | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders                    | VARCHAR   | 0x8012D9c4b80f35c558c005dAF3bbbA06b43349fB,0x0000000000000000000000000000000000000000,2,0xa9a6A36269 |                                                                                                                        |
| offerFulfillments         | VARCHAR   | 0,0                                                                                                  |                                                                                                                        |
| considerationFulfillments | VARCHAR   | 0,0,0,1                                                                                              |                                                                                                                        |
| fulfillerConduitKey       | VARCHAR   | 0x0000007b02230091a7ed01230072f7006a004d60a8d4e71d599b8104250f0000                                   |                                                                                                                        |
| maximumFulfilled          | VARCHAR   | 1                                                                                                    |                                                                                                                        |

## 32. Table: Seaport\_call\_fulfillBasicOrder\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-05-11 10:27:36+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 42570660                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x134c0f8338855d624edcbac537659c4c8070adbdecead5a20304859ed5b5d862                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 72                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| parameters         | VARCHAR   | 0x0000000000000000000000000000000000000000,0,1179075000000000000000,0x411Cb271ab1e63F81B786655837a8d |                                                                                                                        |

## 33. Table: Seaport\_call\_fulfillOrder\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2023-02-11 20:05:09+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 39184400                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x455ba13b76099d50dc4ed6b168ec7d165a8ddaf077afef9d3ba8b0634d65ea6b                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 62                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order               | VARCHAR   | 0xfFA233D21D2CC69041b7d40F1E2C594EB023C0aA,0x0000000000000000000000000000000000000000,2,0x41b4A2FABD |                                                                                                                        |
| fulfillerConduitKey | VARCHAR   | 0x0000000000000000000000000000000000000000000000000000000000000000                                   |                                                                                                                        |

## 34. Table: Seaport\_call\_getCounter\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-11 08:15:40+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37935638                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa95b71eb3b4373acdb2f455054c668c3df6ef3340a727006eba7a85634b3a32b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 53                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,0                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| offerer            | VARCHAR   | 0x21c8e614cd5c37765411066d2ec09912020c846f                         |                                                                                                                        |

## 35. Table: Seaport\_call\_getOrderHash\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-11 08:15:40+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37935638                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa95b71eb3b4373acdb2f455054c668c3df6ef3340a727006eba7a85634b3a32b                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 53                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,1                                                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| order              | VARCHAR   | 0x21C8e614CD5c37765411066D2ec09912020c846F,0x0000000000000000000000000000000000000000,2,0x5229cBE99c |                                                                                                                        |

## 36. Table: Seaport\_call\_getOrderStatus\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-03 18:01:12+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 39925665                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x710864ca080a792ad4260a0515db427bd4766e0769cc16d0a020ee0ae48ff16a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 37                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0,8                                                            | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| orderHash          | VARCHAR   | 0xb9175d48b40598ff8773c906e5f30af7e9eaea80935d80128011159723ad60ce |                                                                                                                        |

## 37. Table: Seaport\_call\_incrementCounter\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-10 06:29:10+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 44900333                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf6efdaf4c4216d1a008d3a85cb316e225f95d7940c374473c04ea49352635da1 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 54                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 38. Table: Seaport\_call\_information\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-11-16 14:12:19+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 35681352                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7489b1502ce802683f1f150f0e83864ca1eab3be7028eb9a7aefb27d52e62c14 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 114                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 39. Table: Seaport\_call\_matchAdvancedOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-04 00:53:57+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 45879600                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xda818840a0fbb3c5f92469f490ab4da643dafbb47758f8f8dca3d32ea81cf992                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                                                    | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,1                                                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| advancedOrders     | VARCHAR   | 0x865a0783DBb879680e341D4F94dfe610C6A32721,0xB2F6A627d2a673B81B6BE0f57e51C0541368199D,1,0x2791Bca1f2 |                                                                                                                        |
| criteriaResolvers  | VARCHAR   | 0,1,0,19055812547572553953948978016179019841614,,1,0,0,19055812547572553953948978016179019841614,    |                                                                                                                        |
| fulfillments       | VARCHAR   | 1,0,0,0,0,0,2,0,2,0,1,0                                                                              |                                                                                                                        |

## 40. Table: Seaport\_call\_matchOrders\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-12-22 21:22:17+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 37153137                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc161a61e0e1cab00d3b3e9b70f4a764137ec29826890289d235743b510d46a3d                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 69                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0xedC4F833E05feB31861f7aB2Cbaa18C5a3894fE6,0x0000000000000000000000000000000000000000,2,0x6C97eF47d6 |                                                                                                                        |
| fulfillments       | VARCHAR   | 0,0,0,2,1,0,0,0,1,0,0,1                                                                              |                                                                                                                        |

## 41. Table: Seaport\_call\_name\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-01-31 02:18:57+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 38726627                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xf384d1f21a6a2000d968b5e5514031c315b2f6a938ee07886b8b6b37d5947c78 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 49                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 42. Table: Seaport\_call\_validate\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-02-13 01:30:26+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 39228199                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x9503a652116f76af3f985192845cfc8424bfa7cb8e536865165a6a144ca0a375                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 57                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| orders             | VARCHAR   | 0x1Aa454AcF8ba9edB77C5034C61B10560da1EeC65,0x0000000000000000000000000000000000000000,3,0x622d8FeA46 |                                                                                                                        |

## 43. Table: Seaport\_event\_CounterIncremented\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-21 14:53:49+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 41789857                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe3de1bc0495288c2fcaae962e7505a8c6bb464b8fcbf212ef1ff4bb9f5f2c0fd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 778                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the contract that produced the log                |
| newCounter        | VARCHAR   | 2                                                                  |                                                              |
| offerer           | VARCHAR   | 0xb2e2ac8a02b0f0f68f3afc000d0e5be30e0c4830                         |                                                              |

## 44. Table: Seaport\_event\_OrderCancelled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-21 12:16:53+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 37097457                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe53de70f9f75301b72db1742f1b5fa1aaca7587185b63a13d842025a40ccc889 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 28                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0x02c6a905f53166e0dab7b79f6005b85d548b35038db584cf8f0265ded2268da7 |                                                              |
| offerer           | VARCHAR   | 0x000b332ceb516aec6826c61eeec143f0b4448f45                         |                                                              |
| zone              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |

## 45. Table: Seaport\_event\_OrderFulfilled\_history

| Column            | Type      | Example                                                                                       | Description                                                  |
| ----------------- | --------- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-29 16:13:30+00:00                                                                     | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 42103328                                                                                      | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd3a111ebf1376ccf4272066413e693c381ccae99a93a66ff5856d67d4961f99                            | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 305                                                                                           | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                                                    | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xc3445834eb68354e8af40842979b37347f1af73190f4bf9ae501e103f49491ea                            |                                                              |
| offerer           | VARCHAR   | 0x996d6f5a35ee45dda8fec5447fe4229d748d8eb5                                                    |                                                              |
| zone              | VARCHAR   | 0x137eb632876bffa557258aebd270b15180559d8e                                                    |                                                              |
| recipient         | VARCHAR   | 0x137eb632876bffa557258aebd270b15180559d8e                                                    |                                                              |
| offer             | VARCHAR   | 3,0xf16AB2D54E95CF9d8922a244C1c09107c3B96888,774,1                                            |                                                              |
| consideration     | VARCHAR   | 3,0x021a832F2aA9826BdF1a07bC41274bA4B4Fef68c,855,1,0x996d6F5a35eE45dda8fEc5447Fe4229d748d8EB5 |                                                              |

## 46. Table: Seaport\_event\_OrderValidated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-15 10:58:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 43936458                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d3685ee77987328b66d33a7800271c07802b05e12480effd8e25949d5831a5c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 292                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00000000006c3852cbef3e08e8df289169ede581                         | Address of the contract that produced the log                |
| orderHash         | VARCHAR   | 0xd2213795745d75f449b2d3e0f4b7b35ad019964525df2dbbe4cfcdf4a8a0aca8 |                                                              |
| offerer           | VARCHAR   | 0xf599e67c61ebfdfda254e8a5895297d1718910bb                         |                                                              |
| zone              | VARCHAR   | 0xac96e016f2543f8d92af50fe0bc9ee84e0b2867e                         |                                                              |
