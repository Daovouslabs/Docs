# pancakeswap

## 1. Table: UniswapV3Factory\_event\_FeeAmountEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-01 00:16:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16950686                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x157ee31f54d40ab46d6096de3751a86c55e659147322edcec582ec77ff90c03d | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 281                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0bfbcf9fa4f9c56b0f40a671ad40e0805a091865                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 100                                                                |                                                              |
| tickSpacing       | VARCHAR   | 1                                                                  |                                                              |

## 2. Table: UniswapV3Factory\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-24 17:11:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17330451                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x45008049c67ecd4dfdd54b9dc519a1952a2253c20890394d4f2ea4dadbce2512 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 306                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0bfbcf9fa4f9c56b0f40a671ad40e0805a091865                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x21835332cbdf1b3530fae9f6cd66feb9477dfc02                         |                                                              |
| newOwner          | VARCHAR   | 0x0c0388e4bbf121a06ea531d2244e93e044964879                         |                                                              |

## 3. Table: UniswapV3Factory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 19:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17473193                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xdbac8624daa7080d46b5319c3692fddceb65b04a3a26e609dc50d83e53314fc4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 178                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0bfbcf9fa4f9c56b0f40a671ad40e0805a091865                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0xc02aaa39b223fe8d0a0e5c4f27ead9083c756cc2                         |                                                              |
| token1            | VARCHAR   | 0xe9a64497f4723ba0e884be625c6450f811a4304b                         |                                                              |
| fee               | VARCHAR   | 2500                                                               |                                                              |
| tickSpacing       | VARCHAR   | 50                                                                 |                                                              |
| pool              | VARCHAR   | 0x36b000d51f4d2dd9817e853e4bda8a096fe6ca0c                         |                                                              |

## 4. Table: UniswapV3Pool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-09 00:38:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17652648                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x429bf2f47351816a15cdf8e86c0ba17a00cd3fb6551bccabd704d38db81c916e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 345                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x04c8577958ccc170eb3d2cca76f9d51bc6e42d8f                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x46a15b0b27311cedf172ab29e4f4766fbe7f4364                         |                                                              |
| tickLower         | VARCHAR   | -2                                                                 |                                                              |
| tickUpper         | VARCHAR   | 0                                                                  |                                                              |
| amount            | VARCHAR   | 661522903992176                                                    |                                                              |
| amount0           | VARCHAR   | 14482161255                                                        |                                                              |
| amount1           | VARCHAR   | 51663831614                                                        |                                                              |

## 5. Table: UniswapV3Pool\_event\_CollectProtocol\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-01 03:37:23+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16951677                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x73dd8eb4262f274cb4da4350d53a314f50ec787d98b1ded03011f3a89af9adf8 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 99                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xb078bf211e330b5f95b7114ae845188cc36b795d                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0bfbcf9fa4f9c56b0f40a671ad40e0805a091865                         |                                                              |
| recipient         | VARCHAR   | 0x40492810a7de793eef0dfb3a58338fdfea511047                         |                                                              |
| amount0           | VARCHAR   | 3000000000000                                                      |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: UniswapV3Pool\_event\_Collect\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-02 07:40:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17391639                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x717a5819ca1dabf56097667dfc375ff9c552874b7d9d64d4b3fbac1883c918ef | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 288                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x04c8577958ccc170eb3d2cca76f9d51bc6e42d8f                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0x46a15b0b27311cedf172ab29e4f4766fbe7f4364                         |                                                              |
| recipient         | VARCHAR   | 0x0020c5222a24e4a96b720c06b803fb8d34adc0af                         |                                                              |
| tickLower         | VARCHAR   | -12                                                                |                                                              |
| tickUpper         | VARCHAR   | 8                                                                  |                                                              |
| amount0           | VARCHAR   | 725896993805                                                       |                                                              |
| amount1           | VARCHAR   | 749999999999                                                       |                                                              |

## 7. Table: UniswapV3Pool\_event\_Flash\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| sender            | VARCHAR   |                                                              |             |
| recipient         | VARCHAR   |                                                              |             |
| amount0           | VARCHAR   |                                                              |             |
| amount1           | VARCHAR   |                                                              |             |
| paid0             | VARCHAR   |                                                              |             |
| paid1             | VARCHAR   |                                                              |             |

## 8. Table: UniswapV3Pool\_event\_IncreaseObservationCardinalityNext\_history

| Column                        | Type      | Example                                                            | Description                                                  |
| ----------------------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp              | TIMESTAMP | 2023-06-12 22:53:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number                 | INTEGER   | 17467060                                                           | The block number where this event was emitted                |
| transaction\_hash             | VARCHAR   | 0x1ad1bb14e68776ff85b71add3fe6b9c4ea24a2197e669ab49b59e6b9f30b14c7 | Hash of the transactions in which this event was emitted     |
| log\_index                    | INTEGER   | 125                                                                | Integer of the log index position in the block of this event |
| contract\_address             | VARCHAR   | 0x1ac1a8feaaea1900c4166deeed0c11cc10669d36                         | Address of the contract that produced the log                |
| observationCardinalityNextOld | VARCHAR   | 1                                                                  |                                                              |
| observationCardinalityNextNew | VARCHAR   | 11                                                                 |                                                              |

## 9. Table: UniswapV3Pool\_event\_Initialize\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-01 14:37:35+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 16954933                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac348744622ae1d945e5079678966c9402ef4a6be4c43d1399a151f6a7f8fb13 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 232                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1ac1a8feaaea1900c4166deeed0c11cc10669d36                         | Address of the contract that produced the log                |
| sqrtPriceX96      | VARCHAR   | 1856732409091090553720748176553929                                 |                                                              |
| tick              | VARCHAR   | 201250                                                             |                                                              |

## 10. Table: UniswapV3Pool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-13 23:28:11+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17474337                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x72b3a43226f1b272092ca5fd28935e0399a03edf2e77f53260676e4c9da0e973 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 200                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x04c8577958ccc170eb3d2cca76f9d51bc6e42d8f                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x46a15b0b27311cedf172ab29e4f4766fbe7f4364                         |                                                              |
| owner             | VARCHAR   | 0x46a15b0b27311cedf172ab29e4f4766fbe7f4364                         |                                                              |
| tickLower         | VARCHAR   | 0                                                                  |                                                              |
| tickUpper         | VARCHAR   | 3                                                                  |                                                              |
| amount            | VARCHAR   | 11459437558924028                                                  |                                                              |
| amount0           | VARCHAR   | 1007230692707                                                      |                                                              |
| amount1           | VARCHAR   | 711514276785                                                       |                                                              |

## 11. Table: UniswapV3Pool\_event\_SetFeeProtocol\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| feeProtocol0Old   | VARCHAR   |                                                              |             |
| feeProtocol1Old   | VARCHAR   |                                                              |             |
| feeProtocol0New   | VARCHAR   |                                                              |             |
| feeProtocol1New   | VARCHAR   |                                                              |             |

## 12. Table: UniswapV3Pool\_event\_Swap\_history

| Column             | Type      | Example                                                            | Description                                                  |
| ------------------ | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp   | TIMESTAMP | 2023-07-24 09:50:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number      | INTEGER   | 17762183                                                           | The block number where this event was emitted                |
| transaction\_hash  | VARCHAR   | 0x6887c14720a617db070c3d6c3d36f9d908d9038e31f6a1e44023f30538d227ea | Hash of the transactions in which this event was emitted     |
| log\_index         | INTEGER   | 9                                                                  | Integer of the log index position in the block of this event |
| contract\_address  | VARCHAR   | 0x04c8577958ccc170eb3d2cca76f9d51bc6e42d8f                         | Address of the contract that produced the log                |
| sender             | VARCHAR   | 0x1b81d678ffb9c0263b24a97847620c99d213eb14                         |                                                              |
| recipient          | VARCHAR   | 0x80d4230c0a68fc59cb264329d3a717fcaa472a13                         |                                                              |
| amount0            | VARCHAR   | 332920031530                                                       |                                                              |
| amount1            | VARCHAR   | -332878930400                                                      |                                                              |
| sqrtPriceX96       | VARCHAR   | 79226913292880927676830085110                                      |                                                              |
| liquidity          | VARCHAR   | 41219032828910933                                                  |                                                              |
| tick               | VARCHAR   | -1                                                                 |                                                              |
| protocolFeesToken0 | VARCHAR   | 10986361                                                           |                                                              |
| protocolFeesToken1 | VARCHAR   | 0                                                                  |                                                              |
