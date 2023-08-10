# velodrome

## 1. Table: PairFactory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-02-13 20:35:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 74162194                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x29497e8dbbf95e52499c3267f518a581c32c841f279c174ca6d8866bd7670b62 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x25cbddb98b35ab1ff77413456b31ec81a6b6b746                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x2513486f18eee1498d7b6281f668b955181dd0d9                         |                                                              |
| token1            | VARCHAR   | 0x46f21fda29f1339e0ab543763ff683d399e393ec                         |                                                              |
| stable            | VARCHAR   | true                                                               |                                                              |
| pair              | VARCHAR   | 0xc93f7825523ee5cea2d659843297002542732824                         |                                                              |
| unnamedField0     | VARCHAR   | 458                                                                |                                                              |

## 2. Table: Pair\_event\_Approval\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-08-03 00:31:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17348832                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x83d25f2eb2b41db05d5f36872890fabad81bfa7e32aca5d8c45ae76ba4c87a06 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xec24eb97cec2f0f6a2d61254990b0f163bbbfe1d                         | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xc290067ef915116e31ce171097d4697da36c8c43                         |                                                              |
| spender           | VARCHAR   | 0x00acfd3420cd652500f5ba1b90ac7c19f694c5c3                         |                                                              |
| amount            | VARCHAR   | 8000000000000000000000000000                                       |                                                              |

## 3. Table: Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-30 22:07:01+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107578022                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x0aa06aaa6aff6bcb227ce2ebe2f13421331944298f5b0ce3177f80a46fcba7ff | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 39                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x16e7e0960a74b0ea3e61118a0c0eae8f83d43d7c                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x9b50b06b81f033ca86d70f0a44f30bd7e0155737                         |                                                              |
| amount0           | VARCHAR   | 512794718879665227488                                              |                                                              |
| amount1           | VARCHAR   | 845159770504519529142                                              |                                                              |
| to                | VARCHAR   | 0xd211b9d5da830e29ca1ec9be1d1723b91fa81e3f                         |                                                              |

## 4. Table: Pair\_event\_Claim\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-10 20:29:05+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 106711084                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x68bd91d51e8e806a22d16c228e9570adc2bafac2c5ed899056b3c48e3967b48e | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 16                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x47029bc8f5cbe3b464004e87ef9c9419a48018cd                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xd3217d8dcf0324442adca35aa9b2f45aa342b6e7                         |                                                              |
| recipient         | VARCHAR   | 0xd3217d8dcf0324442adca35aa9b2f45aa342b6e7                         |                                                              |
| amount0           | VARCHAR   | 0                                                                  |                                                              |
| amount1           | VARCHAR   | 38                                                                 |                                                              |

## 5. Table: Pair\_event\_Fees\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-12 03:43:30+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14304213                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x573f86f27dd675ad2e7bd0900a7bf70eba380d24af4377b86412cad66b816277 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 12                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xadf902b11e4ad36b227b84d856b229258b0b0465                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x0d7ba80188b908e110757338da125b28fa4c2a6b                         |                                                              |
| amount0           | VARCHAR   | 0                                                                  |                                                              |
| amount1           | VARCHAR   | 1182                                                               |                                                              |

## 6. Table: Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-08-06 16:32:55+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 107870399                                                          | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe93779f6ff766c15f92fe94a94356379f91ad7003696897fdba251c15a70c9b1 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 37                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3905870e647c97cb9c8d99db24384f480531b5b9                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x9c12939390052919af3155f41bf4160fd3666a6f                         |                                                              |
| amount0           | VARCHAR   | 753175595956069                                                    |                                                              |
| amount1           | VARCHAR   | 916579524581429498                                                 |                                                              |

## 7. Table: Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-04-22 21:45:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 93328640                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xe5581881957d4905e39ad4d4268bd8fbedaf2d0c635c6a32994d7b8ad29a09e4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 7                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x47029bc8f5cbe3b464004e87ef9c9419a48018cd                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0xa132dab612db5cb9fc9ac426a0cc215a3423f9c9                         |                                                              |
| amount0In         | VARCHAR   | 100000000000000000000                                              |                                                              |
| amount1In         | VARCHAR   | 0                                                                  |                                                              |
| amount0Out        | VARCHAR   | 0                                                                  |                                                              |
| amount1Out        | VARCHAR   | 228564400                                                          |                                                              |
| to                | VARCHAR   | 0xd8b73d634bd6f6d7d1e992551ab7e06e4c21b171                         |                                                              |

## 8. Table: Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-07-12 00:10:40+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 14296538                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x10af2da00368ef818c5e79c035bc9a7447e84585038380b85e9dbcfca8b7c93c | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x4f7ebc19844259386dbddb7b2eb759eefc6f8353                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 2170075504789                                                      |                                                              |
| reserve1          | VARCHAR   | 2373791348968672998671340                                          |                                                              |

## 9. Table: Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-09-13 00:30:59+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 22903133                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xac8bb60d37b903fad97fb8791eaf2cdd6104f3ec9c7a9e787d19070d336001ea | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 20                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x06141423dcf1a5a4c137039063ac873cdc1e363a                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0x0000000000000000000000000000000000000000                         |                                                              |
| to                | VARCHAR   | 0xa77ae94fd4a89b787d638325f79294353cc23859                         |                                                              |
| amount            | VARCHAR   | 61948336766764536                                                  |                                                              |
