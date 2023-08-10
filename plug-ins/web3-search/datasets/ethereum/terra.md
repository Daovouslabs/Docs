# terra

## 1. Table: Minter\_call\_addSigner\_history

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
| \_signer           | VARCHAR   |                                                                                                                        |             |
| \_signatures       | VARCHAR   |                                                                                                                        |             |

## 2. Table: Minter\_call\_changeThreshold\_history

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
| \_newThreshold     | VARCHAR   |                                                                                                                        |             |
| \_signatures       | VARCHAR   |                                                                                                                        |             |

## 3. Table: Minter\_call\_collectOwnership\_history

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
| \_token            | VARCHAR   |                                                                                                                        |             |
| \_to               | VARCHAR   |                                                                                                                        |             |
| \_signatures       | VARCHAR   |                                                                                                                        |             |

## 4. Table: Minter\_call\_mint\_history

| Column             | Type      | Example                                                                                              | Description                                                                                                            |
| ------------------ | --------- | ---------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-03-09 00:46:23+00:00                                                                            | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 16787178                                                                                             | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xeb684b1aa6f9cd6afb1fe5ff40ea06abd78d5921c5956cd152e8b33d0941b8e4                                   | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 15                                                                                                   | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                                                 | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0x9123077acafb3d743c68418304b2a11566cc1175                                                           | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                                                    | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                                                 | Error in case input parsing failed                                                                                     |
| \_token            | VARCHAR   | 0x09a3ecafa817268f77be1283176b946c4ff2e608                                                           |                                                                                                                        |
| \_to               | VARCHAR   | 0x19d6fb8e6f61986bdbceda0f9cb8af60048465a4                                                           |                                                                                                                        |
| \_amount           | VARCHAR   | 7784489903000000000000                                                                               |                                                                                                                        |
| \_txHash           | VARCHAR   | 0x841b0641f63dda714c2006ae869f234dc6333732c98cce6e2f4e6fdd33695aa3                                   |                                                                                                                        |
| \_signatures       | VARCHAR   | 0x9e9f524dd1bc78c852d84a29c54bb7d7cfe0ea753f60eee59ac4ad13c59d8a31485ed0e548ac1bf26603b73beb9f8cf30f |                                                                                                                        |

## 5. Table: Minter\_call\_removeSigner\_history

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
| \_signer           | VARCHAR   |                                                                                                                        |             |
| \_signatures       | VARCHAR   |                                                                                                                        |             |

## 6. Table: WrappedUST\_call\_allowance\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-08-04 01:49:11+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17838446                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x14d1e0b7aee5c57e4b6897263a76158b2313e411d349ab4d44665c3e9176b7a5 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 69                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 1,0,0                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| owner              | VARCHAR   | 0x74de5d4fcbf63e00296fd95d33236b9794016631                         |                                                                                                                        |
| spender            | VARCHAR   | 0x1111111254eeb25477b68fb85ed929f73a960582                         |                                                                                                                        |

## 7. Table: WrappedUST\_call\_approve\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-11 00:20:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17666777                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x35fbc90d23e050674aa05db8d2522d80f3d68c3d2766cc68e06d5faf41a1e1da | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 45                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| spender            | VARCHAR   | 0xe66b31678d6c16e9ebf358268a790b763c133750                         |                                                                                                                        |
| amount             | VARCHAR   | 0                                                                  |                                                                                                                        |

## 8. Table: WrappedUST\_call\_balanceOf\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-29 10:51:09+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14678741                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xc5dea30d1cc864ee2c7e0dcba8cff818424117a030cb152039c83f9b08eba56b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 262                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,0,0                                                              | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| account            | VARCHAR   | 0x48b078edcf15e618113718547cfae38129b32023                         |                                                                                                                        |

## 9. Table: WrappedUST\_call\_burn\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-02-11 03:27:44+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11832836                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x707fd5395a205e125e875eb76129d7c0dd64f0909308651a6f26dbac66f3051f | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 8                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| amount             | VARCHAR   | 16134809169000000000000                                            |                                                                                                                        |
| to                 | VARCHAR   | 0x01a1455376ccd1626ca7c3dcf3cfc1c66503ba4a000000000000000000000000 |                                                                                                                        |

## 10. Table: WrappedUST\_call\_decimals\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-10-24 07:25:35+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 15816458                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x5b4d055599f4dc668d7471b11fba2a962e6234f49d17777e6b88b6c0201a8f82 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 113                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,3,0,5,4                                                          | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 11. Table: WrappedUST\_call\_decreaseAllowance\_history

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
| spender            | VARCHAR   |                                                                                                                        |             |
| subtractedValue    | VARCHAR   |                                                                                                                        |             |

## 12. Table: WrappedUST\_call\_increaseAllowance\_history

| Column             | Type      | Example                                                                        | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-24 11:53:59+00:00                                                      | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17762792                                                                       | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x7625f4087335070a4147de18bab086a9172e79a006cde79110cf87af88e3651c             | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 23                                                                             | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                                           | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                                     | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                              | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                                           | Error in case input parsing failed                                                                                     |
| spender            | VARCHAR   | 0x0000553f880ffa3728b290e04e819053a3590000                                     |                                                                                                                        |
| addedValue         | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                                                                                        |

## 13. Table: WrappedUST\_call\_mint\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-03-09 17:57:15+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14354044                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xd8dac0b3b0c6c5fe751bbe69b9d1c17f48c8a7847c1e849f12ed7787751ffee3 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 2                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| account            | VARCHAR   | 0x8f8a829bf3253a7c42e6aaccc65abdd262d4e672                         |                                                                                                                        |
| amount             | VARCHAR   | 9000000000000000000                                                |                                                                                                                        |

## 14. Table: WrappedUST\_call\_name\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-11-10 10:57:39+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 13588107                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xbf9a4c2fa11dfba86844a19ccbc0b117f137eb8d1e475d7712fd5de8a000675d | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 103                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 15. Table: WrappedUST\_call\_owner\_history

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

## 16. Table: WrappedUST\_call\_renounceOwnership\_history

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

## 17. Table: WrappedUST\_call\_symbol\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2022-04-25 18:01:07+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 14655246                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x46ed4f0764987c2b8cbe683ec14b3b2b3932396b56561ae95415ad899e4a6d3b | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 114                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0,2                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 18. Table: WrappedUST\_call\_totalSupply\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-02-02 16:41:06+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 11777946                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x48a11559e2d9f39c727c77356f71c1fc42bb519c0d1e4a3088cb705b59284e14 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 166                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 3                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |

## 19. Table: WrappedUST\_call\_transferFrom\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-04-19 23:41:20+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12273520                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x2bab78c5ea690fdfc504734ffb09953b7c20817d570f67f3661639624f84dc31 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 90                                                                 | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 0                                                                  | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| sender             | VARCHAR   | 0xca748cb3e3de6ceab581db13bb9362d4d55353b9                         |                                                                                                                        |
| recipient          | VARCHAR   | 0x42d4e90ff4068abe7bc4eab838c7de1d2f5998a3                         |                                                                                                                        |
| amount             | VARCHAR   | 278027109957204924438443                                           |                                                                                                                        |

## 20. Table: WrappedUST\_call\_transferOwnership\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2021-03-22 06:41:10+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 12087042                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0x14aaf8f441326e4bc1fe2b6369255d0d6b961f685e18e2e8665f8361dfff4221 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 135                                                                | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | None                                                               | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| newOwner           | VARCHAR   | 0x9123077acafb3d743c68418304b2a11566cc1175                         |                                                                                                                        |

## 21. Table: WrappedUST\_call\_transfer\_history

| Column             | Type      | Example                                                            | Description                                                                                                            |
| ------------------ | --------- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------- |
| block\_timestamp   | TIMESTAMP | 2023-07-16 15:42:59+00:00                                          | Timestamp of the block where this event was emitted                                                                    |
| block\_number      | INTEGER   | 17706812                                                           | The block number where this event was emitted                                                                          |
| transaction\_hash  | VARCHAR   | 0xa55372628ef2be4ba13a58091c0bc3fa3791a30b22094b6b95cb853a47047433 | Hash of the transactions in which this event was emitted                                                               |
| transaction\_index | INTEGER   | 0                                                                  | Integer of the transactions index position in the block                                                                |
| trace\_address     | VARCHAR   | 4,0                                                                | Comma separated list of trace address in call tree                                                                     |
| to\_address        | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the called contract                                                                                         |
| status             | INTEGER   | 1                                                                  | Either 1 (success) or 0 (failure, due to any operation that can cause the call itself or any top-level call to revert) |
| error              | VARCHAR   | None                                                               | Error in case input parsing failed                                                                                     |
| recipient          | VARCHAR   | 0x8b00ee8606cc70c2dce68dea0cefe632cca0fb7b                         |                                                                                                                        |
| amount             | VARCHAR   | 6822180789900377167796                                             |                                                                                                                        |

## 22. Table: WrappedUST\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-12 13:56:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17464412                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x308c4f80c5131a404ebbf56410be2c51a4b238522e16d506ddef906bdee75903 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 69                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xa7dfd988bc054527de78da9c8530e2a6aef82597                         |                                                              |
| spender           | VARCHAR   | 0x68b3465833fb72a70ecdf485e0e4c7bd8665fc45                         |                                                              |
| value             | VARCHAR   | 0                                                                  |                                                              |

## 23. Table: WrappedUST\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-08-02 00:39:08+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12942844                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x87cd5e2de70e35bcc3a1b08d6ba01827dae19dcad26d2977a0e615a27af10ffc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 240                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the contract that produced the log                |
| \_sender          | VARCHAR   | 0x037a9c5092b77f6fb566f32c8272286c62fdf3b2                         |                                                              |
| \_to              | VARCHAR   | 0x8b8075e4e768b3115485407f4f4926adb0be1ee3000000000000000000000000 |                                                              |
| amount            | VARCHAR   | 11425331166000000000000                                            |                                                              |

## 24. Table: WrappedUST\_event\_OwnershipTransferred\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-03-22 06:41:10+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 12087042                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14aaf8f441326e4bc1fe2b6369255d0d6b961f685e18e2e8665f8361dfff4221 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 119                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the contract that produced the log                |
| previousOwner     | VARCHAR   | 0xc6821958f8d73ad0819502c35e383db8d3077ea2                         |                                                              |
| newOwner          | VARCHAR   | 0x9123077acafb3d743c68418304b2a11566cc1175                         |                                                              |

## 25. Table: WrappedUST\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-02-22 08:34:57+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 11905783                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfd157300a7697feda27448778f0ca784ab3dd1c0da3fef445b8f519f48176b85 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 154                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xa47c8bf37f92abed4a126bda807a7b7498661acd                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0x816958b4110640be3dd4139afe3389b1828445ec                         |                                                              |
| value             | VARCHAR   | 64535400000000000000000                                            |                                                              |
