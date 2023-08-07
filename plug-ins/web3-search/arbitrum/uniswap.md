# uniswap

## 1. Table: UniswapV3Factory\_event\_FeeAmountEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-18 01:52:33+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 61952847                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x39722d69370c7332a0ba49c30ed834399933c118a6296a60c31c62b69e29dbcc | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 100                                                                |                                                              |
| tickSpacing       | VARCHAR   | 1                                                                  |                                                              |

## 2. Table: UniswapV3Factory\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-12-26 11:02:52+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 48972827                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x7d42d3755ada7791d93dec1649d2aabc4a9dbb3abde46c04ae89d8983be55ee4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| oldOwner          | VARCHAR   | 0x1a9c8182c09f50c8318d769245bea52c32be35bc                         |                                                              |
| newOwner          | VARCHAR   | 0x2bad8182c09f50c8318d769245bea52c32be46cd                         |                                                              |

## 3. Table: UniswapV3Factory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-15 04:21:36+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30176752                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x51684d3965fe5aae7d64f9f4e0f95e995fceb190df9b1ad55d1d07736a5d91c4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x82af49447d8a07e3bd95bd0d56f35241523fbab1                         |                                                              |
| token1            | VARCHAR   | 0xeeeeeb57642040be42185f49c52f7e9b38f8eeee                         |                                                              |
| fee               | VARCHAR   | 500                                                                |                                                              |
| tickSpacing       | VARCHAR   | 10                                                                 |                                                              |
| pool              | VARCHAR   | 0x27558e1a615a78e2076e33eda9a643750197180e                         |                                                              |

## 4. Table: UniswapV3Pool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-04 00:06:00+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 57810663                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xf9439e003fabf8629b411fd77d4eb180fa3b1faa5dd1c138e343fa4efaa74096 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x00717a5af000bb6d1b7ba2dabf89abd44e8aa059                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| tickLower         | VARCHAR   | -322380                                                            |                                                              |
| tickUpper         | VARCHAR   | -69080                                                             |                                                              |
| amount            | VARCHAR   | 31317993113278                                                     |                                                              |
| amount0           | VARCHAR   | 9278046283234272                                                   |                                                              |
| amount1           | VARCHAR   | 95515223053                                                        |                                                              |

## 5. Table: UniswapV3Pool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-02-04 15:19:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 5420519                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x1c5ced91ea26eec5ed70a5df1e48d93998819cae62046ee710464bbf4c46138b | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x149e36e72726e0bcea5c59d40df2c43f60f5a22d                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| owner             | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| tickLower         | VARCHAR   | 256380                                                             |                                                              |
| tickUpper         | VARCHAR   | 256500                                                             |                                                              |
| amount            | VARCHAR   | 6886771157900201                                                   |                                                              |
| amount0           | VARCHAR   | 111660714                                                          |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: UniswapV3Pool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-03-09 01:07:20+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7605013                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xa48a5d3a015b86bf23f78d0f166a6010f522e2de61d5cfd7566de9b498e03cba | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 3                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x08e0b47588e1ac22bc0f8b4afaa017aaf273f85e                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x68b3465833fb72a70ecdf485e0e4c7bd8665fc45                         |                                                              |
| recipient         | VARCHAR   | 0x3e250a0ae9ff6005ea9dab67b5bea09948a0a1df                         |                                                              |
| amount0           | VARCHAR   | 4567651868610951603797                                             |                                                              |
| amount1           | VARCHAR   | -780159925649068978513                                             |                                                              |
| sqrtPriceX96      | VARCHAR   | 32788363919472729082666245164                                      |                                                              |
| liquidity         | VARCHAR   | 7108469728846259933783435                                          |                                                              |
| tick              | VARCHAR   | -17647                                                             |                                                              |
