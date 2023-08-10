# uniswap

## 1. Table: UniswapV3Factory\_event\_FeeAmountEnabled\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-18 00:59:07+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14799808                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xef9f126b2d52391e80ca3b0d42d4112866668df2930fb9f48f75a53cf8cd08b9 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| fee               | VARCHAR   | 100                                                                |                                                              |
| tickSpacing       | VARCHAR   | 1                                                                  |                                                              |

## 2. Table: UniswapV3Factory\_event\_OwnerChanged\_history

| Column            | Type      | Example                                                      | Description |
| ----------------- | --------- | ------------------------------------------------------------ | ----------- |
| block\_timestamp  | TIMESTAMP | Timestamp of the block where this event was emitted          |             |
| block\_number     | INTEGER   | The block number where this event was emitted                |             |
| transaction\_hash | VARCHAR   | Hash of the transactions in which this event was emitted     |             |
| log\_index        | INTEGER   | Integer of the log index position in the block of this event |             |
| contract\_address | VARCHAR   | Address of the contract that produced the log                |             |
| oldOwner          | VARCHAR   |                                                              |             |
| newOwner          | VARCHAR   |                                                              |             |

## 3. Table: UniswapV3Factory\_event\_PoolCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-20 07:11:48+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 2458641                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xb368cf13b18e043c2113ffa6a0c1cb7d0336db1b7b52c84824d3359421cb5a32 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1f98431c8ad98523631ae4a59f267346ea31f984                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0xb24f50dd9918934ab2228be7a097411ca28f6c14                         |                                                              |
| token1            | VARCHAR   | 0xc84da6c8ec7a57cd10b939e79eaf9d2d17834e04                         |                                                              |
| fee               | VARCHAR   | 3000                                                               |                                                              |
| tickSpacing       | VARCHAR   | 60                                                                 |                                                              |
| pool              | VARCHAR   | 0x4d7c361d7758107bdb88e4d36ef5ac5d85f8c6fa                         |                                                              |

## 4. Table: UniswapV3Pool\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-10-24 18:07:13+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 31221816                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x324008864905f7e8e08ce84f7618462f6b6afbccc0719556e6327d5ee8ac06d6 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4a5a2a152e985078e1a4aa9c3362c412b7dd0a86                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| tickLower         | VARCHAR   | 800                                                                |                                                              |
| tickUpper         | VARCHAR   | 820                                                                |                                                              |
| amount            | VARCHAR   | 26327982896655433947                                               |                                                              |
| amount0           | VARCHAR   | 0                                                                  |                                                              |
| amount1           | VARCHAR   | 27414727826323474                                                  |                                                              |

## 5. Table: UniswapV3Pool\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-02 18:27:47+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107701045                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x5d69e49a61d44725c8aeb30b5ca8768314e90c65add2f036b7199e47dfedf7c5 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x000eca51aaf0ca8dc92b13a93d897039d7802f7d                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| owner             | VARCHAR   | 0xc36442b4a4522e871399cd717abdd847ab11fe88                         |                                                              |
| tickLower         | VARCHAR   | -295260                                                            |                                                              |
| tickUpper         | VARCHAR   | -275580                                                            |                                                              |
| amount            | VARCHAR   | 286905336845462767                                                 |                                                              |
| amount0           | VARCHAR   | 463019097371260373314473                                           |                                                              |
| amount1           | VARCHAR   | 0                                                                  |                                                              |

## 6. Table: UniswapV3Pool\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-01-30 16:58:16+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 3016115                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9378325b14921d67f9136bee42d531848e332a9509110ae97816632fda55c901 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 2                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x34f7ffe0ab212476a878f6277568f55d6927b251                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x68b3465833fb72a70ecdf485e0e4c7bd8665fc45                         |                                                              |
| recipient         | VARCHAR   | 0xf43c95f4ea8d69c1251399322af97973f6211a2d                         |                                                              |
| amount0           | VARCHAR   | 150000000000000000                                                 |                                                              |
| amount1           | VARCHAR   | -16130149523183650466                                              |                                                              |
| sqrtPriceX96      | VARCHAR   | 811870041593848068805372698482                                     |                                                              |
| liquidity         | VARCHAR   | 50737156889573267762                                               |                                                              |
| tick              | VARCHAR   | 46542                                                              |                                                              |
