# sushiswap

## 1. Table: UniswapV2Factory\_event\_PairCreated\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2022-04-19 18:54:44+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 17089048                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xbb885247ba0ea1f533463aab0a8065d77eee7600b59fdcc1942b0baf45638056 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 377                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0xc35dadb65012ec5796536bd9864ed8773abc74c4                         | Address of the contract that produced the log                |
| token0            | VARCHAR   | 0x9e5a4e0585ff34acb89f4ef161b25ebe3977e35c                         |                                                              |
| token1            | VARCHAR   | 0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c                         |                                                              |
| pair              | VARCHAR   | 0x7412a030c9f7b6eaf82e47d3e89281b499fcb5fa                         |                                                              |
| \_uint            | VARCHAR   | 1423                                                               |                                                              |

## 2. Table: UniswapV2Pair\_event\_Approval\_history

| Column            | Type      | Example                                                                        | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-03-25 23:58:19+00:00                                                      | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 26784650                                                                       | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x14a2c75a9b8aa28f88b5e4bf897905345e3d18aab4c848b1afd119f9038a1baf             | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 18                                                                             | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x2905817b020fd35d9d09672946362b62766f0d69                                     | Address of the contract that produced the log                |
| owner             | VARCHAR   | 0xde62947329085292a28ec4b694f637ea259daad0                                     |                                                              |
| spender           | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                                     |                                                              |
| value             | VARCHAR   | 115792089237316195423570985008687907853269984665640564039457584007913129639935 |                                                              |

## 3. Table: UniswapV2Pair\_event\_Burn\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-06-19 18:16:41+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 29244639                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x6103ab29ef1cc3b832c4ee324ec2184743e9fa026acee530e3e370da3bbdee79 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 84                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x8cc8605f2b54852b54a77b7e9711bb1156581ee9                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0           | VARCHAR   | 156447534629                                                       |                                                              |
| amount1           | VARCHAR   | 1005905100553283226                                                |                                                              |
| to                | VARCHAR   | 0xe91d93f713946f7742c10df35ffec463c842dead                         |                                                              |

## 4. Table: UniswapV2Pair\_event\_Mint\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-07-25 17:30:24+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 30277483                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xc34e98e8926d9516cdb7b99802315523a790320a6106eaeafa4dd9873cb310d4 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 1821                                                               | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1aaae656642523f5e847c2afbf317d7b6073b965                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x1b02da8cb0d097eb8d57a175b88c7d8b47997506                         |                                                              |
| amount0           | VARCHAR   | 999999999999999                                                    |                                                              |
| amount1           | VARCHAR   | 725608416436409                                                    |                                                              |

## 5. Table: UniswapV2Pair\_event\_Swap\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-05-11 17:37:28+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 28123041                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x9040d4c57d23fd4194721debd118aae92109f6d0d4ab254f917b51af937c8531 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 216                                                                | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x3d41ced5764340265d58ea4996f909eb05e25fdb                         | Address of the contract that produced the log                |
| sender            | VARCHAR   | 0x000000000003a3c2878a1df56a486c9683220456                         |                                                              |
| amount0In         | VARCHAR   | 0                                                                  |                                                              |
| amount1In         | VARCHAR   | 141491011442345836                                                 |                                                              |
| amount0Out        | VARCHAR   | 154969894152396848481                                              |                                                              |
| amount1Out        | VARCHAR   | 0                                                                  |                                                              |
| to                | VARCHAR   | 0x000000000003a3c2878a1df56a486c9683220456                         |                                                              |

## 6. Table: UniswapV2Pair\_event\_Sync\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2021-05-03 08:12:12+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 7095880                                                            | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0xfca61404142fd56fe1eb495280ed2fbbe9ce833f7b30273f663eadcb782aefdd | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 97                                                                 | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x0fb437607fd05bb7f1e324481eaa7c2909a15978                         | Address of the contract that produced the log                |
| reserve0          | VARCHAR   | 1242984204645876314501                                             |                                                              |
| reserve1          | VARCHAR   | 916479375782420515                                                 |                                                              |

## 7. Table: UniswapV2Pair\_event\_Transfer\_history

| Column            | Type      | Example                                                            | Description                                                  |
| ----------------- | --------- | ------------------------------------------------------------------ | ------------------------------------------------------------ |
| block\_timestamp  | TIMESTAMP | 2023-01-03 03:36:03+00:00                                          | Timestamp of the block where this event was emitted          |
| block\_number     | INTEGER   | 24454864                                                           | The block number where this event was emitted                |
| transaction\_hash | VARCHAR   | 0x3959aa18ecad41980238486058fed34ac45fe69adcf6ebef55d428847350b551 | Hash of the transactions in which this event was emitted     |
| log\_index        | INTEGER   | 0                                                                  | Integer of the log index position in the block of this event |
| contract\_address | VARCHAR   | 0x1087aed92c5329099ac9ee76ef9c14058c2803de                         | Address of the contract that produced the log                |
| from              | VARCHAR   | 0xbf87d4a808aade437348b61e80704433b0bbbe7e                         |                                                              |
| to                | VARCHAR   | 0xc3a8b55aff589c31b48fa3936d7d7648607726a4                         |                                                              |
| value             | VARCHAR   | 447213595499957938280                                              |                                                              |
