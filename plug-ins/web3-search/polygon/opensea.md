# opensea

## 1. Table: ZeroExFeeWrapper\_call\_getExchange\_history

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

## 2. Table: ZeroExFeeWrapper\_call\_isOwner\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-07-18 21:30:01+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 30874671                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x494df7f6cd5b39ad28a56846accb054316f57756245fc8b0768905b63686f91a | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 40                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf715beb51ec8f63317d66f491e37e7bb048fcc2d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| owner              | VARCHAR   | 0x9b814233894cd227f561b78cc65891aa55c62ad2                         |                                                                                                                        |

## 3. Table: ZeroExFeeWrapper\_call\_matchOrders\_history

| Column              | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------- | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp    | TIMESTAMP | 2022-01-07 09:49:27+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number       | INTEGER   | 23436551                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash   | VARCHAR   | 0x931afc8a3202579725d410d0e4db4bbc71ea26eff4b97c3cd778170b8d4c9cc2                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index  | INTEGER   | 212                                                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address      | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address         | VARCHAR   | 0xf715beb51ec8f63317d66f491e37e7bb048fcc2d                                                           | Address of the called contract                                                                                         |
| status              | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error               | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| leftOrder           | VARCHAR   | 0x0E7209e529C3B7E5442c7D26E377280fCF353E44,0x0000000000000000000000000000000000000000,0xF715bEb51EC8 |                                                                                                                        |
| rightOrder          | VARCHAR   | 0xd170E556E94194da54F0Fa6aBd2C7F6a60b4cAcD,0x0000000000000000000000000000000000000000,0xF715bEb51EC8 |                                                                                                                        |
| leftSignature       | VARCHAR   | 0x1c3eb033c5d176f0f430fb4e0b20779225dced4e8075fa4e56ea3cf7b1001141877f46071536f3082c7c67cb424eb03a3c |                                                                                                                        |
| rightSignature      | VARCHAR   | 0x1b102932b5a1b0fd34f849fd12eb2cedaccc0d847d9404110c9281cf1ebb06f3c472fecab29c758a4ca5ed105da90ed986 |                                                                                                                        |
| feeData             | VARCHAR   | 0x5b3256965e7C3cF26E11FCAf296DfC8807C01073,225000000000,0xd170E556E94194da54F0Fa6aBd2C7F6a60b4cAcD,4 |                                                                                                                        |
| paymentTokenAddress | VARCHAR   | 0x7ceb23fd6bc0add59e62ac25578270cff1b9f619                                                           |                                                                                                                        |

## 4. Table: ZeroExFeeWrapper\_call\_proxyCall\_history

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
| target             | VARCHAR   |                                                                                                                        |             |
| callData           | VARCHAR   |                                                                                                                        |             |

## 5. Table: ZeroExFeeWrapper\_call\_setExchange\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-07-22 16:14:40+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17149990                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x936fbf06d16c63fdfb08598a307d0e9e92a1780d555c30f3056f0f4176052f15 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 88                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf715beb51ec8f63317d66f491e37e7bb048fcc2d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| exchange           | VARCHAR   | 0xfede379e48c873c75f3cc0c81f7c784ad730a8f7                         |                                                                                                                        |

## 6. Table: ZeroExFeeWrapper\_call\_setOwner\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-06-28 21:33:16+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16262818                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x27c413c04c63dfd5d2c2742a14612b3ecdc15438f12659c4c173fbb44d1c6d38 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 97                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xf715beb51ec8f63317d66f491e37e7bb048fcc2d                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| owner              | VARCHAR   | 0x9b814233894cd227f561b78cc65891aa55c62ad2                         |                                                                                                                        |
| isOwner            | VARCHAR   | true                                                               |                                                                                                                        |
